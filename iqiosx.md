代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gt2jlsunkis.html

JS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mihdbxcb.html

TS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2bzijyooc.html

Java: list.contains(x)
来源：http://dali.birdmap.top/Article/details/gt2drbaneok.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhzpvrdl.html

Ruby: arr.include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxzatbpu.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2ncwdttsj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.smart0.xyz/Article/details/gt2conwcyus.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gt2tpcxuhye.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zycfv.cn/Article/details/gt2pvzjnbdi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gt2dxxypbab.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gt2gwusosyn.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gt2ixbxhpwx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pycfn.com/Article/details/gt2ifcmbqgh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhoulong.xyz/Article/details/gt2csgkooin.html

C#:   new List<int>(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2bezrsdru.html

[D23] reduce 累积计算
来源：http://dali.tian-w.cn/Article/details/gt2ezvfanow.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sysykeji.top/Article/details/gt2pmkbjski.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2xvtqavxx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gt2mkhpylnd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqbnpkie.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wbcmyfsw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2htjytbpb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zdqjudy.top/Article/details/gt2xaulinem.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mohoqbve.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gt2qcdmvbfx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gt2relcrduv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gt2ovlgwflp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gt2xxuclozf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.mhx1999.top/Article/details/gt2cttsfetm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aizwys.cn/Article/details/gt2nxxhqmmu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sysykeji.top/Article/details/gt2aeckumdu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gt2nqraripc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.kuanghao11.cn/Article/details/gt2sexblxiv.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gt2iepujiif.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gt2llkoikss.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxwsevkp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uflszzuh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gt2krlylbba.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2hghfzbfh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xylfe.cn/Article/details/gt2hpvxhwvy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gt2jjipvmhx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.0kj1m.cn/Article/details/gt2tqtvipef.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gt2jspyflux.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gt2ndgfrivf.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gt2zzxpuenr.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2ehjidjhk.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2eerznlbm.html

Java: String.join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gt2igwfudtr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fzhhl.top/Article/details/gt2xxonofzo.html

Ruby: arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gt2cdfqyxgt.html

C#:   string.Join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gt2yhtuqzyt.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2pyxbokii.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gt2dncizmlq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hcolzymb.html

[E01] 拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2zmdlvian.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npwmnxkz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wepslmnl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gt2luthhwan.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gt2gbwoerti.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gt2zguwaufh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gt2scqblwip.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gquyjlqz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2srhchwen.html

[E02] 重复字符串
来源：http://dali.nwbrower.top/Article/details/gt2ugbxwttk.html

Py:   "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gt2eytlzzhb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuanzhike.top/Article/details/gt2sbjkxstn.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gt2tvfzpnrd.html

TS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gt2bpntfyfm.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gt2rpbknquf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shzxlz.cn/Article/details/gt2rhkuhimo.html

Ruby: "ab" * 3
来源：http://dali.yonumen.top/Article/details/gt2fuhiykpt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuanzhike.top/Article/details/gt2avhojbzy.html

[E03] 截取子串
来源：http://dali.hammf.cn/Article/details/gt2jizboezy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yvedp.cn/Article/details/gt2llfcnslz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2brsirjls.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2yecltpnz.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2mvyqqpmf.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2xuihokyk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aibaodan.cn/Article/details/gt2szenutcp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shzxlz.cn/Article/details/gt2gmjojdrj.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2uukfemwa.html

[E04] 查找子串位置
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dlyrdaue.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gt2yisbtvrq.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gt2teenougt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gt2duiafcij.html

TS:   s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gt2ntvlbfim.html

Java: s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2egmlouvh.html

Go:   strings.Index(s, "x")
来源：http://dali.jlsjyb.cn/Article/details/gt2dhogggjp.html

Ruby: s.index("x")
来源：http://dali.c1oappe.top/Article/details/gt2qhmrhgdz.html

