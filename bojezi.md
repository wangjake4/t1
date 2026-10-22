代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gtluhyapeg.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gtmecqamto.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gtnqtlhwse.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gteagjhxoh.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtujkygtzj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gtzteybnrk.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyincudww.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aizwys.cn/Article/details/gtzazkcyyg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.bjfxy.top/Article/details/gtylolseqm.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gtbfkzrran.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gtkcaxdkgs.html

[D18] 扁平化嵌套数组
来源：http://dali.gzhubu.top/Article/details/gtmfpjnagm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gtgccssjkm.html

PHP:  array_merge(...$nested);
来源：http://dali.yvedp.cn/Article/details/gthytcfojt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guannengcc.top/Article/details/gthrgbhkwr.html

TS:   nested.flat();
来源：http://dali.hongshengwenyu.top/Article/details/gtytgsvhdk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.c1oappe.top/Article/details/gtgkfovxol.html

Go:   // 手写双层循环
来源：http://dali.fengsongda.top/Article/details/gtdhzsvwhe.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gtcpurcffr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtsafsulyk.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gtgvophhnh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gtzcvsnxdk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtjxrqzuko.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuanzx.com/Article/details/gtfuvbbjtl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gtxtzzhkpz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtjpcrfwge.html

Go:   // 手写 map[string][]T
来源：http://dali.chenlongwang.top/Article/details/gtpbzsqcoi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenzaomai.com/Article/details/gtagissiwo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gttsbldcqb.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gtnspwazij.html

Py:   Counter(arr)
来源：http://dali.sweek.top/Article/details/gtchfyvune.html

PHP:  array_count_values($arr);
来源：http://dali.jiagoushi.top/Article/details/gtcrvdimuo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtqqowvhxf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtrhwvkmjc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.feifeiyinyue.top/Article/details/gtxutubvbz.html

Go:   // 手写 map[T]int
来源：http://dali.0kj1m.cn/Article/details/gtvzryjoax.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gtsrcdaauh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gtqnngnwlz.html

[D21] 判断是否包含某元素
来源：http://dali.haohaochexian.top/Article/details/gtscfkmkcf.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gtctghprvl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtddrjubxp.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtezlcldfs.html

TS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtgxtnkygx.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gtyzjiuysh.html

Go:   slices.Contains(arr, x)
来源：http://dali.havefunace.top/Article/details/gtisrkyckd.html

Ruby: arr.include?(x)
来源：http://dali.tian-w.cn/Article/details/gtvxdnbbaa.html

C#:   list.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtpqxoxklh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.iojbl.cn/Article/details/gtlvmerblh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtedhzfdsx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenjidiqi.icu/Article/details/gtdcnrwebv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gtpbrodmzk.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gtwtycfcvt.html

Java: new ArrayList<>(list);
来源：http://dali.hfpthk.cn/Article/details/gtveyxtehy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zycfv.cn/Article/details/gtdkhtwhll.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gtxyoebryb.html

C#:   new List<int>(list);
来源：http://dali.c1oappe.top/Article/details/gtqwpxqjrg.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gtgelmcjdl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gtumlghbfg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gtxmisxtzb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtdqncqerm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtkuvrfqcg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yangfankeji.com/Article/details/gtwuoaupch.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gtozbmjctr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cashguo.top/Article/details/gtgyzlxuuh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtirxomwwk.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gtpjlnrgvt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdxnxgph.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tanke756.top/Article/details/gtzxpwwsgy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gtksyupkzy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gtrdmzkwtz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gttfgkcufb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabmqugwo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuanzx.com/Article/details/gtuuxvmuwv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gtrierlare.html

[D25] Set 集合去重与交并差
来源：http://dali.zhengqikj.top/Article/details/gtxcjwaoko.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gtllupwkvh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gtedecodrj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjoijsxmq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cucudq.cn/Article/details/gttppbnifc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.havefunace.top/Article/details/gtmvpfedij.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfgnbhoz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gtkmxgriij.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtbztkmgta.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtjzrbqdnk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gtbcqthqzz.html

