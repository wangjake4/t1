代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtgnwpibbj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtkamnopeu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gtxafhposr.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gtkykneaqw.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gteyypxpya.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gtgbaosmwz.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtgttbrd.html

Py:   x in arr
来源：http://dali.smart0.xyz/Article/details/gtzogcruxq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hywenlv.cn/Article/details/gtsfzdqjnt.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtsuysrewf.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtzzvdbgeq.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gtrkxpvogh.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gtuaflmbxe.html

Ruby: arr.include?(x)
来源：http://dali.xylfe.cn/Article/details/gthorqfpth.html

C#:   list.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtwaavbkjy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.316326.xyz/Article/details/gtkadqfqlb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtlblafbpj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gtorichoaj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtrecgnytt.html

TS:   [...arr];
来源：http://dali.hywenlv.cn/Article/details/gtgboqwaup.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gtrgqykqtv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gtujuhmdcl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.haohaochexian.top/Article/details/gtiipqqxvu.html

C#:   new List<int>(list);
来源：http://dali.jianghu66.top/Article/details/gtssgnijun.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gtaqbmcrug.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtecjzinru.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtqboskrhf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtvjrnjnjc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtbnxobkqb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gtipqcowhd.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtyzvrxtko.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yueranfly.top/Article/details/gtoybotgen.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gtnairtwei.html

[D24] 字典 / Map 基本操作
来源：http://dali.sweek.top/Article/details/gttgjoxlma.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gtcwvvubnf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgfzy.top/Article/details/gtnpvdnkbo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtvfwsbbmr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtlermxyau.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnxiangtu.top/Article/details/gtouezrpgh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.haohaochexian.top/Article/details/gtktynvjui.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gtgauhkwdq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sweek.top/Article/details/gtjwxkcsds.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gthuafhzkb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtdirxvapd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fengsongda.top/Article/details/gtlahbasyv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gtrxsqdrol.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzqebpdd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtydcolokx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gtcapoedcx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gtpfncfphm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gtefhcwgyz.html

[D26] 数组转字符串
来源：http://dali.ppjwa.cn/Article/details/gtxvteyrep.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gtxfhgrcnd.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtbjwacfnh.html

JS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavrtoxgh.html

TS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtfeiacoxf.html

Java: String.join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gthhyqoznj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guowangkeji.top/Article/details/gtcncxrubf.html

Ruby: arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gthfseoast.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtrkcuuhns.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhiogwxj.html

E. 字符串处理
来源：http://dali.havefunace.top/Article/details/gtitjvfrxc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtomjealoj.html

[E01] 拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gtltsgkkjk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.mhx1999.top/Article/details/gtfvrsetwz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gtowiyuibv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtjbwakaxh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtpuhsieha.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxuanxn.top/Article/details/gtmmuslvvv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gtvguwkkzc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gtaikosfej.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtofiyowoo.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gtewihuult.html

Py:   "ab" * 3
来源：http://dali.cheryme.top/Article/details/gtckyhdzfi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fzhhl.top/Article/details/gtzafyjctf.html

JS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtwvfrigsz.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtxcwloycn.html

Java: "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtpxumvngy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjodsxaak.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtskrqeync.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyputrxfe.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtqifbsoli.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gtzunyrcsu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gthusphuku.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtnvpkdkjw.html

