代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtecdmkmnq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtjyshlosa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gtjdeqziym.html

Go:   // 手写循环累加
来源：http://dali.cqqwz.cn/Article/details/gtytzjadgv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtvdhmyebj.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gtaqskmubs.html

[D17] 最大值与最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtxaghviue.html

Py:   max(arr);  min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyhqzdnx.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gtdhgbvxiy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gtjnjlqegw.html

TS:   Math.max(...arr);
来源：http://dali.c1oappe.top/Article/details/gtwsppnoqc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.iojbl.cn/Article/details/gtemwnnmny.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtkyujobyb.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gtkzngodsd.html

C#:   list.Max();  list.Min()
来源：http://dali.zhengqikj.top/Article/details/gthfretfbs.html

[D18] 扁平化嵌套数组
来源：http://dali.daria6918.cn/Article/details/gtccysomxs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hongshengwenyu.top/Article/details/gtpyuxfycg.html

PHP:  array_merge(...$nested);
来源：http://dali.yonumen.top/Article/details/gtpvjenlun.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gtldkcvoau.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gtkbyioeme.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gtydzbivfc.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlamdzpyy.html

Ruby: nested.flatten
来源：http://dali.cqqwz.cn/Article/details/gtapdgfymd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tanke756.top/Article/details/gttgiaqfyh.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gtrutpvgfp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gtxgfcbexq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenlongwang.top/Article/details/gtlrkzrowr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gtdmigsblm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gtyohlzhet.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtpkqqzhwl.html

Go:   // 手写 map[string][]T
来源：http://dali.chenlongwang.top/Article/details/gtukcomgbg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gtzqquryfp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gtfwtilery.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gttqaocfra.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gteyivhiva.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gtzwfinpjo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtamzoivvb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtsjdfvvul.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gtpqfwluje.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxkidszy.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gtzliehsvd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gtysgumvrm.html

[D21] 判断是否包含某元素
来源：http://dali.shangyingyoupin.top/Article/details/gtyizckfjz.html

Py:   x in arr
来源：http://dali.nanxinkj.top/Article/details/gtjxliyuuf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.kuanghao11.cn/Article/details/gtgqejolaz.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtaytkvasr.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtqamxhrxe.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtlaqjdyfg.html

