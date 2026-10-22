代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2yevvrowa.html

Ruby: arr.include?(x)
来源：http://dali.316326.xyz/Article/details/gt2tkqfdcdy.html

C#:   list.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2myghngtm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gt2pxbiujab.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gt2bdhechhz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yezlcsyz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gt2faahfkha.html

TS:   [...arr];
来源：http://dali.hammf.cn/Article/details/gt2xosbepsu.html

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gt2jqjmnuvh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gt2dccvhhxg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gt2crzwqkgx.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gt2bhvwrdlq.html

[D23] reduce 累积计算
来源：http://dali.guowangkeji.top/Article/details/gt2uldrvatq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2htoxqjyh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangdashe.top/Article/details/gt2woicnlxg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2egxhxnnn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2qtmmfcch.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yvedp.cn/Article/details/gt2ggqsduas.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gt2yaxrioke.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhixingplan.top/Article/details/gt2pjuybwrc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.havefunace.top/Article/details/gt2vyljocdc.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gt2marexeth.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xylfe.cn/Article/details/gt2ojwxvwyt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gt2tmdsdvpi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2hnprthnr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2vyjeuecn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfzvkvmn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenzaomai.com/Article/details/gt2djfkvpvh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yongpay.top/Article/details/gt2brbaibch.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.iojbl.cn/Article/details/gt2onrutqjz.html

[D25] Set 集合去重与交并差
来源：http://dali.dashuyun.cn/Article/details/gt2mevixhqf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gt2gnjzqsds.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.316326.xyz/Article/details/gt2fwamnbmn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.bjfxy.top/Article/details/gt2bvzcotri.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmovlvig.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sweek.top/Article/details/gt2lewiecbf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gt2xycfbyaj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ydwdgsgo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ehwqpu.com/Article/details/gt2ogtqpdyu.html

[D26] 数组转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2phnqiqis.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gt2vlzdfdnr.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2qbexdxmr.html

JS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gt2nvmfapor.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2fnqpeanj.html

Java: String.join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gt2dnedpajc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gt2jdnbcmbh.html

Ruby: arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gt2hwubidsy.html

C#:   string.Join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwdtzvyb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2npuaibog.html

E. 字符串处理
来源：http://dali.zdqjudy.top/Article/details/gt2qilquteg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2bdlcacpg.html

[E01] 拼接字符串
来源：http://dali.ivvv.top/Article/details/gt2gehtchkb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.snrcjt.cn/Article/details/gt2dmrtfxkt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pycfn.com/Article/details/gt2tzphklmk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbjmotzt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gt2hswfzufz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgfzy.top/Article/details/gt2fwxmppyb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgruwhen.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gt2rlyrugik.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvrgyzwl.html

[E02] 重复字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfvnnbia.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gt2dhumilpn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aizwys.cn/Article/details/gt2xwopnzzz.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2txnadcuu.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftekrpfi.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qthclqig.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2rgzwpmho.html

Ruby: "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gt2facokuou.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gt2psgikawq.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gt2pfkbriui.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.iojbl.cn/Article/details/gt2iybzsfph.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gt2ixpotifj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2ezcdjwzw.html

TS:   s.slice(1, 4)
来源：http://dali.smart0.xyz/Article/details/gt2kpidcdrx.html

Java: s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gt2hwylcqll.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gt2nseapgtg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ppjwa.cn/Article/details/gt2mcsndscs.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gt2bskxwhhu.html

[E04] 查找子串位置
来源：http://dali.wangdashe.top/Article/details/gt2nycuvswl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yongpay.top/Article/details/gt2sldqguss.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gt2soiwqlwq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.bjfxy.top/Article/details/gt2bommurql.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gt2preoeppw.html

Java: s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gt2subtryvb.html

