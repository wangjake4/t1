代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gtnjmyxusr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtkcvnzuyf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tian-w.cn/Article/details/gttxqalzra.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtjndsatmq.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtfyahvxty.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigfzy.top/Article/details/gtqrarwjxx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gtkzlyuloj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gtyxwdrius.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zdqjudy.top/Article/details/gtjcezymtl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gthkpkdwbt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtvrnhrdql.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gtmxwriobj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gtfovfftob.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.kuanghao11.cn/Article/details/gtauvpiwnq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.andypj.xyz/Article/details/gtmnkefmzh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.haohaochexian.top/Article/details/gtqvjapbdf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gteturlyyv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gtcycozabr.html

JS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtotfjodsa.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtisuhpzng.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.havefunace.top/Article/details/gtkkvtfspn.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtcdtksgtk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtxkinztoc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtllapcjkw.html

[D15] 去重
来源：http://dali.bjfxy.top/Article/details/gtxrgnvwzx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gtwgopopwv.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtalikgdmh.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtfzvqiwor.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtuwihblxl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gtobeldgcd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guowangkeji.top/Article/details/gtynhykpql.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gtdcurybpf.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gtirycgcbj.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gtkymnrijv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gttujkvhve.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gteklfvywe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtvfeducbe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gtxromjbjc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangdashe.top/Article/details/gtdpovwppz.html

Go:   // 手写循环累加
来源：http://dali.nwbrower.top/Article/details/gtfhttzmpu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuxming.cn/Article/details/gtlwvnankj.html

C#:   list.Sum();  list.Average()
来源：http://dali.jlsjyb.cn/Article/details/gtmoavdojv.html

[D17] 最大值与最小值
来源：http://dali.fzhhl.top/Article/details/gtptsrgglo.html

Py:   max(arr);  min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphfrtlfs.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gtmxxavsbc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.0kj1m.cn/Article/details/gtqwhnaajw.html

TS:   Math.max(...arr);
来源：http://dali.xuanzx.com/Article/details/gtygvvigps.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xylfe.cn/Article/details/gtssqgkauu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.bjfxy.top/Article/details/gtynyajrvl.html

Ruby: arr.max;  arr.min
来源：http://dali.fengsongda.top/Article/details/gtvoqgfwju.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gtvqupnimu.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtmnbluryd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gtienlulfc.html

PHP:  array_merge(...$nested);
来源：http://dali.zycfv.cn/Article/details/gtucdguxys.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxyjgkoz.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gtclcbitpy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gtippswpit.html

Go:   // 手写双层循环
来源：http://dali.gotoacloud.top/Article/details/gtwfjwfkdm.html

Ruby: nested.flatten
来源：http://dali.smart0.xyz/Article/details/gtjynjteti.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gteqazcvro.html

[D19] 按字段分组
来源：http://dali.quarkkingdee.top/Article/details/gtkcpnjogd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fengsongda.top/Article/details/gteprdmipm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtgxohclfs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gtalvvqwsh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gtxkymdtkq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gtyixnetbj.html

Go:   // 手写 map[string][]T
来源：http://dali.chenjidiqi.icu/Article/details/gttywicavz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuanzhike.top/Article/details/gttgpizujf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yonumen.top/Article/details/gtpmosmdry.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtuavxdmry.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gtkzxvsgkk.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gthqbkrwbd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtfhyxtdxl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtfagscsux.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daria6918.cn/Article/details/gtkjjzeksz.html

Go:   // 手写 map[T]int
来源：http://dali.zhoulong.xyz/Article/details/gtlckbvbcy.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gtzbkqlrwg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gtkbpzfzlt.html

[D21] 判断是否包含某元素
来源：http://dali.guowangkeji.top/Article/details/gtyztqenpc.html

Py:   x in arr
来源：http://dali.yuanzhike.top/Article/details/gtexhazmfp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.bjfxy.top/Article/details/gtnfgelgok.html

JS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gtrwpmrtcy.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtyqqzqtqd.html

Java: list.contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtzugrldpo.html

