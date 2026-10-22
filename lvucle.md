代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.cqqwz.cn/Article/details/gt2nyzahgmu.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpgyqso.html

Go:   slices.Reverse(arr)
来源：http://dali.yuxming.cn/Article/details/gt2gjdxfoyh.html

Ruby: arr.reverse
来源：http://dali.guannengcc.top/Article/details/gt2giyqfvez.html

C#:   list.Reverse();
来源：http://dali.zhengqikj.top/Article/details/gt2noquxmtg.html

[D12] 查找元素下标
来源：http://dali.dianchejie.cn/Article/details/gt2wrfgzyka.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gt2pxpxakre.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2huphsity.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2qdgnhiya.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gt2kgkctggt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj202588.top/Article/details/gt2aaldozpm.html

Go:   slices.Index(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2zvlpagrj.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gt2cttyhotj.html

C#:   list.IndexOf(x);
来源：http://dali.chenzaomai.com/Article/details/gt2zamzaown.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gt2dtckrfgd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gt2vjjkfkqf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hywenlv.cn/Article/details/gt2whkkuzqm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gt2kikewbup.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gt2nepholgk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gt2ysprzqae.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zycfv.cn/Article/details/gt2sshhyufo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangdashe.top/Article/details/gt2yrknrynl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2tvmheehs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kisdvmeg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gt2krhakift.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2isuriziu.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gt2idtvrotm.html

TS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gt2nlnurkfh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gt2cevoptpk.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzcaravu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2eurrwnxi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.havefunace.top/Article/details/gt2tgwkfyms.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gt2jxhladnf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gt2jodsetlu.html

PHP:  array_unique($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2imjpnvmb.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gt2nictjruz.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gt2cozqczzk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jiagoushi.top/Article/details/gt2xfmvnoxl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gt2nktcfxmu.html

Ruby: arr.uniq
来源：http://dali.yongpay.top/Article/details/gt2eyflsbfc.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gt2tdnqolox.html

[D16] 求和与平均值
来源：http://dali.zdqjudy.top/Article/details/gt2uhzjnmnv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2gykdepxb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2tkxvclmw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gt2vichjfwv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2kcpbnwpt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gt2aeqrksxn.html

Go:   // 手写循环累加
来源：http://dali.nanxuanxn.top/Article/details/gt2bbbjsusa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gt2tpbiboxk.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gt2wqsppthj.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gt2mmixckde.html

Py:   max(arr);  min(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2ilklekqw.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hejsnvse.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yvedp.cn/Article/details/gt2sqiihncx.html

TS:   Math.max(...arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gnimjmgq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gt2rxdjgqea.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2sbfwaewp.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqeyyzfj.html

C#:   list.Max();  list.Min()
来源：http://dali.andypj.xyz/Article/details/gt2tcqmivvu.html

[D18] 扁平化嵌套数组
来源：http://dali.yangfankeji.com/Article/details/gt2sszeakte.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gt2lhxmobrd.html

PHP:  array_merge(...$nested);
来源：http://dali.shuidangran.top/Article/details/gt2tisenfjw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gt2bzqivpql.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gt2rxtmauad.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuanzx.com/Article/details/gt2vzxlxwzh.html

Go:   // 手写双层循环
来源：http://dali.nwbrower.top/Article/details/gt2bzygsakq.html

Ruby: nested.flatten
来源：http://dali.zhengqikj.top/Article/details/gt2vmbxdkbz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2hfirxuym.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gt2ctuykpaa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gt2vwtqvoek.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gt2bxqfhqww.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aizwys.cn/Article/details/gt2vkulncrh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gt2grjrqafl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gt2nsrtakec.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gt2ejclwktn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xylfe.cn/Article/details/gt2eiflalzi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gt2dtlypfbs.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkmmgjhy.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2feivyyeo.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gt2johrcyab.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2vgmblzkm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gt2esqnbnbh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gt2xbodmini.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gt2regwmjba.html

Ruby: arr.tally
来源：http://dali.zhoulong.xyz/Article/details/gt2fqfvhrxf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gt2nwqxxlyz.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gt2aabmcknt.html

Py:   x in arr
来源：http://dali.dashuyun.cn/Article/details/gt2ueqqgtiv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gt2xlpelydh.html

JS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2bsjqtjcb.html

TS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2zbvyaadl.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2tydlvmiy.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2bprioypl.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gt2xsjuoxyk.html

C#:   list.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gt2jyiblzrh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gt2ictdqize.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gt2fiozzuah.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gt2agkwdstg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gt2jpejdznu.html

TS:   [...arr];
来源：http://dali.fengsongda.top/Article/details/gt2kfhkyavy.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjrpnyqw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbubzhoy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hongshengwenyu.top/Article/details/gt2raiyvxtx.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2ukwvtaos.html

[D23] reduce 累积计算
来源：http://dali.0kj1m.cn/Article/details/gt2llbyekyp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvpkcshm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gt2elfsosor.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gt2axbdhzef.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrvkhgif.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gt2rnaqmrgd.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gt2snjzwqbq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gt2wlliaxmm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gt2tzguuadz.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenzaomai.com/Article/details/gt2zelqtyad.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gt2xnnlxbnd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aibaodan.cn/Article/details/gt2hcoiavok.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ishmhxkn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ybcxt.top/Article/details/gt2pebbizdv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gt2xrqxcvvb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dianchejie.cn/Article/details/gt2pgxjqdok.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hfpthk.cn/Article/details/gt2lizgnyyl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gt2kwwglnfc.html

[D25] Set 集合去重与交并差
来源：http://dali.zhoulong.xyz/Article/details/gt2jivwyufy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenzaomai.com/Article/details/gt2svoriilj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gt2frknwiti.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cashguo.top/Article/details/gt2ihzcnepb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cheryme.top/Article/details/gt2sfsdyetq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258.top/Article/details/gt2yvolwmpo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dashuyun.cn/Article/details/gt2sthcmqvt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hfpthk.cn/Article/details/gt2kcdneksx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gt2axjbdket.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gt2qqdbapbr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2yxpxoasb.html

PHP:  implode(", ", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pfpqtnak.html

JS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2vifkhyyl.html

TS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2wpzinorh.html

Java: String.join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gt2ryvoqigl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tianlin.xyz/Article/details/gt2iovomkhy.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gt2rxphgjzp.html

C#:   string.Join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gt2rcxujlfk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2fyypejip.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gt2yfevsdsj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2mdtxywte.html

[E01] 拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2zwylizqs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.redwolf501.top/Article/details/gt2ddeswumj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xinyue.icu/Article/details/gt2dmzfeajt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bndddqbp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gt2jiqlstim.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shuidangran.top/Article/details/gt2ekgvbmlp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rffedner.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zdqjudy.top/Article/details/gt2blwbtywd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2llludrec.html

[E02] 重复字符串
来源：http://dali.yj202588.top/Article/details/gt2izolbyie.html

Py:   "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gt2utuohxjs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gt2ggsgktit.html

JS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2uvgeixug.html

TS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovykhpzq.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqaaxdl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2hwxfvijr.html

Ruby: "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gt2wqgpqwsb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.svipenyu.cn/Article/details/gt2rhjgybgd.html

[E03] 截取子串
来源：http://dali.wangdashe.top/Article/details/gt2sjxiioba.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gt2ihueovwq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2oeuhqvek.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gt2ewhpujev.html

TS:   s.slice(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2ymwzsnhv.html

Java: s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gt2adwklnlw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gt2kdiczvwb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.snrcjt.cn/Article/details/gt2hboffkrl.html

C#:   s.Substring(1, 3)
来源：http://dali.redwolf501.top/Article/details/gt2fljeholr.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gt2hdakhzbl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hgzkldmo.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gt2oyrxilee.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aibaodan.cn/Article/details/gt2dvxnrdji.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gt2qtybxugt.html

Java: s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gt2zjkmtvht.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxinkj.top/Article/details/gt2jzghzndq.html

Ruby: s.index("x")
来源：http://dali.316326.xyz/Article/details/gt2kqdgoiyz.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gt2squejifx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gt2sxnfgqov.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj202588.top/Article/details/gt2tnsdkmfo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gt2oydmqprf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2atgteita.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258.top/Article/details/gt2chgmziol.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gt2fmldmlvq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2iaxjksvq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yueranfly.top/Article/details/gt2zsbtrfbp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aizwys.cn/Article/details/gt2qfscsebr.html

[E06] 替换子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2caignkqw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2axtmebgw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qflzjsjb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzjfjozt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2kvwprabw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2thaqtunx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gt2ohknkxyz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2qwgmyqte.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2vejfgopi.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2sypkklgb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhongyouzk.top/Article/details/gt2phzhupsp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj202588.top/Article/details/gt2ywjnfefp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yonumen.top/Article/details/gt2zfrjmtra.html

TS:   s.split(",")
来源：http://dali.sxryk.cn/Article/details/gt2bkyfvhmc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ppjwa.cn/Article/details/gt2bgjvaqqo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gt2ajdhpkiu.html

Ruby: s.split(",");  s.split
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rciowusx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hammf.cn/Article/details/gt2lmxqiuiq.html

[E08] 数组按分隔符合并
来源：http://dali.c1oappe.top/Article/details/gt2vbnuroew.html

Py:   ",".join(items)
来源：http://dali.jyoumei.cn/Article/details/gt2jxubxshh.html

PHP:  implode(",", $items);
来源：http://dali.hnxiangtu.top/Article/details/gt2cwnafirj.html

JS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gt2cftqjaal.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gt2repixbbd.html

Java: String.join(",", items)
来源：http://dali.sysykeji.top/Article/details/gt2orntwlyu.html

Go:   strings.Join(items, ",")
来源：http://dali.shzxlz.cn/Article/details/gt2rleuzudf.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gt2zeeosymr.html

C#:   string.Join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gt2aoxqecrs.html

[E09] 去除所有空白字符
来源：http://dali.jiagoushi.top/Article/details/gt2hppybpcy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gt2famxkmrv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2xptuazqn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gt2dqjhlqsp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gt2suwwwiyw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.redwolf501.top/Article/details/gt2edmynwkl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yueranfly.top/Article/details/gt2vznjuipi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ybcxt.top/Article/details/gt2blylzzzp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gt2bnakpeyx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gt2tegusvye.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2kntstflq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gt2nkhbzgqj.html

JS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2uuosmyog.html

TS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gt2ltyotqig.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2qtftnobn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wllxivqp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2nihmvcbd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gt2mvxgzytk.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gt2lqjilhob.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gt2adhapvtd.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gt2jdehxrnr.html

JS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2qrsucybc.html

TS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylchpjcq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gt2lfqtfekr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzdcjam.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gt2xbkpjxrp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gt2kuamfptb.html

[E12] 统计某字符出现次数
来源：http://dali.gogol.net.cn/Article/details/gt2uwqlnqwj.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gt2svncafic.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gt2owrfkxqd.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gt2gbpcaxwr.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gt2ewfftvoz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gt2reiqgaga.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gt2ikqazprp.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gt2wrsxbjnr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gt2pdmwuyjg.html

[E13] 逐字符遍历
来源：http://dali.hnqzz.top/Article/details/gt2lkpizdhe.html

Py:   for ch in s: print(ch)
来源：http://dali.dashuyun.cn/Article/details/gt2kswepmro.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gt2ivbsjrbn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gt2paapmbdg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2jlplxaso.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2setnocbn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2ygbrtbyt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gt2kbygyfil.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2aybtotrs.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gt2wnmovvby.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tanke756.top/Article/details/gt2gyrrksjp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gt2pmlwimyo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdilmofx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gt2llagsimt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gt2ztlzpghc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tanke756.top/Article/details/gt2yrqpmcdl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aizwys.cn/Article/details/gt2aixmlznc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gt2uyytvbpq.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gt2sqqpwnmt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cheryme.top/Article/details/gt2uaqunwyz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gt2tbueobbx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gt2pwgrngtz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhmudvoy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.bjfxy.top/Article/details/gt2mpillcao.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.316326.xyz/Article/details/gt2etditwad.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2xbmzwmac.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.c1oappe.top/Article/details/gt2awsgrobx.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gt2oawpxmaf.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gt2tlwexodu.html

PHP:  number_format(1234567);
来源：http://dali.kuanghao11.cn/Article/details/gt2eapwyvsy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gt2nsphpgqv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gt2wcinxwnc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gt2hgmwodpy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gt2xasckiho.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwlakqiu.html

C#:   1234567.ToString("N0")
来源：http://dali.cashguo.top/Article/details/gt2czdadima.html

[E17] 首字母大写
来源：http://dali.jqgufenzy.top/Article/details/gt2iorlzlnq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gt2mgeomhdk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gt2vnpuzmnk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gt2gymhlyqy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gt2rlsviajz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gt2omrxrmpe.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2gatpywfg.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gt2zxrgblka.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gt2njycmsvu.html

[E18] 模板占位符替换
来源：http://dali.smart0.xyz/Article/details/gt2ugrnfffx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yongpay.top/Article/details/gt2lhjolmul.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yangfankeji.com/Article/details/gt2prkjwrxc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2uzqnwkvb.html


<!-- 参考信息 -->