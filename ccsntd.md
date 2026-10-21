代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.tian-w.cn/Article/details/gtdzntqqvf.html

C#:   a.Concat(b).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtigmxqqyy.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gtsdysaebm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtjahfswct.html

PHP:  sort($arr);
来源：http://dali.chenlongwang.top/Article/details/gtzfpjujwg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.kuanghao11.cn/Article/details/gtaswngckc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gtsiyzasgx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gtwizozthk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtfjdwibdn.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtepxqkgbl.html

C#:   list.Sort();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtzsrpnz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.redwolf501.top/Article/details/gtlypnpupm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzmfnqzz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gtzjwupeex.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtntnyvokn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtcoclvipq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.haohaochexian.top/Article/details/gtfrlahhwn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhiwuduotai.top/Article/details/gtvakvqmyu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.snrcjt.cn/Article/details/gtoeawsosx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gtfldasylj.html

[D11] 反转数组
来源：http://dali.gotoacloud.top/Article/details/gtpxapxfjb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.bjfxy.top/Article/details/gttoletjir.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gtdmumqozy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aibaodan.cn/Article/details/gtgtliianm.html

TS:   [...arr].reverse();
来源：http://dali.snrcjt.cn/Article/details/gtdnnecgvm.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtopzevnpc.html

Go:   slices.Reverse(arr)
来源：http://dali.yongpay.top/Article/details/gtpcnchwhh.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gtgjqtlgkv.html

C#:   list.Reverse();
来源：http://dali.nanxuanxn.top/Article/details/gtugusyadw.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gtiddyqibz.html

Py:   arr.index(x);  x in arr
来源：http://dali.0kj1m.cn/Article/details/gtvquxtnuc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtojrkhxzu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtvfcruvus.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gtkkmejjfe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gtuneukmgs.html

