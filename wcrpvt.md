代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtyyvtvalb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gttbqqgcit.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gtlzwconni.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gtqvobbefj.html

Ruby: arr.tally
来源：http://dali.316326.xyz/Article/details/gtmvzuicno.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gtmyqsvmsn.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gtjvqglxjk.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gtqmbzdojh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guannengcc.top/Article/details/gtraxmcwhd.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtyvskykyf.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtafluokzy.html

Java: list.contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtxmdjkvee.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtboskshxz.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gtcfyadxtw.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgeoyiimk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gtdqsnaevl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gthiemkylu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gtxzltfstt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtuvtlfmhj.html

TS:   [...arr];
来源：http://dali.fengsongda.top/Article/details/gtpqhdkcbq.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gtllsnwhyq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.vqdsnc.cn/Article/details/gtzfriwxzz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjauopdz.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrmgnmkr.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gtmgjrinsk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jiagoushi.top/Article/details/gtrglsajgh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pycfn.com/Article/details/gtzlveduor.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtiuowltci.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtriwwlfia.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gtazsbemux.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtqkcdvict.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gogol.net.cn/Article/details/gtjbbpxrcw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gtmkudptrz.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gtplkbkwfg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.andypj.xyz/Article/details/gtlyfclexa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigfzy.top/Article/details/gtsnkyrklv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gtbzpgbkpz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtnxlipslr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gtfktfdjar.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gtbsdqrlmt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigufen.top/Article/details/gtgkznaapp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hywenlv.cn/Article/details/gtegjrzzsb.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gtcuzpyxtt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtteipzpap.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gtuntfawmn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gtknhsplkc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shangyingyoupin.top/Article/details/gtuewghvnn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gtjzndotdk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuanzx.com/Article/details/gtnmhrscos.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gtnvjgjggk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtdmhcmlyq.html

[D26] 数组转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtudeuns.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gtgkpdgqyl.html