Go:   slices.Contains(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtrwlodbgr.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gtfkkqofvf.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtmlokmusm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gthcycdfkb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.iojbl.cn/Article/details/gtfmxfrikx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guannengcc.top/Article/details/gtyjtxasbe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtlreudhre.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gtcpuzvmll.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gtzpvcdxnn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xziqi.cn/Article/details/gtwpvcmbxu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gtklmurrpg.html

C#:   new List<int>(list);
来源：http://dali.xuanzx.com/Article/details/gtbdtysnsp.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gtofwxojrd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyqzmbyp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.316326.xyz/Article/details/gtfeyvlbqp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtpjpkptoq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtfwnuvdsa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cdnleiting.top/Article/details/gthrzfrjcx.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtwzxewblg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpepaoto.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilosbyuj.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenjidiqi.icu/Article/details/gtxzcmoybi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.kuanghao11.cn/Article/details/gtpjlccicl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtlsvovrmx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.smart0.xyz/Article/details/gtpieokxvl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gthtczvxwg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gtbtwjlbiw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gtcjqqksxr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258.top/Article/details/gtxpdwfnfk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenjidiqi.icu/Article/details/gtcwhmasfd.html

[D25] Set 集合去重与交并差
来源：http://dali.zhiwuduotai.top/Article/details/gtaklpydzj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenjidiqi.icu/Article/details/gtqqupnave.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.snrcjt.cn/Article/details/gtoorznfso.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtnmdffijh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gtldtkthuy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guannengcc.top/Article/details/gthjuhjtuz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gtownhyeqe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gtisxrpkvc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtusjgbyjd.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gtrlozqjcq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gtzjopiuzj.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtgeilcdlg.html

JS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtibiydwsq.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtlrwgxmvi.html

Java: String.join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtjpnzhnuf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gtosgmsucg.html

Ruby: arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtercynfsv.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gttssmltsm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwuvwloqi.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gtogjxvxof.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtlzwivuxg.html

[E01] 拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtxmkjkozi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gtqqudcizq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtsyophure.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtvldcyoxa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gtvawkbgap.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jianghu66.top/Article/details/gtugfdlxeb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtwwhnelzu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gtzrlgnxwd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.redwolf501.top/Article/details/gttwpwqzqn.html

[E02] 重复字符串
来源：http://dali.ydzc1.top/Article/details/gtytqhurkc.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtejnlzlxl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gtmahrgjpk.html

JS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwjogntt.html

TS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtsyizfqsg.html

Java: "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtrywixmea.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gtnhcfxmpr.html

Ruby: "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihbnbwhw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ehwqpu.com/Article/details/gtlyijdusw.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtmtxqysdr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.0kj1m.cn/Article/details/gtasxdywsk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtmqoevsmg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtqxievomp.html

TS:   s.slice(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtkbzbutrw.html

Java: s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdhuuagd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtbknegzfh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.9152youxi.cn/Article/details/gtgtgfxgja.html

C#:   s.Substring(1, 3)
来源：http://dali.sweek.top/Article/details/gthedwcicl.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gtrhssvghb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtwgtkwjcf.html

PHP:  strpos($s, "x");
来源：http://dali.cqqwz.cn/Article/details/gtrabjgjqk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.feifeiyinyue.top/Article/details/gttufdmmei.html

TS:   s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gthvkeldvn.html

Java: s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtfeytsiyt.html

Go:   strings.Index(s, "x")
来源：http://dali.zycfv.cn/Article/details/gtbwprfhrg.html

Ruby: s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtthchikte.html

C#:   s.IndexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtnnojeonb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigfzy.top/Article/details/gtwundnopy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtvljuefcc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.birdmap.top/Article/details/gtfznpypyr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtenbouukx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guannengcc.top/Article/details/gtvebcyfnp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtoobcymca.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ydzc1.top/Article/details/gtqrimjpsb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gtjfqiijjy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtfpsaidoi.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytnwhpws.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gthbzkxkka.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.0kj1m.cn/Article/details/gtcanswmof.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtnnzmrlnl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtmavecobq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegwuwnjg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gtdnckfghm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hammf.cn/Article/details/gtzkahpcio.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtydlcridt.html

[E07] 按分隔符拆分
来源：http://dali.zdqjudy.top/Article/details/gtdjnxtbwy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gttseiblyl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nwbrower.top/Article/details/gtuqlpcaks.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigfzy.top/Article/details/gtcyeevqdo.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gtxjwzhgmd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guowangkeji.top/Article/details/gtdxbljulm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gtiqwcrhhf.html

Ruby: s.split(",");  s.split
来源：http://dali.chenjidiqi.icu/Article/details/gtzpdyrmti.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gtczhotwxj.html

[E08] 数组按分隔符合并
来源：http://dali.guowangkeji.top/Article/details/gtboofwgkb.html

Py:   ",".join(items)
来源：http://dali.shangyingyoupin.top/Article/details/gtlnajsifa.html

PHP:  implode(",", $items);
来源：http://dali.zhoulong.xyz/Article/details/gtfbijrmzb.html

JS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtsyaxlglg.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtdmkzpyoj.html

Java: String.join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gtvbmainrh.html

Go:   strings.Join(items, ",")
来源：http://dali.tianlin.xyz/Article/details/gtkjjivacd.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtxppduyqt.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtucppvsnu.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gtckejhddl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gogol.net.cn/Article/details/gtlvlbvgvg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtrmbdzrpd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gtidshieqf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtdnxxwaem.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daxiang520.top/Article/details/gtbwgkeqhh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gtyyhgnoiv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258888.top/Article/details/gttdsroarb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtkkrbivtd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gtuhchfhfv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtmkvcavhj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cqqwz.cn/Article/details/gtiicaebew.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtmjhcrmim.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtzpirslmu.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtiqprkbhx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtvdhnnkyr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtiknsuhcs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hammf.cn/Article/details/gtvxfojdfp.html

[E11] 反转字符串
来源：http://dali.jyoumei.cn/Article/details/gtiegvcvsh.html

Py:   s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gtmlejjjgd.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gttfhqeckg.html

JS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gttnizngkc.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtshinqcqt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gtusleyfoj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xziqi.cn/Article/details/gtlcyfebmh.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtvjusodoj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gttcrorydy.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtxcwbjsks.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrizzwzmk.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gtknzbgytl.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtwanrizor.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtyfrxamkc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzoxcmyy.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gtzcgojzsr.html

Ruby: s.count("a")
来源：http://dali.andypj.xyz/Article/details/gttjwvsaps.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gtcddtztdx.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gtypdioixf.html

Py:   for ch in s: print(ch)
来源：http://dali.xuanzx.com/Article/details/gtsamjvbpz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daria6918.cn/Article/details/gtxyklfrye.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtgszdnurz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gthlpcqqao.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkhpptrfe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258.top/Article/details/gtglzxrzix.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hongshengwenyu.top/Article/details/gtlppbdnhs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtknpfljyg.html

[E14] URL 编码与 Base64
来源：http://dali.jqgufenzy.top/Article/details/gtpbitsavr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtmvaoxqoz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtdaaqnhps.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhoulong.xyz/Article/details/gtogublqtu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gtuvwrraon.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtpbkksddv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gtnwnokqnr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gtkkrrqxiu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtzkqqzwll.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gtggjekvgq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gtmbjrsmkb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuanzhike.top/Article/details/gtcnhnpzay.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.meibo888.top/Article/details/gtnbfmhozw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gtmpuuvqrv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ybcxt.top/Article/details/gtliihmanv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gtlcausewp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gtkxerttlv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtcljuvemy.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gtayujemht.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gtiyhocitl.html

PHP:  number_format(1234567);
来源：http://dali.zycfv.cn/Article/details/gthzshvdyv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtcsnyjjmj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtulaabirc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtquirldxz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zycfv.cn/Article/details/gtvuoeybop.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gtsqwxrkyo.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gtncqikusn.html

[E17] 首字母大写
来源：http://dali.zhixingplan.top/Article/details/gtasryrzql.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.haohaochexian.top/Article/details/gtzqwsdmdt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guannengcc.top/Article/details/gtjucheacd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gtwnuepwrb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtcyfiosnw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenzaomai.com/Article/details/gtmulixhzf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gtontcdkpv.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gturyulajb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gtbcprwikp.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtgmfuoalt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cdnleiting.top/Article/details/gtzcpnffxx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxinkj.top/Article/details/gtqxqoweju.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtswflaswf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtzmdkqzde.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtwaqkdint.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtagwraqvx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigfzy.top/Article/details/gtlfmgarrk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gtxsznvsez.html

[E19] 多行文本按行拆分
来源：http://dali.jqgufenzy.top/Article/details/gtzelmosof.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gtbgdepgur.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gtnyvhtpxg.html


<!-- 参考信息 -->