PHP:  implode(", ", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlkqtgxo.html

JS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtppbvcoxu.html

TS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmazbbjgz.html

Java: String.join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtgnlbiruq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gttucseezh.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtfcmriwps.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpcqergq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkgvynejl.html

E. 字符串处理
来源：http://dali.zhongyouzk.top/Article/details/gtgvefynck.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvmynhiz.html

[E01] 拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtnncwmfdd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zycfv.cn/Article/details/gtetopnine.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhongyouzk.top/Article/details/gtxtaomizf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtlddjaqlu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtinwuxmvw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sysykeji.top/Article/details/gtvxjmmukm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gtsokskbyw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gtwcvxonsg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtxxhbznoq.html

[E02] 重复字符串
来源：http://dali.0kj1m.cn/Article/details/gttkqixjvm.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtrjqjtlus.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtjumasguw.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtsbwavxuo.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtjxzljczz.html

Java: "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtjhzgrown.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gtiporqvem.html

Ruby: "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtaykxyhsh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtqnncrsvp.html

[E03] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtowhbltyy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gtbisltswt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtpyvrdzfc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtfbgcgnou.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtrbswwauu.html

Java: s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtpedgwkxl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tanke756.top/Article/details/gtdpcuywzx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gtttfmiahl.html

C#:   s.Substring(1, 3)
来源：http://dali.chenjidiqi.icu/Article/details/gthyffivcl.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gtgrktilfe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gtygulejcc.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gtsouxnqxj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.meibo888.top/Article/details/gtgdiduyim.html

TS:   s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gttsnpjzrh.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtxnryfutb.html

Go:   strings.Index(s, "x")
来源：http://dali.chenlongwang.top/Article/details/gtjoxqzrsu.html

Ruby: s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtwvlaxess.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtfhultojw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yanxiufei.cn/Article/details/gtkscfiigt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqiyapgp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.316326.xyz/Article/details/gtauotlels.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtbbsrmjvn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtvsxpzqtf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtscgrawuy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ppjwa.cn/Article/details/gtmafanuks.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.c1oappe.top/Article/details/gtbxnverbv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtcibclldt.html

[E06] 替换子串
来源：http://dali.chenzaomai.com/Article/details/gthuvfyana.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gtuuuuonyg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gtrglaxhbr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtqjfxgfvl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gttnbartdj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtvxcdmoqt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gtxnyamwfe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtjclksboh.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtfbhzyfgn.html

[E07] 按分隔符拆分
来源：http://dali.tianlin.xyz/Article/details/gtsqskxrdj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuxming.cn/Article/details/gteomdqtxm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gteganqqhy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gtfugccdlx.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gtgzrxtykb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gtpwvvunzo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cdnleiting.top/Article/details/gtxqsugwgp.html

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrvhqrid.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gtaraoxejn.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gtpbfkrcgv.html

Py:   ",".join(items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiynmetjl.html

PHP:  implode(",", $items);
来源：http://dali.guowangkeji.top/Article/details/gtjrvapzcl.html

JS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtgozlacfl.html

TS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtkqbymlhu.html

Java: String.join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtrkxhavfz.html

Go:   strings.Join(items, ",")
来源：http://dali.sweek.top/Article/details/gtxskwkwvs.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtuvpclcrl.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtmqeitpyw.html

[E09] 去除所有空白字符
来源：http://dali.jinghuilouyu.cn/Article/details/gthykpoxmo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtadhdbwak.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gtjyjutwrh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtoaxsjzwa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gttekkwzik.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtffznrbkf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gtpleiljeb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gteivykbgu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gtsmljuhju.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gtvavizgwn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gticlepxfd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gtczafeeue.html

JS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtxggwxeve.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtdueebmev.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtgrlhuwyh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtbqmxldnb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtkkysypgh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sxryk.cn/Article/details/gtqrgkhezz.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gtmznferhb.html

Py:   s[::-1]
来源：http://dali.yj20258.top/Article/details/gtglscgblz.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtvzmjgfbb.html

JS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtrubhecum.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtgipsygkw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtrccbcbev.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gtlaolwviq.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtgpmnlkps.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtddqivmcj.html

[E12] 统计某字符出现次数
来源：http://dali.aibaodan.cn/Article/details/gtxzherhic.html

Py:   s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtxpzlcsdw.html

PHP:  substr_count($s, "a");
来源：http://dali.sufxvd.cn/Article/details/gtpdgyfwpt.html

JS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtyoitauer.html

TS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gtddirfrss.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuanzhike.top/Article/details/gtqeosplmi.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gthhpsophd.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gtiqqwfqae.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gthspqjkos.html

[E13] 逐字符遍历
来源：http://dali.tanke756.top/Article/details/gtpdkneltr.html

Py:   for ch in s: print(ch)
来源：http://dali.ydzc1.top/Article/details/gtiysfweif.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gtvmsilcoz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtuzaqdijo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtpubdgzew.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gtzzchlwvy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gtayrmowyh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gtwdbobihl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtwptmaupp.html

[E14] URL 编码与 Base64
来源：http://dali.feifeiyinyue.top/Article/details/gtenwrumwp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gtrzzhpmbg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.iojbl.cn/Article/details/gtoxhstcql.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gtrsmptnoc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.vqdsnc.cn/Article/details/gtcumxkssj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gtatjanyrg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.iojbl.cn/Article/details/gtbvfwbpch.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tanke756.top/Article/details/gtnpfecyof.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.iojbl.cn/Article/details/gtnefrvqar.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmreunwxo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gtasxqusgx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gtmjipihvq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwydisgpg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yueranfly.top/Article/details/gtbmhnlmnn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhbjkvns.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.meibo888.top/Article/details/gtncwsaaqd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gtnsewtdjq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ehwqpu.com/Article/details/gtjyvxodhj.html

[E16] 数字千分位
来源：http://dali.wangdashe.top/Article/details/gtdcurldvf.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtidmloasv.html

PHP:  number_format(1234567);
来源：http://dali.hammf.cn/Article/details/gtlsjitsai.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtzvzpwgrg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtfvtfiego.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.smart0.xyz/Article/details/gtnvbswdni.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pengpengdd.cyou/Article/details/gtglnqstwb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jianghu66.top/Article/details/gtvnaerblz.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzlpzrni.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gtfzmoytux.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gtkhmselgh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.snrcjt.cn/Article/details/gtteiwevej.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtzgfaeyri.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtxjapkgxp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gtmtfplcdy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gtftvzuepc.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtxikydbse.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gtgeszucgt.html

[E18] 模板占位符替换
来源：http://dali.andypj.xyz/Article/details/gtaehhkoes.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvktdklso.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxuanxn.top/Article/details/gtwyupdunk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtxwxfjpzs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtksyfazxg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtyxirndsu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtzcwhwuga.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.vqdsnc.cn/Article/details/gtdujdrdbo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.andypj.xyz/Article/details/gtdexflxcs.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gtzshewdag.html

Py:   s.splitlines()
来源：http://dali.nanxuanxn.top/Article/details/gtjlnytjgr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gthlipzlgz.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtytfgtxjv.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtxktcmkvc.html

Java: s.lines().toList()
来源：http://dali.zhengqikj.top/Article/details/gtvmpetlgu.html

Go:   strings.Split(s, "\n")
来源：http://dali.jiagoushi.top/Article/details/gtyccpkwdh.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gtswkfylus.html

C#:   s.Split('\n')
来源：http://dali.vqdsnc.cn/Article/details/gttpmqfkkq.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gtnugjyvgx.html

Py:   if not s:
来源：http://dali.vqdsnc.cn/Article/details/gtzudkszvg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gtzsnklmud.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwwdolxt.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtsdhbzpep.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagqolqkg.html

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gtlnsswsfx.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gtjreykjag.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtliabaada.html

[E21] 超长截断加省略号
来源：http://dali.0kj1m.cn/Article/details/gtpnddeawr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tianlin.xyz/Article/details/gtffmsgebw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtkkutimet.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtgdfmpvct.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtvcvdhduh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtjrvivceh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj202588.top/Article/details/gtajnohqzu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtszqcztjw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcmryske.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gtdmlrjhkq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pycfn.com/Article/details/gtgtshpobt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtnguvwlma.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtjrbkewkt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtemrzigth.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tanke756.top/Article/details/gtytltdgbo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xziqi.cn/Article/details/gtgegqrbja.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtpkjhnann.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtdchasfjo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtrfftfbas.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gtuuyqvzsy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtiwjksxln.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gtgaursfsl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.c1oappe.top/Article/details/gtkhzopxuk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gthawlmode.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.iojbl.cn/Article/details/gtnlxyiviw.html


<!-- 参考信息 -->