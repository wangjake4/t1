代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gt2ycvcdeoa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iialpfzp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gt2hxvaxrjy.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2iheonibe.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mnkomuob.html

C#:   list.IndexOf(x);
来源：http://dali.guannengcc.top/Article/details/gt2iiwzwttx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocmqxkzj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2suhroddx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ivvv.top/Article/details/gt2xwxumhox.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gt2aowhxpqx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gt2jpjbabfe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.birdmap.top/Article/details/gt2yhtotttq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gt2atliwhen.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.mhx1999.top/Article/details/gt2taatqsbe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2fojiospw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gt2wtyoldpf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2xwfhvgxa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gt2qiqkvjmr.html

JS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gt2askfzqvt.html

TS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gt2tapxncki.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2ionvwlet.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmasxrtl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2seysniwk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2vnxkvapt.html

[D15] 去重
来源：http://dali.wangdashe.top/Article/details/gt2sxrqpimm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gt2sknoggut.html

PHP:  array_unique($arr);
来源：http://dali.havefunace.top/Article/details/gt2ezhlmuxq.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gt2vmidlkpm.html

TS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpzltnva.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gt2jkgbjwik.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sysykeji.top/Article/details/gt2cjzhaoic.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gt2yhdvlojf.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2asknpsvf.html

[D16] 求和与平均值
来源：http://dali.jinqigfzy.top/Article/details/gt2vnpruoif.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2gziayygh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gt2mkbwcenh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gt2rdvqnwyx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2pbjhguxs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jyoumei.cn/Article/details/gt2vijjlofj.html

Go:   // 手写循环累加
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewjoviiv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gt2fvgbpxiy.html

C#:   list.Sum();  list.Average()
来源：http://dali.vqdsnc.cn/Article/details/gt2ulrahkqv.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gt2ijncucmp.html

Py:   max(arr);  min(arr)
来源：http://dali.tian-w.cn/Article/details/gt2rojqhrhf.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2ymauuasq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aibaodan.cn/Article/details/gt2tfmtuuqq.html

TS:   Math.max(...arr);
来源：http://dali.guannengcc.top/Article/details/gt2biyubnwi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ydzc1.top/Article/details/gt2udulxsdu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2zniykowy.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gt2zwljztiu.html

C#:   list.Max();  list.Min()
来源：http://dali.daxiang520.top/Article/details/gt2ufqsoznu.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gt2oizzygoe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gt2saunytjr.html

PHP:  array_merge(...$nested);
来源：http://dali.jianghu66.top/Article/details/gt2yyjvufcx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daxiang520.top/Article/details/gt2acmparus.html

TS:   nested.flat();
来源：http://dali.fzhhl.top/Article/details/gt2zuohvobq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2bkwneowl.html

Go:   // 手写双层循环
来源：http://dali.chenzaomai.com/Article/details/gt2hkljlqjc.html

Ruby: nested.flatten
来源：http://dali.hnqzz.top/Article/details/gt2iudqchtd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2inbyfabm.html

[D19] 按字段分组
来源：http://dali.yanxiufei.cn/Article/details/gt2fbsnudxv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2zwiprzje.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gt2qesmhpvl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqqeplsq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmaxnkgl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gt2yzkoolru.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gt2rgkiajvm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gt2gclhjubt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gt2dbpuudbg.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gt2pjqtguaw.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2vsponcch.html

PHP:  array_count_values($arr);
来源：http://dali.xuanzx.com/Article/details/gt2vqgwxyob.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gt2xmfdjfrl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlsfaesj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guowangkeji.top/Article/details/gt2poamagwu.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gt2bvjxyvjt.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gt2oewtnvnh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gt2ezopcomf.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gt2nlkmnimk.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gt2uuyeewbm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guannengcc.top/Article/details/gt2lpdzajlk.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2sfulkqvr.html

TS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gt2itazhtzf.html

Java: list.contains(x)
来源：http://dali.sysykeji.top/Article/details/gt2ibsexzxc.html