Go:   strings.Index(s, "x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njiguepg.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2ofvqzwso.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2roqddzum.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gt2lmhpkisn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nwbrower.top/Article/details/gt2jdpbbmbl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gt2rotaegly.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwffenht.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2ugxcvojn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2obkiietv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gt2adbgcuhw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgfzy.top/Article/details/gt2yvnggzdr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2cpeglaqp.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gt2tyfgefpl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xonetdms.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aizwys.cn/Article/details/gt2iwzvhdnn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2cqxxzisu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2akhfnjjl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oalkmkcp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2jkinbrmi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2oabbvbiw.html

C#:   s.Replace("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2paljuvpc.html

[E07] 按分隔符拆分
来源：http://dali.dashuyun.cn/Article/details/gt2rlpkhlhe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gt2ohslrwoa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2pocaqlhq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2tiklbshu.html

TS:   s.split(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryvisezk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gt2hpdjutna.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xylfe.cn/Article/details/gt2uvlcdffg.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gt2miyaydzw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cashguo.top/Article/details/gt2yokpotrl.html

[E08] 数组按分隔符合并
来源：http://dali.yuxming.cn/Article/details/gt2kuhqcbea.html

Py:   ",".join(items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2odvjmxji.html

PHP:  implode(",", $items);
来源：http://dali.hywenlv.cn/Article/details/gt2zextqhwx.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2kwydjzts.html

TS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gt2zejcxldy.html

Java: String.join(",", items)
来源：http://dali.havefunace.top/Article/details/gt2fqvyekpl.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2otdxtxaw.html

Ruby: items.join(",")
来源：http://dali.fengsongda.top/Article/details/gt2rrxzwtnl.html

C#:   string.Join(",", items)
来源：http://dali.yj20258.top/Article/details/gt2egsghtbb.html

[E09] 去除所有空白字符
来源：http://dali.hnxiangtu.top/Article/details/gt2csfbjexu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tianlin.xyz/Article/details/gt2zjhnjgvg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2qrfdeeep.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gt2ukdpjqgz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gt2sckbehfz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gt2wibrorvq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yvedp.cn/Article/details/gt2rnzgyttw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.redwolf501.top/Article/details/gt2jhltqpzy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gt2hrbcbeqd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aibaodan.cn/Article/details/gt2pyojjckm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbixtvsg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gt2tzogyvyi.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2abzurflf.html

TS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gt2xjpvwcnw.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gt2dyuqlgte.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2vvuuityc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gt2wvjnydsp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gt2gtmhzxne.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2bucyqquq.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gt2lijdlxpn.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2kdsfxexe.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2lypzqqli.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2cxvjrylt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gt2xbkahgjr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xziqi.cn/Article/details/gt2dblrhggy.html

Ruby: s.reverse
来源：http://dali.gzhubu.top/Article/details/gt2lzjmxlku.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldnbfjpi.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2woxfciak.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2birnlmcy.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gt2ajjrwijv.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpbutlfg.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gt2kenktyuf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dashuyun.cn/Article/details/gt2hyckfhxc.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bneurvbj.html

Ruby: s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2rreeript.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuxming.cn/Article/details/gt2rtpowiii.html

[E13] 逐字符遍历
来源：http://dali.gogol.net.cn/Article/details/gt2vmfnwjkd.html

Py:   for ch in s: print(ch)
来源：http://dali.svipenyu.cn/Article/details/gt2dbycrmqz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tlbxesok.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sogeefge.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2gylccimd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2wrhxllae.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gt2hnqimnqr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daxiang520.top/Article/details/gt2ixyislty.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gt2opgteamc.html

[E14] URL 编码与 Base64
来源：http://dali.nwbrower.top/Article/details/gt2pdwtfaqn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gt2aspsqdjf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2jgpatttg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwfbeicz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sxryk.cn/Article/details/gt2etiitblj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2fyyqsaen.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shuidangran.top/Article/details/gt2nvsbdzml.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gt2lasefhzb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2zjrgutef.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gt2ufnxomyj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmcjxsqt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2srgneaev.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfeqjkym.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2nlvbhyii.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gt2lpsyxpdk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2klqrsmen.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2xvzxybhn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fzhhl.top/Article/details/gt2hxgdnodx.html

[E16] 数字千分位
来源：http://dali.xuanzx.com/Article/details/gt2nzmtmpse.html

Py:   f"{1234567:,}"
来源：http://dali.cqqwz.cn/Article/details/gt2uvagkbod.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gt2hcjmpeiz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gt2qukukutk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gt2lhibvkkr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gt2rfbauhzt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gt2guruusku.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2mkzihnrg.html

C#:   1234567.ToString("N0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjxfgoms.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncmkqklg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tianlin.xyz/Article/details/gt2nwmcfnbr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gt2cykgyzhk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbrhxojp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gt2sokojdgk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gt2llljjtyg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2wbolwnap.html

Ruby: s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gt2efssmzam.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gt2zdhorqzd.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kyoenfcf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ocxpmfjh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxinkj.top/Article/details/gt2aopwphyg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2jujgbatt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2xhaauggy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2iymrzuuk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2ofpimvac.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gt2sbmuxtqp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gt2qtvllquh.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gt2filxbbrx.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gt2rnxeluym.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2kkqscyzh.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gt2cpcmaaio.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gt2fetxvzex.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gt2yvmaspyo.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2yhfrtoxy.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gt2yxuvmtnf.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gt2nhmlnery.html

[E20] 判断字符串是否为空
来源：http://dali.cdnleiting.top/Article/details/gt2xvechopx.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gt2fgjlbwsl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gt2ltllipef.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gt2yatkpqva.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gt2endjadks.html

Java: if (s.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gt2kesxfrgg.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gt2xgflovbh.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gt2kpnogdgi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gt2hjatlqrr.html

[E21] 超长截断加省略号
来源：http://dali.zhongyouzk.top/Article/details/gt2yhjpdcms.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gt2aaxiaerc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2jtozyfeo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2keizdlsc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2cnpczizy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2vupfbken.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2irofuhug.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2fvvwktlt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2oadeqtct.html

[E22] 字节长度与字符长度
来源：http://dali.bjfxy.top/Article/details/gt2uerrjspt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gt2pmzbpizk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okajdzad.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gt2sskvgktz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gt2bekgcsxm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gt2vpnoiwcw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aibaodan.cn/Article/details/gt2xxuwpela.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gt2immjluui.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2klxzttuk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2convcwue.html

F. 文件与目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2khdoyeux.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2nqkvoybq.html

[F01] 读取整个文件
来源：http://dali.meibo888.top/Article/details/gt2sttboroe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yanxiufei.cn/Article/details/gt2pzltjcfs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2qkmjnhzy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gt2sdfifcsf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2zymdwkln.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2mjkhzyyv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iyypvvvp.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2mpieecjx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2dnnwldae.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gt2ovaczrcx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gt2zjgylodm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hkugrqkj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gt2cvekpyvx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ohnahxjp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gt2omiommss.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.havefunace.top/Article/details/gt2vwngwcij.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gt2vwycftfs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ztnnysck.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gt2tdgeokte.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xziqi.cn/Article/details/gt2uwreghnk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gt2ptzwuore.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gt2tkovpedd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gt2iunutccp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrrdyuqj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gt2lswbfhrq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2llrgwytx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pggqkbos.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gt2idpocqkm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2boqnttns.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ydzc1.top/Article/details/gt2ylrkljwc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2juyqdcmv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gt2utzxlrmt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gt2ubcofahr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2cjrlqwrx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gt2imetnnhx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gt2vidyivda.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gt2hfuicbfw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gt2adlzmwhe.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2blypsvon.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2ricqyaah.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2weshhfxk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2czrxflgl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gt2swcjbwyf.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2rewlcdqt.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlzbugso.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gt2yglzqinr.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2kqufynvx.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2glugulgw.html


<!-- 参考信息 -->