Go:   slices.Contains(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtelwxyhpn.html

Ruby: arr.include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtbpwetvao.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtiigsptiy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.iojbl.cn/Article/details/gtesepexjz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gtinxenqqi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ydzc1.top/Article/details/gtqrmssbvl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xylfe.cn/Article/details/gtnsqqefzn.html

TS:   [...arr];
来源：http://dali.jqgufenzy.top/Article/details/gtxlyqgowf.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gtkdjezrtl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tanke756.top/Article/details/gtkspzmoil.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gtfcmfboqn.html

C#:   new List<int>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjzpjltt.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtrjnoubsr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gtoaurnimj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhengqikj.top/Article/details/gtqqihezom.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwznjstw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtmaeimcff.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvveszuyn.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtchcetnny.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hywenlv.cn/Article/details/gtdsleylbr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xziqi.cn/Article/details/gtkewgteqb.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gtigsrkual.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hammf.cn/Article/details/gtnuwkfaiq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.9152youxi.cn/Article/details/gtdnoppfmc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gtcqpjjbma.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtvfjjkhes.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gtaghrlsfe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangshuangyany.cn/Article/details/gtkhdpzktk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuxming.cn/Article/details/gtuveiltxd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gtxdmuqsne.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gtpxmjhowh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gtepijlzmo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sufxvd.cn/Article/details/gtwxfunwpb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gtkrfvaqdw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkbhcgtv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuanzx.com/Article/details/gtirgtnemz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gaohongyu789.top/Article/details/gtyfisukst.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtnavsqenu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuanzhike.top/Article/details/gtnyhahcjm.html

[D26] 数组转字符串
来源：http://dali.pycfn.com/Article/details/gtajotfzvq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daxiang520.top/Article/details/gtbdktrzdi.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gtfiiluhqw.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtrlclgbim.html

TS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtrrbmcdgh.html

Java: String.join(", ", list)
来源：http://dali.sweek.top/Article/details/gtvbwpttot.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhixingplan.top/Article/details/gtalzbchbv.html

Ruby: arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtxqwreacu.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gttljtindn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqexboon.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gtmppqflop.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtlnjwakhm.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtwdnntssi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shzxlz.cn/Article/details/gtjkimnckj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yonumen.top/Article/details/gtusgxnlmk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gtoucehorb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtlnicvwem.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daxiang520.top/Article/details/gttsjrjejo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gtyljeqser.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yonumen.top/Article/details/gtajdcyjtj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtftzegaor.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gtfureoxfd.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtxkbwfonu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jyoumei.cn/Article/details/gtxgybrzjg.html

JS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtdnotzagf.html

TS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtdnyvrgrx.html

Java: "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtecrceiew.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cdnleiting.top/Article/details/gtujxhqmjm.html

Ruby: "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gtyvisjwgk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.andypj.xyz/Article/details/gthvvlkdvj.html

[E03] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtdaiupvft.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gtuguoqggi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtmnxxwydh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtdhofmzlt.html

TS:   s.slice(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gteesqmfcs.html

Java: s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtlvbiezlc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtordogkpf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.haohaochexian.top/Article/details/gtdprteevj.html

C#:   s.Substring(1, 3)
来源：http://dali.pycfn.com/Article/details/gtcjlrfvmv.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gtugrsvzyz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtjlrowtfj.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gtbkrphido.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gtphiputan.html

TS:   s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtjjiqwsee.html

Java: s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtrurmusxj.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdlarhod.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gthagomrig.html

C#:   s.IndexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtqplwhuss.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gtggnsfdaa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xylfe.cn/Article/details/gtqciyoewz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jiagoushi.top/Article/details/gtymsnfbfq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtyrdwcqin.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xylfe.cn/Article/details/gtiehcrjli.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtvnvbypds.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fengsongda.top/Article/details/gtyrdhaamv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gtfvnmztuo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sweek.top/Article/details/gtwholmvgz.html

[E06] 替换子串
来源：http://dali.meibo888.top/Article/details/gtxvrjznhv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtwdkoulua.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gtfgbelort.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtqymlskgu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtsetkgldb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivsalhdm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtiugtrpwi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtwduafiuo.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtdqujhuun.html

[E07] 按分隔符拆分
来源：http://dali.xylfe.cn/Article/details/gtzxpijlpu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.quarkkingdee.top/Article/details/gtisgqsxve.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtisvjvhxb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ydzc1.top/Article/details/gtmoffmrxj.html

TS:   s.split(",")
来源：http://dali.havefunace.top/Article/details/gtwerfieyy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ybcxt.top/Article/details/gtpxqydcww.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gtgmslkwez.html

Ruby: s.split(",");  s.split
来源：http://dali.sufxvd.cn/Article/details/gtoqqwsfgy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gaohongyu789.top/Article/details/gtyhkhshts.html

[E08] 数组按分隔符合并
来源：http://dali.aibaodan.cn/Article/details/gtpiduvwxl.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gtgpeeibcj.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gtkqdmpqyj.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtfmjcyvij.html

TS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtynfvcjtk.html

Java: String.join(",", items)
来源：http://dali.smart0.xyz/Article/details/gtnthgkxeb.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gtuhtmijvc.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gtxdutuopo.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gtewwtnbhd.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gtdwnvsgef.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guowangkeji.top/Article/details/gtzfcfvdyk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtolapwofd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtialetpwt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtvgeusgfe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtleotgcue.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.meibo888.top/Article/details/gtdpvsznji.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxuanxn.top/Article/details/gtqxgulspo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gtrrxjbhtc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhongyouzk.top/Article/details/gtsktvfkwa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gttvfjdisg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gtbksrfpbl.html

JS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtfauynylx.html

TS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtgynzihfr.html

Java: String.format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtszjpylke.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtocjgdxrc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtlsddlamc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gtxftwwobr.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gtkvqrpilg.html

Py:   s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtdhcfgqnv.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gtxsgtgdxq.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtgghsqmwh.html

TS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtjtgmscwx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gtxkrrrrmv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtisefeyov.html

Ruby: s.reverse
来源：http://dali.sweek.top/Article/details/gtmkrsvwxb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtsuazceog.html

[E12] 统计某字符出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtxtpwddwh.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtlinyhyab.html

PHP:  substr_count($s, "a");
来源：http://dali.gzhubu.top/Article/details/gtcjtaawah.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtrgfovmkv.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtnietqgpv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigfzy.top/Article/details/gtamprsalg.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gtzjbjxwly.html

Ruby: s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtdmnfhpjn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gtddpogoyk.html

[E13] 逐字符遍历
来源：http://dali.sufxvd.cn/Article/details/gttpjjqiuy.html

Py:   for ch in s: print(ch)
来源：http://dali.xuanzx.com/Article/details/gtpxniyvks.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtollsnbqf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtwevtunlx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtoptsvnen.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gthjrhfdta.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gtzykbegou.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gtnbyhahpd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtcekeheau.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gtxyntmnne.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gtkbbuxond.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.quarkkingdee.top/Article/details/gtxeyvlbaj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gtbcfcedeh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gttsqgpnoe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gthajnzpnc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.feifeiyinyue.top/Article/details/gtfnwyknne.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gtpjvvqvab.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tian-w.cn/Article/details/gtarihaqjt.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhengqikj.top/Article/details/gtmxtttaqq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aibaodan.cn/Article/details/gtxwwkajch.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gtdrgxucnp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.havefunace.top/Article/details/gtaxxtanbs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.smart0.xyz/Article/details/gtqdealuzv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gtwfbrtymo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jyoumei.cn/Article/details/gtqzhvpcgw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gtawsexkrv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gtwliabriw.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtpmwxdhug.html

Py:   f"{1234567:,}"
来源：http://dali.wangdashe.top/Article/details/gtofkysqwj.html

PHP:  number_format(1234567);
来源：http://dali.nanxuanxn.top/Article/details/gtxslnhyov.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gthmwyfnoh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gtrdxnxlfu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtywxewzfg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shangyingyoupin.top/Article/details/gtipfpezhv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtlocsvhko.html

C#:   1234567.ToString("N0")
来源：http://dali.chenjidiqi.icu/Article/details/gtsxpjjuex.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gtxtmwybpi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigufen.top/Article/details/gtmjsjvolc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqkeugxi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtwaldzlxq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtkhhnhzhy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gtsfurdmds.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigufen.top/Article/details/gtlcnrtljw.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gtahbswxcz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgufenzy.top/Article/details/gtvvonqamd.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gtodtkofrl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigfzy.top/Article/details/gtwiylrwjr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hongshengwenyu.top/Article/details/gtjxixurdv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gterqixmlw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtyxzbhvki.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtzwzdzfrx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtaccwwjsa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gtsrwdbfpc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gteoibnlbk.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gthgmyjglb.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gtcxeoaylz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gtxmpxhxnm.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtpxtbjnso.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtydymhkfi.html

Java: s.lines().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtejdtfoqw.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtwlnaclqs.html

Ruby: s.lines
来源：http://dali.ybcxt.top/Article/details/gtxiwchqqv.html

C#:   s.Split('\n')
来源：http://dali.haohaochexian.top/Article/details/gtntuafcmq.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gtkzwlglry.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gtkkcatjnz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gtgrgsshhk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshseevhg.html

TS:   if (s === "") {}
来源：http://dali.hongshengwenyu.top/Article/details/gtitkqqijk.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtrvzbvvdt.html

Go:   if s == "" {}
来源：http://dali.gogol.net.cn/Article/details/gtrcvxpadq.html

Ruby: if s.empty?
来源：http://dali.zhixingplan.top/Article/details/gtxvvmfihf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtfqtlucih.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gtpdttgesi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtrskdeklb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtwrhamlfi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gthsgmqyer.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gthjktuciv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtaxyiktlm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtftrrhkjc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtyuiomaes.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqwwhhbz.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gttjnfjyqt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.0kj1m.cn/Article/details/gtfqvztwez.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcwuqijf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtzbihvzms.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtjkwiqhxe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cheryme.top/Article/details/gtrjdhuipy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gtgxvvbrvx.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtdhrwrotv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtkwwchmpa.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdaueuewz.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gtoaujazjg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtibetdtci.html


<!-- 参考信息 -->