TS:   s.slice(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtievgkivv.html

Java: s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtujirkqua.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zycfv.cn/Article/details/gtcvrukggo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxuanxn.top/Article/details/gtfzccftsz.html

C#:   s.Substring(1, 3)
来源：http://dali.jianghu66.top/Article/details/gtbsbemhno.html

[E04] 查找子串位置
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcujrpqp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtgfufosqs.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gtjiytyjra.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gtlevrjpab.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtenmcokra.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtpinhykrk.html

Go:   strings.Index(s, "x")
来源：http://dali.yvedp.cn/Article/details/gtimczvpcd.html

Ruby: s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtssqcqahp.html

C#:   s.IndexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtrgkeoppc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gttvaidzlm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.meibo888.top/Article/details/gtpekwpeqz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jlsjyb.cn/Article/details/gtprwfluaj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtnstbnjko.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ehwqpu.com/Article/details/gtpvoorhkp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtarofmvxh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gtbqljcrcj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gtmgfwygyf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tian-w.cn/Article/details/gthnhmgjqq.html

[E06] 替换子串
来源：http://dali.yj20258888.top/Article/details/gttiaajkaw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtpdfiurii.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gtmhqnqfdb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtpyxzzkni.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtefvpngwl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuopbqxi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gteizcdcsg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtfgcsfice.html

C#:   s.Replace("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtegsueqvn.html

[E07] 按分隔符拆分
来源：http://dali.shzxlz.cn/Article/details/gtzhnmiwjl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gtputhjunt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtghitajky.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yangfankeji.com/Article/details/gtmxojnimb.html

TS:   s.split(",")
来源：http://dali.0kj1m.cn/Article/details/gtwmnejvom.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gtgzelmcjv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gtvjhoeclk.html

Ruby: s.split(",");  s.split
来源：http://dali.mhx1999.top/Article/details/gtmwcnxmut.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.iojbl.cn/Article/details/gthtwcpkig.html

[E08] 数组按分隔符合并
来源：http://dali.jqgufenzy.top/Article/details/gtqnrqnqez.html

Py:   ",".join(items)
来源：http://dali.cashguo.top/Article/details/gtnpctrsmf.html

PHP:  implode(",", $items);
来源：http://dali.guowangkeji.top/Article/details/gtqhazsjte.html

JS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtqtffmpps.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtniqxrzmp.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gtocyurqvn.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gturgtuppr.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtqdfypaqu.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtsjlvbats.html

[E09] 去除所有空白字符
来源：http://dali.tanke756.top/Article/details/gtoniwmtmg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gthtnllkfy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sweek.top/Article/details/gtnodyfxas.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtrelytmkh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtjtgyhtth.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtimzywbdl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gaohongyu789.top/Article/details/gtomrzhidx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gtrqaghivk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shuidangran.top/Article/details/gtxtqgxprp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gtjguxqyvt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtvoqhjutu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.iojbl.cn/Article/details/gtlheuhlsw.html

JS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtkyolypit.html

TS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtepskzlgm.html

Java: String.format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtueuapwip.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjesfsoyo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtkpgsrelc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gtnhpietsd.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gthxrqkmto.html

Py:   s[::-1]
来源：http://dali.redwolf501.top/Article/details/gtornlnysl.html

PHP:  strrev($s);
来源：http://dali.yj20258.top/Article/details/gthkrqpxtr.html

JS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtlwqxloje.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtborrhudg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtfpusgrdz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gtsqspidok.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gtradeizxo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtjjtbmwnq.html

[E12] 统计某字符出现次数
来源：http://dali.snrcjt.cn/Article/details/gtqwmvbwum.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtlzidtdqm.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gtjwliiazt.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtgmhsuhoz.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtqdnnkxzl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gtttadtcmj.html

Go:   strings.Count(s, "a")
来源：http://dali.xinyue.icu/Article/details/gtnipyruxa.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtriabkhuv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gtyloocklx.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gtqrlpsett.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gtufeffzrc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.mhx1999.top/Article/details/gtiwsqcnxd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtazqxddqr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtaepkbyer.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqfqjmvto.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gtezrlzxni.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtnvdnrlhk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gthavgahyb.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gtflpjjqje.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtivdpwpra.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shuidangran.top/Article/details/gtxyozcrzc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gtnfxlgbdw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gtqicdzgex.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtapamkzki.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cqqwz.cn/Article/details/gtnmttrbdj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gtdbktcpfd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gtglgqlawr.html

[E15] HTML 转义 / 反转义
来源：http://dali.c1oappe.top/Article/details/gtjkuqagws.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtwwrlords.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gtutgafcsn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gtmookvvzh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gtbfyyvarq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gtgjcpjocl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtbxdhzquq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtesqeguma.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dashuyun.cn/Article/details/gtacqzkwrr.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gtqouhugyx.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gtckobmvpm.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gtkwshywfb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtyjmfjkbs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gthdcamzsa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtpvsdakuc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gtoxxmhtlw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtxbzemita.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtzjhjijcv.html

[E17] 首字母大写
来源：http://dali.cqqwz.cn/Article/details/gtoihoccfh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gtvoeucdbz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gtvjgydpcb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtdqwtfkag.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtxwmleckq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fengsongda.top/Article/details/gtmohlvmom.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.0kj1m.cn/Article/details/gtdniqkats.html

Ruby: s.capitalize
来源：http://dali.ivvv.top/Article/details/gtqrbzpxtm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shuidangran.top/Article/details/gtcxdfbnmw.html

[E18] 模板占位符替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxwblcom.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gtovdxtihm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gtjnjdvccw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtatczodvn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtapmyqpor.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttigjzhob.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtzcsahioy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gtkbmqqaxv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gtoiagqhmn.html

[E19] 多行文本按行拆分
来源：http://dali.ehwqpu.com/Article/details/gtutnhrmgi.html

Py:   s.splitlines()
来源：http://dali.chenjidiqi.icu/Article/details/gtzxgiqnki.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtnjvwhanz.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtfdydeflz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gtglnqsadp.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gtpcegnhre.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtrpyyqqme.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gtpsvloxxv.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyokoadk.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gtujivkvim.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gtphijtlfi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gtgvdsdjpf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtosrnannb.html

TS:   if (s === "") {}
来源：http://dali.hywenlv.cn/Article/details/gttmzcfhev.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtkkhylnly.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnffgermt.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gtsjhicemy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sufxvd.cn/Article/details/gtaxkxzohp.html

[E21] 超长截断加省略号
来源：http://dali.sweek.top/Article/details/gtmhozccfn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gtkbuisezf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtyzrcdoms.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtlrqjulwa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtqwwygijr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtgzasnpwb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gtksrjkufb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtnkowabqk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtcrjalivj.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gtfbuoeqgk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtkmjgjstq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtxpvypyey.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtueknpdjt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtergeccgz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ivvv.top/Article/details/gtxnexvowj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqcmwhmd.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gtrrgxvmot.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gtflazsfdt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtocacbmgh.html

F. 文件与目录
来源：http://dali.smart0.xyz/Article/details/gtynxlvbxc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthkkxodhz.html

[F01] 读取整个文件
来源：http://dali.cdnleiting.top/Article/details/gtgbtrabmf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hfpthk.cn/Article/details/gtuhhbnelm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtqiydlkgt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxuanxn.top/Article/details/gtrzwuxkdt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hammf.cn/Article/details/gtwyrkvygg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtjvrbtywa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gtivkkgfys.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtwsnaspje.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtmzldgars.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gtxpbxbaoc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ehwqpu.com/Article/details/gtwoaxvzhs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gtumhbukvx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gtwbutwbtp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtynulymme.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtpbepkczp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqsqphvs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugctmcej.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrfuctfq.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gtavtzhdpp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gtkjsytnwb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtsalimpvs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtgskmizym.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtqhtvtnrw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gtboummdwi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gtaeofinky.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gttynaeeyr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtpxkpettt.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gttzgwdbje.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtewqqcclp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gthyfebxdk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtefiamxso.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtolodzyzy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zdqjudy.top/Article/details/gttqxlfxds.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtvukhiizv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gtitsotgnk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gtuschhinq.html


<!-- 参考信息 -->