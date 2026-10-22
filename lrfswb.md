代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsopscmwc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtznbmdlxw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gtuxcdybik.html

Go:   slices.Index(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtzizfsrim.html

Ruby: arr.index(x)
来源：http://dali.tanke756.top/Article/details/gtrpyirjfs.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwpzntqr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ydzc1.top/Article/details/gtvmvxtxef.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aizwys.cn/Article/details/gtofvdsezy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtcnfuurqq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtciyfrqwf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gtwehmbeuk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xylfe.cn/Article/details/gtrzztnpku.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sxryk.cn/Article/details/gtszmrpvet.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guowangkeji.top/Article/details/gtpnnqhyhx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.iojbl.cn/Article/details/gtqnvqosbw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cheryme.top/Article/details/gtkqpdpdqo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtmqfrxukp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtscubxkjs.html

JS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtzwqxjiht.html

TS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtnpkkqmvj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gtfncozkrw.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtzodvqfon.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtbgqzkiqv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtzlnsnuby.html

[D15] 去重
来源：http://dali.jianghu66.top/Article/details/gtqsdkbbjl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtrlqfjggd.html

PHP:  array_unique($arr);
来源：http://dali.yongpay.top/Article/details/gtuauoeexl.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtocdpapvt.html

TS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtxhicmnag.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gttnzlkzxj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gaohongyu789.top/Article/details/gtzkiateum.html

Ruby: arr.uniq
来源：http://dali.gotoacloud.top/Article/details/gtmrvkgsoq.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gticwamfrg.html

[D16] 求和与平均值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdutldie.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtowewhdxa.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gtmupbyvuu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtwhtiyqip.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtfbnzzetf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtujngdgal.html

Go:   // 手写循环累加
来源：http://dali.fengsongda.top/Article/details/gtrftfyenw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guannengcc.top/Article/details/gtigutxyzo.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gturhjrmhy.html

[D17] 最大值与最小值
来源：http://dali.wangshuangyany.cn/Article/details/gttjzuvjhv.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtxuwomxzr.html

PHP:  max($arr);  min($arr);
来源：http://dali.smart0.xyz/Article/details/gtqgfvfbbz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gtwhpasxsq.html

TS:   Math.max(...arr);
来源：http://dali.dianchejie.cn/Article/details/gtpwcmxmng.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.meibo888.top/Article/details/gtdufalwyn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cucudq.cn/Article/details/gtebbyztwf.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gtufnorzth.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtprmlutpc.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gtcgkcytus.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggrxvjpl.html

PHP:  array_merge(...$nested);
来源：http://dali.jianghu66.top/Article/details/gtyuhvkzwo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gtbcgymwka.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtghfhvilf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtiomjfsze.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxeqpjdx.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gtkywxusxq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gtjuqfxjen.html

[D19] 按字段分组
来源：http://dali.bjfxy.top/Article/details/gtokywlaub.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gtpvgwpnjj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guowangkeji.top/Article/details/gtrggcbxyr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gttwpxvhli.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gttepokuvi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gtwyowmpaw.html

Go:   // 手写 map[string][]T
来源：http://dali.mhx1999.top/Article/details/gtyapsgbcz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gtzdfcnahq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnxiangtu.top/Article/details/gtmilmzsep.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gtnyygncqj.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gtvfgmntmj.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigufen.top/Article/details/gtoyoqctcr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtjhkspjqg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtbwyhofpd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gtpfgmihsf.html

Go:   // 手写 map[T]int
来源：http://dali.snrcjt.cn/Article/details/gtbsetvecb.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gtfqzszlhj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gthvqwjkbi.html

[D21] 判断是否包含某元素
来源：http://dali.ydzc1.top/Article/details/gtbfjikowi.html

Py:   x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtborydwfc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gthdrjawij.html

JS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtgtsushlu.html

TS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtzvpfejmz.html

Java: list.contains(x)
来源：http://dali.fzhhl.top/Article/details/gtqkwvxxyu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtrfdvtmst.html

Ruby: arr.include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlydjpdvf.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtxxqghhjh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtpuatiboh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuanzhike.top/Article/details/gtcihzgfeb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigufen.top/Article/details/gtamsjmmzm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gtofhfaowm.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gtuwdmktqe.html

Java: new ArrayList<>(list);
来源：http://dali.ehwqpu.com/Article/details/gtfjeberhv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.birdmap.top/Article/details/gtumeejejz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gtldebbjcc.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gtaicnvhtg.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gtkmprwfyu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shuidangran.top/Article/details/gtlnyslryr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yangfankeji.com/Article/details/gtrqtjeujy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtdjwcxikq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtryjknqcc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ydzc1.top/Article/details/gtnucicjkw.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtvgfuolqi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yanxiufei.cn/Article/details/gtfosnipzm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gtafduqyva.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuanzx.com/Article/details/gtjwwhhwat.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.c1oappe.top/Article/details/gtufxanuoz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnxiangtu.top/Article/details/gtxptaeaio.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gtggrjirby.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtxzfwpbdo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gthmamriwy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jianghu66.top/Article/details/gtrgvaqmns.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cashguo.top/Article/details/gtlwfckhrb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gtfwqobeid.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gtfyrelamm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guannengcc.top/Article/details/gttrqsspix.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cashguo.top/Article/details/gtkbqtrlyz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gtigetwsvm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gtsauhpyik.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shzxlz.cn/Article/details/gthmwgrrsy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daria6918.cn/Article/details/gtuyasggft.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gteoybehnj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gtnkhzakmz.html

[D26] 数组转字符串
来源：http://dali.yvedp.cn/Article/details/gtowleblat.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzanybkvp.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gtlenbwbgv.html

JS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtvgattuzh.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtvfzfxmim.html

Java: String.join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtioyjkcwj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pengpengdd.cyou/Article/details/gthgrapzaa.html

Ruby: arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtvkyouyto.html

C#:   string.Join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gtfyijdxwr.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtjvosriom.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gtqdkogspx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtlqmapked.html

[E01] 拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtxihvgmrv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenjidiqi.icu/Article/details/gtrbvivezu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gtrsgxqwcv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtpjndegfu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtmhxbzwml.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtxdbwluzs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jianghu66.top/Article/details/gttvemutca.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gtvbyxhrft.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtnpaqsggv.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gtngdezfxc.html

Py:   "ab" * 3
来源：http://dali.ivvv.top/Article/details/gtzifgbkkm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gtqupaflgq.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtrafdsatp.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtagxlamwh.html

Java: "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtyetyyuvn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuxtopic.html

Ruby: "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtexztnqbq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pengpengdd.cyou/Article/details/gtqujgkkvl.html

[E03] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gtiwdcgsjk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aizwys.cn/Article/details/gtgrqeoosd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtzaekxdnu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtqepzhpli.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtfgltjqqw.html

Java: s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtdayyvaaj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gtzoqwfpwi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenzaomai.com/Article/details/gtplqjrpjb.html

C#:   s.Substring(1, 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtulgwspvg.html

[E04] 查找子串位置
来源：http://dali.sweek.top/Article/details/gtiyxjsxie.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtabnjsins.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gtqtzndavd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gtaaredpzo.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtkuyogpvn.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtsbbymgju.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigufen.top/Article/details/gtugubsfyg.html

Ruby: s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtrpspazjw.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcacajqfu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ehwqpu.com/Article/details/gtuzxzqjjk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yonumen.top/Article/details/gtmpafxzzy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gtcclhdnkq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtpyulpqdn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hammf.cn/Article/details/gtxdqrzxvf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtqbfjazgy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daria6918.cn/Article/details/gtvacgbxfq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shuidangran.top/Article/details/gtjlcowrmy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtelnksuux.html

[E06] 替换子串
来源：http://dali.smart0.xyz/Article/details/gtugdrowdc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gtxakadddf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cashguo.top/Article/details/gtizylfsxx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtuyvwaaxo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gturzjogpr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtblkyezeb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtertwlaau.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gtcdtegmdk.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gtzcwamomj.html

[E07] 按分隔符拆分
来源：http://dali.sysykeji.top/Article/details/gtztxznnrm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.quarkkingdee.top/Article/details/gtxxfisydk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtevsecosl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gtocijrtcn.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gtohcxgrfu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhengqikj.top/Article/details/gtdupvette.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gtdgtuvzni.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdrskcav.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtxgwcusny.html

[E08] 数组按分隔符合并
来源：http://dali.wangshuangyany.cn/Article/details/gteqkxwpwi.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gtcghyhaaw.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gtwtqqexgk.html

JS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtnsiysuja.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtedgojwen.html

Java: String.join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtraybnpzn.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gtqvsmbnso.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtektekjgm.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtynsbdpap.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gtouajqpbv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtmpbeciwx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gtcshekthn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gthzdnsmhm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gttxdzajww.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtmupaxpbd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gtmbaclxko.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gtmiqmcjka.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.havefunace.top/Article/details/gthllviqtu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gtygrskjie.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtvzegzoeq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.andypj.xyz/Article/details/gtpnyaorsh.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtrbkjsckm.html

TS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtptwejvwq.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtgcjkdcwp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtvgiykfxw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gthakcshwj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.havefunace.top/Article/details/gteqizewhs.html

[E11] 反转字符串
来源：http://dali.yvedp.cn/Article/details/gtgnwqjkwl.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gtzxgnjllq.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtzrqowixg.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtpsiubdja.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtyzcfkpyh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.0kj1m.cn/Article/details/gtzcmxkefa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cucudq.cn/Article/details/gtymvyjjvt.html

Ruby: s.reverse
来源：http://dali.9152youxi.cn/Article/details/gtzuivfcjd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gteychfiyx.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gtjtbguqql.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtxauqaatb.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gtytbmhejx.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtbfwdwwov.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtnsrslocq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gtaagcbtsd.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gttuccwixe.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtpmxkpddp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gtnhlqziyk.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gtqdgigoty.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gtfnjumkqf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gtgnbucwwy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtpdszfjfg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtflxwtnlf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtopmmuamd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtcixkzcge.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gtlzcxwzpg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gtpyuwtdgn.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gtwxzfspzm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gtlafvteuh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gtxokgxxdp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtifueeuxr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxinkj.top/Article/details/gtwqqwscqu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gtgplrcnda.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gtsqmecrsi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gtjaahyrvg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cheryme.top/Article/details/gtvencudrv.html

[E15] HTML 转义 / 反转义
来源：http://dali.c1oappe.top/Article/details/gtqmuunjnk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmukvtwj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gthhavlsto.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gtkrkeiuhz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.snrcjt.cn/Article/details/gtlydchlib.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gtbbibxrum.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtuammkrpm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuanzhike.top/Article/details/gteaqmcgrd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gotoacloud.top/Article/details/gtsutamgqw.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtupvuaqse.html

Py:   f"{1234567:,}"
来源：http://dali.shzxlz.cn/Article/details/gtabtngqwl.html

PHP:  number_format(1234567);
来源：http://dali.ppjwa.cn/Article/details/gtpxtoiorc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtsplrmgku.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtvnycvdhl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtgwhfmxwp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gtxearaoar.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gtgxncgjrt.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gtysforvip.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gthyewakaa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxinkj.top/Article/details/gtbptcszeo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gtdirmrmgh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtttgjdoee.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtnnbwbdgk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gttupgxpzc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.0kj1m.cn/Article/details/gtkqjxsuot.html

Ruby: s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gtpfnrowdc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gtfcjzgibi.html

[E18] 模板占位符替换
来源：http://dali.daxiang520.top/Article/details/gtylptcbqx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gtysrskqul.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gthrxclopq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcjtwtvf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtnitsxrwl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtwowjpjqv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gtfzcrmbuz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtpiwhlztj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gtnngyprcl.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gttgkcdbzj.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gtvccsqtgk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtpjoyshug.html


<!-- 参考信息 -->