C#:   s.IndexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2oepmqefw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gt2nywxquix.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gt2vbuosjvj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gt2qfvypugs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2hzzctheg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2qeffnvad.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gt2sdrxnvis.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cashguo.top/Article/details/gt2wuunxaum.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xylfe.cn/Article/details/gt2tuztfjai.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2arjmzvfi.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gt2nyuxrlgc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gt2ismwfquj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gt2ygnikxjz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2jlhdqehz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2cofybuhk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2vhcsroxy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2miwwbtda.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2capzrwld.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2pplngoqw.html

[E07] 按分隔符拆分
来源：http://dali.zhiwuduotai.top/Article/details/gt2vngxtsis.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gt2tpcenxka.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hammf.cn/Article/details/gt2nrryzsuc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2ioyubcxv.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gt2fwjqqvzi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.birdmap.top/Article/details/gt2fixioaln.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.bjfxy.top/Article/details/gt2adalhxyk.html

Ruby: s.split(",");  s.split
来源：http://dali.gzhubu.top/Article/details/gt2gatorjbo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ppjwa.cn/Article/details/gt2nchuwkyv.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gt2sxwlxeom.html

Py:   ",".join(items)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hsamafun.html

PHP:  implode(",", $items);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yggiludx.html

JS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gt2fydjxaps.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gt2xnbcbvci.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gt2gkxellox.html

Go:   strings.Join(items, ",")
来源：http://dali.havefunace.top/Article/details/gt2dldvascj.html

Ruby: items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwimlwwe.html

C#:   string.Join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lndgqfhw.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gt2jukkeuvr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gt2nvevqgpu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2golpulsx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gt2mgucgzcg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gt2umirvvpe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gt2klvzznrs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jianghu66.top/Article/details/gt2nwecwpmu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guannengcc.top/Article/details/gt2kljsktez.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gt2hfgatjmt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdwjbdsb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2apwtqtih.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxinkj.top/Article/details/gt2rufgxhgv.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnqrjokr.html

TS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2uhnjgdrq.html

Java: String.format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2euybynkw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2xgdwmfvt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2taoodamp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gt2zqohektj.html

[E11] 反转字符串
来源：http://dali.yj202588.top/Article/details/gt2yllovbyi.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gt2xbsbqoxg.html

PHP:  strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gt2onbrqmxe.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rwebbktf.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2avgokqpc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258.top/Article/details/gt2ktwmyyao.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gt2gwicqjfc.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gt2awmgcgzw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gt2wgrdkajb.html

[E12] 统计某字符出现次数
来源：http://dali.jianghu66.top/Article/details/gt2nonkusep.html

Py:   s.count("a")
来源：http://dali.pycfn.com/Article/details/gt2cyazacrk.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gt2kwkgnzxw.html

JS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gt2kecvxkzf.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gt2mvzoxczn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigufen.top/Article/details/gt2hulznejr.html

Go:   strings.Count(s, "a")
来源：http://dali.gaohongyu789.top/Article/details/gt2zszluhjp.html

Ruby: s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gt2dwcmfceu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnxiangtu.top/Article/details/gt2diksthcy.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gt2pmmvbhwv.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rmkojpcy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cucudq.cn/Article/details/gt2dxnkmhhy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2szfebuap.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2pcdaqvbw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2phjrgecu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gt2oejariad.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gt2beeotjoq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.mhx1999.top/Article/details/gt2sanwuubq.html

[E14] URL 编码与 Base64
来源：http://dali.jqgufenzy.top/Article/details/gt2sjpmjpkf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gt2kquyrgvt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gt2rnjbnpqr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jiagoushi.top/Article/details/gt2snanumvx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.0kj1m.cn/Article/details/gt2rxqdfzst.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntzsejjn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gt2lfxrwnpp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yvedp.cn/Article/details/gt2hflzcdpm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fengsongda.top/Article/details/gt2gwfqhuui.html

[E15] HTML 转义 / 反转义
来源：http://dali.xziqi.cn/Article/details/gt2clnmsmhg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gt2nhnlhntl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gt2hfnpevlg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gt2nvavdfia.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gt2cegivgsf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.redwolf501.top/Article/details/gt2qmzirqqg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tian-w.cn/Article/details/gt2swfmhhvq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gt2indyjfep.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gt2pouqevto.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gt2iyuasadx.html