Go:   slices.Contains(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2zaqutdep.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gt2anklwlav.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2jkzlmpbi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gt2ytbxgncb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgjisurq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gt2hwcitszn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2jcpnazre.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gt2fvjdtmdx.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gt2odupnwul.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gt2iwwrcqdd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gt2hahqefoq.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gt2ivzcbbnu.html

[D23] reduce 累积计算
来源：http://dali.zhengqikj.top/Article/details/gt2tyidxzyt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2narezdrw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ydzc1.top/Article/details/gt2symefaxt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gt2kibajcmv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxwnlvyg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gt2njrxblwo.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gt2fcefdwbu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.0kj1m.cn/Article/details/gt2cgfzwsea.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gt2zlrhcvci.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gt2ipwesboi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfjgcftb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj202588.top/Article/details/gt2mouzqwap.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.redwolf501.top/Article/details/gt2qwcgicov.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2wlrpaoow.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.iojbl.cn/Article/details/gt2uzmrhehj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2suyrlmbs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daria6918.cn/Article/details/gt2hxecvnax.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gt2quwfrruv.html

[D25] Set 集合去重与交并差
来源：http://dali.gaohongyu789.top/Article/details/gt2weujvfmn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gt2zxzyhdzk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gzhubu.top/Article/details/gt2jkoeipsn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gt2ckpedpmy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yanxiufei.cn/Article/details/gt2gsnqbmyu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gt2htuibtyt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangdashe.top/Article/details/gt2eirqinox.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gt2hmixedyl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2izwbcfnj.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gt2iyugsefg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2yjjebgvq.html

PHP:  implode(", ", $arr);
来源：http://dali.nwbrower.top/Article/details/gt2ibrqtrav.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2mgkcujct.html

TS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gt2jvkjsovm.html

Java: String.join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gt2olryeyax.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gt2izsunyhn.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gt2sqwdkzhr.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2degpwwho.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tsqhxrmb.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gt2jdjrmoss.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2nrscaowf.html

[E01] 拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2ggegbxmn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tianlin.xyz/Article/details/gt2kiugupje.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gt2mylaaozb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2dhmnwtnd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2jzngnxmw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.svipenyu.cn/Article/details/gt2ltpzhulg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wkzejqud.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fzhhl.top/Article/details/gt2mbsuvttl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2drmkamrp.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gt2sjpbohwn.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gt2rahjdcbh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ydzc1.top/Article/details/gt2nnpqvihk.html

JS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2npidzbfv.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gt2huwjjrbq.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2jmsennpa.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hokkipnm.html

Ruby: "ab" * 3
来源：http://dali.hammf.cn/Article/details/gt2fapggckg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daxiang520.top/Article/details/gt2mnoxpmfq.html

[E03] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gt2liiehjnq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangdashe.top/Article/details/gt2wpalkdch.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2ybxfjokt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2cvazjjwz.html

TS:   s.slice(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2tucxoftn.html

Java: s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2ayggzwbg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hfpthk.cn/Article/details/gt2mvrvlkpe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gt2tfjxsyrn.html

C#:   s.Substring(1, 3)
来源：http://dali.nwbrower.top/Article/details/gt2bklkxfap.html

[E04] 查找子串位置
来源：http://dali.0kj1m.cn/Article/details/gt2esshuhvd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yueranfly.top/Article/details/gt2uludylki.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gt2juoumzyb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gt2xtcwlglj.html

TS:   s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2vyettclo.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gt2wriplawk.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gt2qzqmwdcz.html

Ruby: s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gt2glzpfjpo.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gt2bidbwmqp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gt2acpksagz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2nvghvprj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gt2oeptloyt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2zvigolay.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2ykmtqxqz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gt2pgpeuqjd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gt2zygdjubd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hammf.cn/Article/details/gt2dxwjivwj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2igdgavzp.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gt2fdugolzg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2tdkkjgnq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258.top/Article/details/gt2vaznmcjw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2fqegfqca.html

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2kocmgfef.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2anfeubjz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2euxxktzd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2izehludb.html

C#:   s.Replace("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2ckqizxto.html

[E07] 按分隔符拆分
来源：http://dali.guowangkeji.top/Article/details/gt2pnqcaphd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guowangkeji.top/Article/details/gt2mjahisgt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2albljdhx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gt2nharxqyo.html

TS:   s.split(",")
来源：http://dali.cucudq.cn/Article/details/gt2ahhskufp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ydzc1.top/Article/details/gt2iglumbfi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lfxczaux.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gt2wqqtwdcq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdmzpkbp.html

[E08] 数组按分隔符合并
来源：http://dali.aizwys.cn/Article/details/gt2dngtgcvv.html

Py:   ",".join(items)
来源：http://dali.kuanghao11.cn/Article/details/gt2xoesfphc.html

PHP:  implode(",", $items);
来源：http://dali.daria6918.cn/Article/details/gt2ycjymylx.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gt2puwdndli.html

TS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ogunfpku.html

Java: String.join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2msujbxzl.html

Go:   strings.Join(items, ",")
来源：http://dali.gaohongyu789.top/Article/details/gt2rybxthku.html

Ruby: items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gt2oqnnbqra.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gt2bovisxip.html

[E09] 去除所有空白字符
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2phvhbrls.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2jtacyzip.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pycfn.com/Article/details/gt2ggjzrspy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gt2vybejzms.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gt2vvspstuc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeupvvy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jatyclhp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gt2hcamcgpg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hammf.cn/Article/details/gt2cmaxjfqp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gt2jclcfeei.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2lsbmrwqu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yonumen.top/Article/details/gt2sykpyjgj.html

JS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gt2wtbjonos.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2vacmqjhm.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2cijghqig.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2zhrfcnin.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gt2gzcgbeyy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gt2muurlxmc.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2pmgzloxl.html

Py:   s[::-1]
来源：http://dali.fengsongda.top/Article/details/gt2efbkfxhi.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gt2byhyxwku.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujemqlhw.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2yfwpsxxz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgfzy.top/Article/details/gt2yroqjqbn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.bjfxy.top/Article/details/gt2jzmhwyta.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2dnvuhoih.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gt2ypiwonpz.html

[E12] 统计某字符出现次数
来源：http://dali.quarkkingdee.top/Article/details/gt2jlwjqxqm.html

Py:   s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzwuzsvj.html

PHP:  substr_count($s, "a");
来源：http://dali.yvedp.cn/Article/details/gt2rikpiske.html

JS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdyzhsbc.html

TS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gt2ifqldpek.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dashuyun.cn/Article/details/gt2udvbjjas.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gt2qxialdql.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gt2qqvdwwoi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jlsjyb.cn/Article/details/gt2mgicavbj.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2wurtgqxp.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gt2fnvfqokx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjochoy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gt2jglcgkis.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2rexfbuqc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2sygejhbm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2yngqgssw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gt2kgmieztr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2jbljocbk.html

[E14] URL 编码与 Base64
来源：http://dali.chenlongwang.top/Article/details/gt2urydzucd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jyoumei.cn/Article/details/gt2whvcoqlg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jyoumei.cn/Article/details/gt2mfexrrog.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuanzhike.top/Article/details/gt2lfnxltcc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gt2xezkupqn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2vzefuebu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.meibo888.top/Article/details/gt2gszwieqm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.smart0.xyz/Article/details/gt2eitkokke.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gt2lhbqqzhd.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuxming.cn/Article/details/gt2hnuhtssx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gt2vwbezzmj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gt2ypsbqpfh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2momhmcbg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2yiboeddk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aizwys.cn/Article/details/gt2pkyixknf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gt2pgszhmxg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uugbmwse.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gt2feypjfza.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmqgjqyy.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gt2jajyntzt.html

PHP:  number_format(1234567);
来源：http://dali.yonumen.top/Article/details/gt2puwnmpog.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gt2qnqmtedj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gt2sxerfjmx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gt2aabwsxxl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gt2jauloyoj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gt2lsaguabd.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gt2hjvacuyl.html

[E17] 首字母大写
来源：http://dali.jyoumei.cn/Article/details/gt2iofofuqf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gt2emttivhq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2lwxbbocb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gt2dkyfxrrs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gt2qfobkkcl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gt2whweyssw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gt2bvvopsel.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgmuwbbh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjoholzw.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gt2rbbgsurl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.c1oappe.top/Article/details/gt2jhneywqk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ylzunyls.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2gtjybhwp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2uibrpwqf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2oyhtiqxq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ddqsbzjx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gt2zwxbspys.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jianghu66.top/Article/details/gt2dlylzkyc.html

[E19] 多行文本按行拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2picmgjhi.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gt2hhshyofp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gt2pupjlwhb.html


<!-- 参考信息 -->