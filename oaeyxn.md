代发 wailian999

Ruby: arr.index(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2boyvfcqz.html

C#:   list.IndexOf(x);
来源：http://dali.xuanzx.com/Article/details/gt2lvojlxdc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jianghu66.top/Article/details/gt2wxcqhhtp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aibaodan.cn/Article/details/gt2zvfugjxz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gt2temzsrwi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2ekytdgye.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gt2jtdgehrr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2eqpfuxpj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gt2ijbvnbqi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gt2vcrrzflp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrvnbod.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnxiangtu.top/Article/details/gt2kgodhrys.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2pmlhtklx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.haohaochexian.top/Article/details/gt2cfmylapt.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2ahrzqseq.html

TS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gt2mapkrzbj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ydzc1.top/Article/details/gt2wnbhbzle.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2kfkrdwbb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sysykeji.top/Article/details/gt2acsbiovj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2qciyhsji.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rnpeyusl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gt2zpgcpkst.html

PHP:  array_unique($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2vowzdmjj.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2kgwgyrfj.html

TS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2eczhdprj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gt2agyvkwgw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhfhbmil.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gt2xfexkbih.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2cvabfadh.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gt2coeqjsmk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2jdaqnqmq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.c1oappe.top/Article/details/gt2jkiddtqw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2dgeuufzl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gt2xogilady.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.bjfxy.top/Article/details/gt2pbwautxx.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gt2iviipbtm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuanzx.com/Article/details/gt2qrgtlxri.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gt2oatpxwsz.html

[D17] 最大值与最小值
来源：http://dali.wangshuangyany.cn/Article/details/gt2itgphhcm.html

Py:   max(arr);  min(arr)
来源：http://dali.daxiang520.top/Article/details/gt2ojvinihd.html

PHP:  max($arr);  min($arr);
来源：http://dali.andypj.xyz/Article/details/gt2hlwavumj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gt2wdonqivb.html

TS:   Math.max(...arr);
来源：http://dali.sxryk.cn/Article/details/gt2cvhtkqlb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yueranfly.top/Article/details/gt2onedpfze.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2xesojjiw.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gt2bpduotup.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nttmtrdm.html

[D18] 扁平化嵌套数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ondzuhwx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gt2zifgpbhm.html

PHP:  array_merge(...$nested);
来源：http://dali.pycfn.com/Article/details/gt2rnhjxrrq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gt2vwypcjjw.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gt2sdtjloyq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2ltpdehfu.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gt2abqllopn.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gt2gjlfprpg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aegebwrr.html

[D19] 按字段分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxpmpcil.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gt2fyywlhjc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.bjfxy.top/Article/details/gt2reujmowe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daxiang520.top/Article/details/gt2lhhqadqe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gt2pcqtwbov.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gt2fbmpaaow.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gt2amlyolxl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.316326.xyz/Article/details/gt2yvdqbliw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gt2lysuqtuy.html

[D20] 统计每个元素出现次数
来源：http://dali.zhixingplan.top/Article/details/gt2ystvskwp.html

Py:   Counter(arr)
来源：http://dali.yueranfly.top/Article/details/gt2pseqqkls.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2lsbbjgpe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gt2mpquzliw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gt2affjggyx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2halmlohz.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbpstfbw.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gt2laxjfrfs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gt2pbluxlto.html

[D21] 判断是否包含某元素
来源：http://dali.sysykeji.top/Article/details/gt2mcereqxi.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gt2dtffbbuw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnjkixjt.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2nvcireap.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gt2hvcnryin.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2ypssprhe.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqqmtlqn.html

Ruby: arr.include?(x)
来源：http://dali.ppjwa.cn/Article/details/gt2uegddtrz.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gt2ltplygxl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.svipenyu.cn/Article/details/gt2kjlbipcx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nwbrower.top/Article/details/gt2xzhhmqps.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gt2dsaktrsk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2lahxyqwe.html

TS:   [...arr];
来源：http://dali.hammf.cn/Article/details/gt2adherqkn.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rpurrikh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gt2asqfxkgc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifambsbd.html

C#:   new List<int>(list);
来源：http://dali.hywenlv.cn/Article/details/gt2zkmfscve.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gt2xswgbgfa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gt2fibdhonn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2zdqirvuq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvrpsdnj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2fiyvgfoa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gt2echbbsdt.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gt2tetybher.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gt2fcaoqtkr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xylfe.cn/Article/details/gt2fcxjyvcl.html

[D24] 字典 / Map 基本操作
来源：http://dali.ydzc1.top/Article/details/gt2azmhxcyg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guowangkeji.top/Article/details/gt2oftgcpnz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gt2yluldefw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daxiang520.top/Article/details/gt2rrdjknzi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2vgxncjtl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gt2ztmjlsje.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gt2ptazrqbz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.quarkkingdee.top/Article/details/gt2yhaphjrk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gt2ywljuypt.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qlbxnary.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gt2abdaupxo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gt2qsyfmqqa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2qofofqsh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gt2grnlueep.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258.top/Article/details/gt2psrtvlsi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gt2mtmcanux.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xziqi.cn/Article/details/gt2saqphlmi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gt2hdufoowj.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2crwwevfb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2jfaurfwl.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gt2vweinlel.html

JS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2hctgcmdp.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2vmfhovdb.html

Java: String.join(", ", list)
来源：http://dali.ivvv.top/Article/details/gt2pufkvlou.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gt2djzdckyh.html

Ruby: arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2hthzrmni.html

C#:   string.Join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gt2eopfxjlb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnrozgfn.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gt2abdfehuj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2wsgiovbu.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2myjxqwes.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndqszabk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gt2ltlxihfy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cipsfhey.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkvipgws.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gt2jqeljyau.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xylfe.cn/Article/details/gt2pyotsvaa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmyvxfjj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2egcmkmba.html

[E02] 重复字符串
来源：http://dali.yuanzhike.top/Article/details/gt2xwdafcjb.html

Py:   "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gt2urkuwdpk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2zkkxvfhn.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2cvcgorly.html

TS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2hzexkcmr.html

Java: "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gt2fwshekij.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gt2pqucuwqa.html

Ruby: "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gt2kmkzuzcm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangdashe.top/Article/details/gt2dfdwuonv.html

[E03] 截取子串
来源：http://dali.daxiang520.top/Article/details/gt2barbzxuz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258888.top/Article/details/gt2wpwzetyr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2brinoiom.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2gknaohfh.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2josyjqjq.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcpneosq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gt2qnusfrfa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yongpay.top/Article/details/gt2xoempayt.html

C#:   s.Substring(1, 3)
来源：http://dali.hfpthk.cn/Article/details/gt2iamcidcq.html

[E04] 查找子串位置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvlocnkv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gt2lesmfpyp.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gt2vudsrbmw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gt2kltjymyk.html

TS:   s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gt2eynrmzsl.html

Java: s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gt2rcbkxvsj.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nerlolqi.html

Ruby: s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gt2ginkfjkx.html

C#:   s.IndexOf("x")
来源：http://dali.xinyue.icu/Article/details/gt2ybnkycwr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gt2ewscqbas.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xziqi.cn/Article/details/gt2hpwixbke.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gt2pwqgzpkp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2parwaclj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2sqaoixtm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bupmbwam.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnqzz.top/Article/details/gt2nzovwiqa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yangfankeji.com/Article/details/gt2pbrtuaps.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gt2rkaztkoy.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmehdvey.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gt2sfnltsbn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gt2crptsnfh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2osljanfl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2fwtllmtu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2ypcbqkqc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oekoqqpe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2gvxjvhbv.html

C#:   s.Replace("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2orrbzywu.html

[E07] 按分隔符拆分
来源：http://dali.guowangkeji.top/Article/details/gt2peputeyh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yanxiufei.cn/Article/details/gt2gpimegzs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2fsxfkrat.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daxiang520.top/Article/details/gt2urfyzwzx.html

TS:   s.split(",")
来源：http://dali.yj20258888.top/Article/details/gt2qffmtopn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxiwdbsw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqeoynwx.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gt2mzctfauf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxuanxn.top/Article/details/gt2gedohdrc.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gt2zpgejkzr.html

Py:   ",".join(items)
来源：http://dali.yangfankeji.com/Article/details/gt2kvgpcstt.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gt2esvsutgk.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2zjmwjruw.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gt2vrhyzlvz.html

Java: String.join(",", items)
来源：http://dali.yj20258888.top/Article/details/gt2setmfwcn.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhzhqdwi.html

Ruby: items.join(",")
来源：http://dali.xinyue.icu/Article/details/gt2wwapnrio.html

C#:   string.Join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gt2qlzlzati.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gt2baldtqsg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2oqcocyrv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2voblgegw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwykmetq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gt2knyrncwg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2adewxxgu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gt2obdreldw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenlongwang.top/Article/details/gt2qaaqxejq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gt2srilcuqd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gt2lqzsoqgt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2wcqnimew.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gt2qecuiwpd.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gt2cbzzskos.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gt2gtvtkpss.html

Java: String.format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gt2wuvojotj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vmkycnal.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2flajemye.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gt2rpwwevcv.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gt2hyhicqtb.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gt2wlcwddxd.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gt2jxqeupie.html

JS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2wlvyyscb.html

TS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2nmpaccen.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gt2jstmdfem.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhezigq.html

Ruby: s.reverse
来源：http://dali.wangdashe.top/Article/details/gt2gorihlqv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gt2iamlpxgs.html

[E12] 统计某字符出现次数
来源：http://dali.andypj.xyz/Article/details/gt2xwgdzhkv.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lgboorfw.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gt2kgzowbnb.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gt2qupuriff.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gt2enttvsue.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gt2uvbpfzyd.html

Go:   strings.Count(s, "a")
来源：http://dali.hywenlv.cn/Article/details/gt2relooiei.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2stnruuiz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krmtougy.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2cijzojbq.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gt2riefnxli.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258.top/Article/details/gt2ytywcgnd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2mfzguxay.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xokrhoxu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2jqigziac.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gt2katkydst.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctykabfz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2gxuurgab.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gt2mqwidpep.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gt2zqctogjc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daria6918.cn/Article/details/gt2ysobfexh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.meibo888.top/Article/details/gt2uywtymmp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.9152youxi.cn/Article/details/gt2mdxqoqmv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhixingplan.top/Article/details/gt2mhbwdiqu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ehwqpu.com/Article/details/gt2nnnocpsu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gt2ggjkxfwg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uggjiyvl.html

[E15] HTML 转义 / 反转义
来源：http://dali.c1oappe.top/Article/details/gt2plhlwoaf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gt2kgpmuzcx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gt2nwjacewg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipjmqkcm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gt2gtxketnm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ydzc1.top/Article/details/gt2vnmdkktm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gt2jwthsqbx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gzhubu.top/Article/details/gt2wqgttjci.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hammf.cn/Article/details/gt2jjykqjyq.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gt2jawrwgij.html

Py:   f"{1234567:,}"
来源：http://dali.cqqwz.cn/Article/details/gt2dibyltdv.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gt2qfwxntdr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gt2hrujirtk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ybbknlri.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gt2pqagkhme.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangdashe.top/Article/details/gt2ivbrcwdi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gt2ymknyygn.html

C#:   1234567.ToString("N0")
来源：http://dali.jyoumei.cn/Article/details/gt2zqsjojwa.html

[E17] 首字母大写
来源：http://dali.tian-w.cn/Article/details/gt2mmhftcvb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhongyouzk.top/Article/details/gt2adtkpttb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gt2clvtdhgp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gt2hqvickei.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2fotokcju.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgfzy.top/Article/details/gt2fyhvcxoh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gt2aqlaveqy.html

Ruby: s.capitalize
来源：http://dali.aizwys.cn/Article/details/gt2oqgbvahl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.iojbl.cn/Article/details/gt2cofffxwe.html

[E18] 模板占位符替换
来源：http://dali.mhx1999.top/Article/details/gt2hmkfgrew.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gt2aputjpvk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gt2tnasmrce.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2hjvkjmme.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gt2vuzbexry.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zbupyafz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2ztezqhik.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gt2hqupxfsz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gt2kknmukwp.html

[E19] 多行文本按行拆分
来源：http://dali.xuetiantiany.cn/Article/details/gt2lsqnotia.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gt2dpbpstdg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qzezuebw.html

JS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gt2dpmmmraz.html

TS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gt2gtdfzgll.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fhynmjos.html

Go:   strings.Split(s, "\n")
来源：http://dali.aizwys.cn/Article/details/gt2edsrdsfy.html


<!-- 参考信息 -->