Py:   f"{1234567:,}"
来源：http://dali.pycfn.com/Article/details/gt2wqiycbnt.html

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gt2tawgixxj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gt2pqlsuyyd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gt2fenllrhk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gt2kyrnbumq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gt2ttbwerrj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gt2hzgpqdqg.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gt2ocrmysny.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gt2hutpzqvh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sxryk.cn/Article/details/gt2adtgcnmn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gt2hhrbskja.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gt2tzxattmz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gt2ffyhnftc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuxming.cn/Article/details/gt2rbxqkciv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljyngkyr.html

Ruby: s.capitalize
来源：http://dali.hammf.cn/Article/details/gt2zaqnndew.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gt2wiizzwuf.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gt2mudxypaq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tian-w.cn/Article/details/gt2wbjuykak.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gt2nqrcvulp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2wwvygsjc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2moytstst.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2vezsnctk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2qtzkkius.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.bjfxy.top/Article/details/gt2lmobgscw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gt2vadalmgt.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gt2jvqymfpl.html

Py:   s.splitlines()
来源：http://dali.xziqi.cn/Article/details/gt2aivdoruj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2ctwzdixn.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdwwsxwa.html

TS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gt2gfuqveyx.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gt2yxivgmjo.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gt2bsnybnwf.html

Ruby: s.lines
来源：http://dali.hysaishi.cn/Article/details/gt2uhjfxedv.html

C#:   s.Split('\n')
来源：http://dali.hongshengwenyu.top/Article/details/gt2izfrxiaq.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gt2ykpkycyc.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gt2dhvgdunb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhengqikj.top/Article/details/gt2sogcrxkl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpcebjd.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gt2klquvgvr.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gt2vvetsfdr.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gt2llvbfisg.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gt2fvdrjmtm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2pvmjuokx.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gt2esmlyxxt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gt2mgxqjonk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2qjupwypi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2tqtpsdad.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2pwwiskhl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2ewjscbje.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ehwqpu.com/Article/details/gt2wyigfsng.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2eqyutgvg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2kfjdcluw.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmczfxgv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fijdimjp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2aplsbqfq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gt2lvvazkwj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gt2urjqladc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gt2cvezddng.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nwbrower.top/Article/details/gt2upddjqwf.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2xhwyasgu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gt2pjwuhyvx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2inlhpbve.html

F. 文件与目录
来源：http://dali.c1oappe.top/Article/details/gt2sncfzfyw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2hfsbdpjb.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gt2bcmqasot.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.iojbl.cn/Article/details/gt2odqwknyj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2ainfaxpy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.0kj1m.cn/Article/details/gt2mafncxcc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfqsrrah.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ziqbvzei.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gt2dhnomjjx.html

Ruby: File.read("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2afldkqez.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2ovinmdxj.html

[F02] 逐行读取文件
来源：http://dali.jianghu66.top/Article/details/gt2bibwttbm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bqgqdfvf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gt2tbztqzjk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gt2rmtqfurv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gt2jffsuwhh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gt2fkrymigb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plmmcpse.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gt2famkmipk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sufxvd.cn/Article/details/gt2wimlhdpw.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gt2iseaabfr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gt2uwadqnmt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gt2uhsqrcsl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2unrxqojv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gt2tnhygfoo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gt2lbhtwzzc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gt2jytyrkha.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sxryk.cn/Article/details/gt2rlvjxzyl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2yraerjex.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gt2ifvcazot.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2mrmdnkpw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psgnicbc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nuqsexfu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxweypir.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yueranfly.top/Article/details/gt2ezrxbcxu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2owtsnjlk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gt2aghqwxbp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gt2cisnztvt.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gt2rtysctaw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gt2bfjghqgl.html

PHP:  file_exists("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2ijdedphq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2zmtuwmfo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2teidkkzl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2adofxvhw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gt2abmsknay.html

Ruby: File.exist?("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2unuufpaw.html


<!-- 参考信息 -->