PHP:  implode(", ", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtmuqzzagk.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtkivmjtns.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtcoiqhoyq.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtoovxqmxu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gthxrniaub.html

Ruby: arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gthnnppvid.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtsbdviqvw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbwcifvis.html

E. 字符串处理
来源：http://dali.wangshuangyany.cn/Article/details/gtmqrftdpo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlxhyokw.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gttpugxkow.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.vqdsnc.cn/Article/details/gtttkzwxoz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitrqfufy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtoopdghfk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtkpazupcw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gzhubu.top/Article/details/gtqwjprkwf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sysykeji.top/Article/details/gttdouocic.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gttwtzkunn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtffoemojw.html

[E02] 重复字符串
来源：http://dali.snrcjt.cn/Article/details/gtjvkloyyu.html

Py:   "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gtarlnxhop.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangdashe.top/Article/details/gtvlqeblvx.html

JS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtuzaksbyk.html

TS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxtjcyvh.html

Java: "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtxskzbyth.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fengsongda.top/Article/details/gthktftepp.html

Ruby: "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gtghaaetdc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gtcubyymuj.html

[E03] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtggkzpisn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zdqjudy.top/Article/details/gtkglapqpj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtbchftwar.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gthfbizcai.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtzfqvcjea.html

Java: s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtxwjmxlmz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jianghu66.top/Article/details/gtidwoukey.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gtviorgxnx.html

C#:   s.Substring(1, 3)
来源：http://dali.svipenyu.cn/Article/details/gtmjtkowrj.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gtakxwajgs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtqgaubpmt.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258888.top/Article/details/gtxfgdoipm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gtxcrpcerq.html

TS:   s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtxxffahmk.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtrfftjsfp.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gtlypbpvnx.html

Ruby: s.index("x")
来源：http://dali.bjfxy.top/Article/details/gtyhwefenm.html

C#:   s.IndexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtpbshdajh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gtofmqpbta.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sweek.top/Article/details/gtwxetvmzf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.bjfxy.top/Article/details/gtdcgkdqqd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gtghdkgozz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqumohhid.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtipalfgny.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuanzhike.top/Article/details/gtuwtohzng.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhongyouzk.top/Article/details/gtwqfjftyt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtrkkdnbxi.html

[E06] 替换子串
来源：http://dali.ybcxt.top/Article/details/gtrwclgeps.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gtvgaqvrcb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.svipenyu.cn/Article/details/gtegjshcts.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtwbzdhpfl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtunqdxfmd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtlbnwnzdw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gtyvrpaxph.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtykbrrnlm.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtyoosgxti.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gtwtnjzvmb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gogol.net.cn/Article/details/gtupkleuff.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtzemhvybt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cqqwz.cn/Article/details/gtkxmeyqhr.html

TS:   s.split(",")
来源：http://dali.zhixingplan.top/Article/details/gttdjosykj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangshuangyany.cn/Article/details/gtjiljciaf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtnmxacotu.html

Ruby: s.split(",");  s.split
来源：http://dali.zycfv.cn/Article/details/gtdzqtvzwe.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuanzx.com/Article/details/gtybjxtapd.html

[E08] 数组按分隔符合并
来源：http://dali.vqdsnc.cn/Article/details/gttlllzgrs.html

Py:   ",".join(items)
来源：http://dali.jinqigufen.top/Article/details/gtfcgukkcg.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gtwurxgyhc.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtnbllrhal.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtmufzigqs.html

Java: String.join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtkbtihxvf.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gtbizokgch.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtbgsljjmj.html

C#:   string.Join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gtykklsiwk.html

[E09] 去除所有空白字符
来源：http://dali.pengpengdd.cyou/Article/details/gtuqipmwbu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gtyrutxanl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gthxxarvcz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtvstciwna.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtwvafhdjw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtmjntufuf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gttagmxotb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gtbufqsjvz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtzruzidxr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gtfhgpcmin.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gthsqlbnzi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hywenlv.cn/Article/details/gtwdqijjdi.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtfnuoqyyx.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtgjumbybw.html

Java: String.format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtqljvracv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gttyjhrhsb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtramtsdia.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hfpthk.cn/Article/details/gtrxulkdhf.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gtqdmogkiv.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtpnvgovzz.html

PHP:  strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gtfkydvghz.html

JS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtqsivojuv.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtdwbikvpz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.9152youxi.cn/Article/details/gtlfurpslk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsrhfatq.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtmvynarlk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gtataxrvzt.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gtpccodhou.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtcrmmsiwd.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtkwwfwrtt.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtphkjoitw.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtfegzlsib.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gtwcfifnkg.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gtgqvrackh.html

Ruby: s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtzubiymll.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gtxbpulyxb.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gtysfftnmz.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gtytyzaeex.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aizwys.cn/Article/details/gturamzpqq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtglbsiopc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtgqadaqqt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtoxkltsdr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gtlnypspzk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gtriqoqeme.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zycfv.cn/Article/details/gtdijztwim.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gtohfcbjmh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.fengsongda.top/Article/details/gtznghzoeb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sysykeji.top/Article/details/gtcmodqcrf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gtjtxduedy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gtxhgphxch.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtwnhgdcvt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gtgwwawzid.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gttacciinr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtdjzlviag.html

[E15] HTML 转义 / 反转义
来源：http://dali.zycfv.cn/Article/details/gtdskddvzi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gtyerqzcrj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtwniaydcf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.vqdsnc.cn/Article/details/gtxldyrpvv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shuidangran.top/Article/details/gtgsrmjuxs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gtauxdhhpm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtamazitfl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gtoourubdu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxbtxppu.html

[E16] 数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gtoxmeptnd.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gtfjwhywti.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gtotsoeyeo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtivtpsvan.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtnhykuals.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gtknoiqzcg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gotoacloud.top/Article/details/gtnbpnikix.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtdghtickd.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gtdrwokekc.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gtmrdseujc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gtbnfkzzxv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtnszvzihj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcxcxoodp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtjetwrwmd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.c1oappe.top/Article/details/gtosonoduw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gtxczqcsxc.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdtphofh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gtjfkxfwgx.html

[E18] 模板占位符替换
来源：http://dali.wangshuangyany.cn/Article/details/gtnxqoeinv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gtpiabbqri.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jyoumei.cn/Article/details/gthdzpmcxv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtrpsnpnns.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gttncxesby.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gthtthdwcg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtbzwaxodl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ybcxt.top/Article/details/gtiiyrvryq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gtrhlpubmi.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gthgcrafto.html

Py:   s.splitlines()
来源：http://dali.jianghu66.top/Article/details/gtugsezvlo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gtbciyzgzp.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhcphcmg.html

TS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtkthbfbzt.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gtilcyjnov.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtaxumyqfa.html

Ruby: s.lines
来源：http://dali.smart0.xyz/Article/details/gtyiubetdm.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gtjnihlybh.html

[E20] 判断字符串是否为空
来源：http://dali.ydzc1.top/Article/details/gtbwtxtrgh.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gtcacuyvfq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gtrsevgcez.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gtlaklgduj.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gtvsjpdasb.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtbgduhbol.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtjzbaplsp.html

Ruby: if s.empty?
来源：http://dali.tian-w.cn/Article/details/gttdebnsqh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtaafdjmnt.html

[E21] 超长截断加省略号
来源：http://dali.cdnleiting.top/Article/details/gtmapdfbvs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hammf.cn/Article/details/gtdrpiztjg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtghpspbtx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtpkvbntpm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtyngokgcv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtsheiapor.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shangyingyoupin.top/Article/details/gtskxwfqum.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtpqspjjxt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtksisdlzj.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gtenusscdb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gtwimuvqcr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtntgnadyf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtnsnhrptf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtjixehojy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shuidangran.top/Article/details/gtdncvougk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yvedp.cn/Article/details/gtnmosuawb.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtkjawqvdh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gthkkuwdfm.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpdbksstf.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtjgvmrrub.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbyvmmgek.html

[F01] 读取整个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtsusjypso.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvczbmit.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqieailwd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gtpcwhwzio.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtfcktvwxb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtemjhshnp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gtflqjuoba.html

Ruby: File.read("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtunjqykum.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtbttqblpm.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gtizujyddl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gtojiqihie.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gtvvxroycp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gteybzrzgq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtvjgqyfhw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtsqolpjae.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gtvzjzeozn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gtiinwxcsh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yueranfly.top/Article/details/gtdsyuzxxg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplbleowx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guowangkeji.top/Article/details/gtuhgcwrsc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtpobkbjhg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gtpuzcjkyv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtkxahayrr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtipjuxwut.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhiwuduotai.top/Article/details/gtaczirzki.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtpxbafevi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtkovukjct.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gtdfzqqfuw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtzfczdpng.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gtexyfzyqk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtxmehpmlu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtgawlhuyz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbhavdde.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtwtzrngud.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenjidiqi.icu/Article/details/gtdgkmlkge.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gtdayxvjuq.html


<!-- 参考信息 -->