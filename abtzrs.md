代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtfuhzmtbd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gtxstrcrxs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tanke756.top/Article/details/gtfdaahvrt.html

Ruby: arr.uniq
来源：http://dali.tanke756.top/Article/details/gtkhbgkmsg.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gtylvkexag.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gtdtwnalwl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aizwys.cn/Article/details/gtbmxbwzby.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtsrbekgpx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtcfyyysqb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtcrbuisme.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gtnsrlcmhc.html

Go:   // 手写循环累加
来源：http://dali.redwolf501.top/Article/details/gtpgjoymnq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gtsbwszccp.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gtsgjwvyql.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gtsuyywbpl.html

Py:   max(arr);  min(arr)
来源：http://dali.yueranfly.top/Article/details/gttexzzbxf.html

PHP:  max($arr);  min($arr);
来源：http://dali.gzhubu.top/Article/details/gtzzqnlzne.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nwbrower.top/Article/details/gtxnrogwph.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gtmtqrhyqm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gtlhocchbg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.andypj.xyz/Article/details/gtmagzhbku.html

Ruby: arr.max;  arr.min
来源：http://dali.fzhhl.top/Article/details/gtlxaolesq.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gtbqkmizud.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gtppweueab.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.vqdsnc.cn/Article/details/gtdylfzwnt.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gtdiuuygpz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hongshengwenyu.top/Article/details/gtqtpamlvq.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhqilxyr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxinkj.top/Article/details/gtooakqnyi.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gtqkdsbypa.html

Ruby: nested.flatten
来源：http://dali.guowangkeji.top/Article/details/gtlchwplcz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtyewiqpix.html

[D19] 按字段分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlyxjgof.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hfpthk.cn/Article/details/gtfjnhzfgx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gthlneoslg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gtpmygiapr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtzzhnbdkg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gtfcwicacs.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxuanxn.top/Article/details/gtyootrxbf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gtkkszzhco.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gthbqhqxwl.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnitvrov.html