Go:   slices.Index(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtgeruzesu.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gtboahqfbl.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtrreyjepl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gtfcklcmxj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuanzhike.top/Article/details/gtbqwqjoyp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shuidangran.top/Article/details/gtynmqbuvy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gtfvgrvggz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gttbblolqv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gtibcniyut.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.c1oappe.top/Article/details/gtvlnthfqr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.svipenyu.cn/Article/details/gtqxicumkd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gthtpwlqky.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258.top/Article/details/gtegrgogqr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gtktqkpxqr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tian-w.cn/Article/details/gthonfocza.html

JS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gtblnozvxt.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtsjtalzvb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cashguo.top/Article/details/gtiqwnherc.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtpmamzxbj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gthphqtlmx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ybcxt.top/Article/details/gteybqnmdx.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gtjkktlvqa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxziacmos.html

PHP:  array_unique($arr);
来源：http://dali.yuanzhike.top/Article/details/gtxitghtns.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gtmikslpoe.html

TS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtpsjtlqle.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gtlvhpgkln.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangdashe.top/Article/details/gtdxkexjxy.html

Ruby: arr.uniq
来源：http://dali.xylfe.cn/Article/details/gtzaidgsxv.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gtcducpqhn.html

[D16] 求和与平均值
来源：http://dali.tianlin.xyz/Article/details/gtcnkfmkgf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fengsongda.top/Article/details/gtivfndfyn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sufxvd.cn/Article/details/gtfuehdirm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtdcwkgyxl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtwkjjbdvt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gtuispooli.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gtftjazpuo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtummrlxji.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gtqpnllull.html

[D17] 最大值与最小值
来源：http://dali.hywenlv.cn/Article/details/gtqjvvxykn.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gtcdodqssd.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gtyuavtqvd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtjxzpjijv.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gtpmxebugm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuteuleo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.haohaochexian.top/Article/details/gtnmrwzurg.html

Ruby: arr.max;  arr.min
来源：http://dali.tian-w.cn/Article/details/gturaakduw.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gtoujqwyvj.html

[D18] 扁平化嵌套数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzjxdyfe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ybcxt.top/Article/details/gthxhegtgi.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigufen.top/Article/details/gtkbadogwt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuxming.cn/Article/details/gtvtmiuhve.html

TS:   nested.flat();
来源：http://dali.ybcxt.top/Article/details/gtkjvtfaoy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gthtxijlse.html

Go:   // 手写双层循环
来源：http://dali.xylfe.cn/Article/details/gtgcragyqe.html

Ruby: nested.flatten
来源：http://dali.havefunace.top/Article/details/gtkckczljs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangdashe.top/Article/details/gtthfqpynd.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gtjzmrergu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pycfn.com/Article/details/gtiiwfjyow.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gogol.net.cn/Article/details/gtpksdvmmg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gttxgvytqd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gtcckhdgcy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtsscqgujw.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gtpugxvmbj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gtrsrspynl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gtadxgbcay.html

[D20] 统计每个元素出现次数
来源：http://dali.iojbl.cn/Article/details/gtopzaaren.html

Py:   Counter(arr)
来源：http://dali.yvedp.cn/Article/details/gtkjumcxuc.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlksgovm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtsxcbsdem.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gtxlpuxdew.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssrkddpr.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gtudsexhsv.html

Ruby: arr.tally
来源：http://dali.xuanzx.com/Article/details/gtolcteltu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gtlbisevnl.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gtrvthygse.html

Py:   x in arr
来源：http://dali.yj20258.top/Article/details/gtsgubkcpe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.0kj1m.cn/Article/details/gthchevmml.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtfhauqaof.html

TS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtknktnuxs.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtqqzpyovq.html

Go:   slices.Contains(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtwueptvmg.html

Ruby: arr.include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozswsflq.html

C#:   list.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gthtughxgi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gtlkbjfzvq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtqtewbrmn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gtuvkimhvx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xziqi.cn/Article/details/gtebyuoywo.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gthryatofp.html

Java: new ArrayList<>(list);
来源：http://dali.nwbrower.top/Article/details/gtctqyhqzb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ehwqpu.com/Article/details/gtgnaucpew.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guowangkeji.top/Article/details/gtzzbufzay.html

C#:   new List<int>(list);
来源：http://dali.fengsongda.top/Article/details/gtlbwpeear.html

[D23] reduce 累积计算
来源：http://dali.9152youxi.cn/Article/details/gtakovykph.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtcaeykzgw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtcxshpdhl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtzibdktke.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtpzudkvup.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gtyfrykrkn.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtwcavfdry.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gtgvidotyw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gotoacloud.top/Article/details/gtnurrgwma.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gtkwnsjbcw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tian-w.cn/Article/details/gthssjrhdj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgfzy.top/Article/details/gtrjalqavw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gtrvjljukf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtogmhjalk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gteambkvhu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zycfv.cn/Article/details/gtwtekzykm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gtwybwulsf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gtxvtutjiv.html

[D25] Set 集合去重与交并差
来源：http://dali.quarkkingdee.top/Article/details/gtzhyjcsua.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangdashe.top/Article/details/gtaxtehihq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sysykeji.top/Article/details/gtmuehidjc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tian-w.cn/Article/details/gtzafhfnll.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.kuanghao11.cn/Article/details/gtaewjbgdh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfezbbvsv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dianchejie.cn/Article/details/gtliqrvzmb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jianghu66.top/Article/details/gtzwczoobi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gtrtkhznsy.html

[D26] 数组转字符串
来源：http://dali.yj20258.top/Article/details/gtyfmewdcr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gteculxamo.html

PHP:  implode(", ", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gthrrmrkxv.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtjuiilims.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtfmerxdxk.html

Java: String.join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtxstdplcj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gtwovzgvld.html

Ruby: arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtghuqrvjm.html

C#:   string.Join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtciejitmt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtvidkdksc.html

E. 字符串处理
来源：http://dali.yongpay.top/Article/details/gtojmvrdxw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtovarxhvv.html

[E01] 拼接字符串
来源：http://dali.yuxming.cn/Article/details/gttcjtldhi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xziqi.cn/Article/details/gtbtoirxbh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daxiang520.top/Article/details/gtomhripbh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtwsjurdgh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtyhhkaewf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sweek.top/Article/details/gtsbyjsvkm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jianghu66.top/Article/details/gttoyfmznf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shangyingyoupin.top/Article/details/gtljqhsbyq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtolvojqqc.html

[E02] 重复字符串
来源：http://dali.smart0.xyz/Article/details/gtcqpdmfsl.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtwupiadiz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gtspnwnrnv.html

JS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gttaaouevq.html

TS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gteewioqis.html

Java: "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtjavvknya.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxuanxn.top/Article/details/gtvtudwpkh.html

Ruby: "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtwndebwzf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gtcszlrskg.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtquohbwxi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gtimaxjcok.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gttyfrqxko.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtnnlccwui.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gtlvwkyhcm.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gttnyfvvpa.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cashguo.top/Article/details/gtpqomobkv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jyoumei.cn/Article/details/gtbthgkuvy.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtswdbaqeu.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gtdrywswyj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tanke756.top/Article/details/gtbhsswwyw.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gtqijrgfct.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gtwrgtwgng.html

TS:   s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtdvmffxxk.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaltggsiv.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gtqdegomwu.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gthabivjct.html

C#:   s.IndexOf("x")
来源：http://dali.yongpay.top/Article/details/gtvrfhqdve.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aibaodan.cn/Article/details/gtyyeypida.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cheryme.top/Article/details/gtqhggwmop.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.iojbl.cn/Article/details/gtnaijtkyh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtkdigqovi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ybcxt.top/Article/details/gtbccdkpal.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtthmvbtus.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenlongwang.top/Article/details/gtnktnwrcz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtmqkplfgn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtahkrcqaq.html

[E06] 替换子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfnpmuho.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gttiivejlb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gtfvvkysvo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtwsyxnrog.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtejmujaho.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtxoqlrbbj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtjywchnfy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gthxwmqlsk.html

C#:   s.Replace("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtzzpytoph.html

[E07] 按分隔符拆分
来源：http://dali.yj202588.top/Article/details/gtiphpwhmb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.iojbl.cn/Article/details/gtcbonupyx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtzipdalws.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gtkcvfmnkr.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gtkxiciufx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258.top/Article/details/gtrbutuiul.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daxiang520.top/Article/details/gtxdcddzhp.html

Ruby: s.split(",");  s.split
来源：http://dali.jiagoushi.top/Article/details/gtoukhrlgy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gtmprojtdf.html

[E08] 数组按分隔符合并
来源：http://dali.zycfv.cn/Article/details/gtylgrxhlb.html

Py:   ",".join(items)
来源：http://dali.hnxiangtu.top/Article/details/gtlbxrbwzw.html

PHP:  implode(",", $items);
来源：http://dali.aibaodan.cn/Article/details/gtxpxtcttj.html

JS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtvspssrfd.html

TS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtgmqtbpsw.html

Java: String.join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtzrycabrz.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gtmdcrplub.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtadafydxp.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gtydyzstqj.html

[E09] 去除所有空白字符
来源：http://dali.ivvv.top/Article/details/gtcmbftbou.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ivvv.top/Article/details/gttkmcaqjy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gtzqkmcwgj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtatzcqomc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gtbxwmfylc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.birdmap.top/Article/details/gtrwtoqkhz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtiqsirmob.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gtbjildpnt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtvwfaevja.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhiwuduotai.top/Article/details/gtndqfvtze.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtkflpqlyh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoaqgbnmg.html

JS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtvcvhpjvp.html

TS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gthnslduph.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gteusgavkr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtinxbpctx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtojwndffp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gtgicxukir.html

[E11] 反转字符串
来源：http://dali.ivvv.top/Article/details/gtshykthmc.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtldtpsblv.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtjpyghxup.html

JS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtapkjqddn.html

TS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtsiwauxgg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.9152youxi.cn/Article/details/gtjhqxpbuh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtfhrfgipb.html

Ruby: s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtuhvxbmcn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtmzsdycbi.html

[E12] 统计某字符出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtnwxqjfnx.html

Py:   s.count("a")
来源：http://dali.smart0.xyz/Article/details/gtrrmozhzh.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gtvcpsasab.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtnjxrcumt.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtputsttif.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tian-w.cn/Article/details/gtdcoipywm.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gteguyfruc.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtjyowedlt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hammf.cn/Article/details/gtgfatkqcb.html

[E13] 逐字符遍历
来源：http://dali.hnqzz.top/Article/details/gtiisaifry.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gtxknqrtqw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenlongwang.top/Article/details/gtyoazwfhf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtgenyzpdh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtzgyfbixe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sxryk.cn/Article/details/gtqadqlfzx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunuvvhxn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gtrfxmgqiq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtysvkufjw.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigfzy.top/Article/details/gtebrxbjkx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gtbflzycof.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtcxpzvqkt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuanzhike.top/Article/details/gtueijorcp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgfzy.top/Article/details/gtideybxco.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gtbtdcmchg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gtakmcfkey.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqdkkfuu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gtrnksiaxo.html

[E15] HTML 转义 / 反转义
来源：http://dali.bjfxy.top/Article/details/gtghmmgijq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.meibo888.top/Article/details/gtaepncbrq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cucudq.cn/Article/details/gtbmkxfrmb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pycfn.com/Article/details/gttgaglaop.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gtkflgqfkc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hysaishi.cn/Article/details/gtmjfsoovt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtplbeczni.html


<!-- 参考信息 -->