Py:   Counter(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthigyxdy.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtbositsgl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gttaxbbexn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtrhphsdio.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gttgbjbaqi.html

Go:   // 手写 map[T]int
来源：http://dali.nwbrower.top/Article/details/gtlrvyurtg.html

Ruby: arr.tally
来源：http://dali.hysaishi.cn/Article/details/gtrspdyrxy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gtqajsnuie.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gtzfwmhssm.html

Py:   x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gtwzyrgxqh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangdashe.top/Article/details/gtdcaytaut.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtwcgpgfpp.html

TS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtzobhkkeu.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtzaqghhzj.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtmcslcmih.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtocewctmo.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtdzkuzbpf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.iojbl.cn/Article/details/gtdrkepovc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gtjbxlfkop.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.andypj.xyz/Article/details/gtigasptoz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yueranfly.top/Article/details/gtrvuvfjqn.html

TS:   [...arr];
来源：http://dali.hammf.cn/Article/details/gtfbhavgkr.html

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gtkqjsmyxs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gtltqxjvsz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwsulvjv.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gtrkiaxhon.html

[D23] reduce 累积计算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyscldlhm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fzhhl.top/Article/details/gtbusjbnir.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gtqaeniupv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtjyhkkcpw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtfekfrfdz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gtuqtydbcb.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtjovhqntq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hfpthk.cn/Article/details/gtsdqxwlnj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gtlgjtnrbq.html

[D24] 字典 / Map 基本操作
来源：http://dali.cqqwz.cn/Article/details/gtjlxxaqla.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gtdbokimnb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gthhvpjchn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hywenlv.cn/Article/details/gtwaluxbia.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtflgsxvir.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gtaysectwl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sysykeji.top/Article/details/gtcxxqplcx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.meibo888.top/Article/details/gtrwwfmaqb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pengpengdd.cyou/Article/details/gthlvqapff.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gtlcouropo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gtohaxsaiz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.vqdsnc.cn/Article/details/gtoqomqzcj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gtipbwwrao.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenlongwang.top/Article/details/gturjornwq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yonumen.top/Article/details/gtbaqnavpj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubwaubkh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gtyuhumbte.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtajshvdow.html

[D26] 数组转字符串
来源：http://dali.ivvv.top/Article/details/gtpuzxqgso.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtbljyhhcz.html

PHP:  implode(", ", $arr);
来源：http://dali.gotoacloud.top/Article/details/gtwnlncvec.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtqvlawnld.html

TS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtwwoxikff.html

Java: String.join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapszmyoj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gtwtddxxis.html

Ruby: arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtdnxwsgkh.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsnlexdq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuxtuism.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gtyysyqqxj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtaqtbwvxo.html

[E01] 拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtazpeczhw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yangfankeji.com/Article/details/gtggerufeb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ydzc1.top/Article/details/gtjkmrldrt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gttuxvzrlt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpasfmlgi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sysykeji.top/Article/details/gtcgmatkdw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258888.top/Article/details/gtkvoeszgf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ivvv.top/Article/details/gtbkvilssf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtpisszayz.html

[E02] 重复字符串
来源：http://dali.guannengcc.top/Article/details/gtumlqsmbh.html

Py:   "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtccrbgeuo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.vqdsnc.cn/Article/details/gtryzvkpuq.html

JS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtqatxztbi.html

TS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtryrqrrcw.html

Java: "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtrjxgqqmm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hammf.cn/Article/details/gtqbblyavm.html

Ruby: "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gtlpbmmmln.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nwbrower.top/Article/details/gtroikeyda.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gtbwpfrbwt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gthmduoaeb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtllqxqsop.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtaeckeqbo.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtvdkicxbl.html

Java: s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtkydrcomf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtatghuvdi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.9152youxi.cn/Article/details/gtepxvkpzn.html

C#:   s.Substring(1, 3)
来源：http://dali.meibo888.top/Article/details/gtxbpsfxkt.html

[E04] 查找子串位置
来源：http://dali.zhengqikj.top/Article/details/gttwgfjwlk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gtsuroanit.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gtzorqipik.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.svipenyu.cn/Article/details/gtilqmhsxo.html

TS:   s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtdvprxvso.html

Java: s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtepwudxtu.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxuanxn.top/Article/details/gtffzlcqdp.html

Ruby: s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gtbtsveqwf.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtestbcide.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daxiang520.top/Article/details/gtqsrsazci.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuanzhike.top/Article/details/gtfpgynicd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nwbrower.top/Article/details/gtpxbbvgml.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtnwsoneyi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gtwhbwlmwz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtqjatslcm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigufen.top/Article/details/gtozvdmsvk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gtjpugluch.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtoidmcqqd.html

[E06] 替换子串
来源：http://dali.316326.xyz/Article/details/gtnpmnvosp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtvbjpremd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258.top/Article/details/gthjjzixzi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtrvjxtezm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtxqzfipgk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtapgffh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtpfqobkjx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtgrojjwgh.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbqxrbii.html

[E07] 按分隔符拆分
来源：http://dali.jyoumei.cn/Article/details/gtngilbixd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuanzx.com/Article/details/gtsjerusao.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtmeofddjq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.meibo888.top/Article/details/gtjlzehvww.html

TS:   s.split(",")
来源：http://dali.jyoumei.cn/Article/details/gtrsdfbuhw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gtgcoqpuzv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhoulong.xyz/Article/details/gtuxpwwvdg.html

Ruby: s.split(",");  s.split
来源：http://dali.andypj.xyz/Article/details/gtewiovycs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.c1oappe.top/Article/details/gtwvgphmxv.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxnbkvdv.html

Py:   ",".join(items)
来源：http://dali.smart0.xyz/Article/details/gtyhbvyhsc.html

PHP:  implode(",", $items);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvemdilf.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtwohewrsm.html

TS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtjtjdditr.html

Java: String.join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtwouiorol.html

Go:   strings.Join(items, ",")
来源：http://dali.c1oappe.top/Article/details/gtkhgcmsii.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtrhgaqqfe.html

C#:   string.Join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gtehdjebis.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gttrdmlssk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yongpay.top/Article/details/gtgbjmafar.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtohcbcnmk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtnvgcjleb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gttfcddrmu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.birdmap.top/Article/details/gtzpdpzqwo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.snrcjt.cn/Article/details/gtlodkihol.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gtpnpofpwn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtjoztjrzg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnxiangtu.top/Article/details/gtsluccquj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtzmpkpuph.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gtugwobukl.html

JS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcafzuox.html

TS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtchfhkaro.html

Java: String.format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtesdzfioa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtpigrhvmq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtjosiavbh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zdqjudy.top/Article/details/gtrpowppkx.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gtymvlljcx.html

Py:   s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtclhtoyzw.html

PHP:  strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtqwhwvvzc.html

JS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtkbqswqkv.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmidwbqqb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gtkmidtbba.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guannengcc.top/Article/details/gtzpifgngs.html

Ruby: s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtdxoooexm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtkqyburrx.html

[E12] 统计某字符出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtyovhijod.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gtuvyytyee.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gtwnnlvyrz.html

JS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gtgzsaradh.html

TS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtbedjnpgc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gtvowgrrry.html

Go:   strings.Count(s, "a")
来源：http://dali.ybcxt.top/Article/details/gtsgnshqxy.html

Ruby: s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtbfbirgwr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gtmptjerrg.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gtgpdbxpqn.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtivbgyylx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogisnaov.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtxkqxnbvf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtbgouvyly.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuxming.cn/Article/details/gtwdtbowlj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yanxiufei.cn/Article/details/gtngysjbhv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yueranfly.top/Article/details/gtwjpbltuq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.birdmap.top/Article/details/gtkkrwuznh.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gtojyliexk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuetiantiany.cn/Article/details/gtunbhqwje.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ydzc1.top/Article/details/gtkengbbxo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gtxctuzvgg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gtkxxaqmsz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtxyrbaoqr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gtyjrxdyga.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.feifeiyinyue.top/Article/details/gtjuboixod.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtvtapvmwk.html

[E15] HTML 转义 / 反转义
来源：http://dali.hysaishi.cn/Article/details/gtbdfppubv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.andypj.xyz/Article/details/gtjaqnglqs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gtcchtactq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuxming.cn/Article/details/gtgrqqksyj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gtcnlfrzgx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aibaodan.cn/Article/details/gtenjtmuvn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ppjwa.cn/Article/details/gtavtvbxce.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gtkxwjbgkq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gtesclmgom.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gtolleiyla.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gtifeplphf.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gtvlpbhbgs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gteqvxfrxd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtshptoqlp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtnzziamyz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtxonqjxuq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtdllezugo.html

C#:   1234567.ToString("N0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtreqxtlnn.html

[E17] 首字母大写
来源：http://dali.shzxlz.cn/Article/details/gtvlnvmhza.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gtclsllkkt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gttjvntgzu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsjzxdyx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtzglinicm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhoulong.xyz/Article/details/gtyeypimxw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ehwqpu.com/Article/details/gtsentfejw.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlazakrro.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cdnleiting.top/Article/details/gtqlikdjos.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gtkclpzixv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yongpay.top/Article/details/gtgxvvpawk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gtcxakmito.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtgcjmtplk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gthhqmojxq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtixhpchci.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfpqmuys.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenjidiqi.icu/Article/details/gtxfdfqscn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtgncpbiqj.html

[E19] 多行文本按行拆分
来源：http://dali.haohaochexian.top/Article/details/gtfzvlqhkw.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtisarnnoh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj202588.top/Article/details/gtdzhreehm.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtfttjyrkn.html

TS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtagwxvhpm.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gtgbdylysi.html

Go:   strings.Split(s, "\n")
来源：http://dali.mhx1999.top/Article/details/gtkoacixta.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gtysjbjjnj.html

C#:   s.Split('\n')
来源：http://dali.pycfn.com/Article/details/gtyumdmtls.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gtpstspole.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gtytbrbnny.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shangyingyoupin.top/Article/details/gtrdnghatr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gttsnhttjc.html

TS:   if (s === "") {}
来源：http://dali.zhiwuduotai.top/Article/details/gtvzvhguum.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtfwawhmst.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gtexjpxbvv.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gtsniguxhx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258888.top/Article/details/gtekppefiw.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtszvooukv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtfsmvfqqw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtvyammame.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtooyirpsh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtxinjqwsk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtqdxenfnf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shangyingyoupin.top/Article/details/gtmdfjbbpn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtaoxlxaei.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtqqhttlcw.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gthdufpgmg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gtavryftej.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtstaukcub.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtyvpsrioa.html


<!-- 参考信息 -->