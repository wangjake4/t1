代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.yonumen.top/Article/details/gtgsjduwwi.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gteejegvzj.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gtljiqrxhz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gthfiizjpo.html

PHP:  sort($arr);
来源：http://dali.tianlin.xyz/Article/details/gtpnyhezvy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.svipenyu.cn/Article/details/gtfkagswhj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gtcyfwsxjd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.havefunace.top/Article/details/gtpsrhqpqf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtamkqdlkz.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtuscxbhpb.html

C#:   list.Sort();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdcjrrav.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gtcozeoghu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtoqnqsbms.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtmldlqpur.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtxbomruyz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtaahjmfvr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aizwys.cn/Article/details/gtborcglbk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yvedp.cn/Article/details/gtbgdfhnqj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yvedp.cn/Article/details/gtbxblbjpg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsiebsdj.html

[D11] 反转数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwvvxqsq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gthhrnpgce.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gtznubcusc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangdashe.top/Article/details/gtrxarpyju.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gtwoxtvfda.html

Java: Collections.reverse(list);
来源：http://dali.jqgfzy.top/Article/details/gtgezriqbj.html

Go:   slices.Reverse(arr)
来源：http://dali.c1oappe.top/Article/details/gtqbnqijdh.html

Ruby: arr.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtdgfevela.html

C#:   list.Reverse();
来源：http://dali.zycfv.cn/Article/details/gtrzsfzjnl.html

[D12] 查找元素下标
来源：http://dali.aizwys.cn/Article/details/gtzsxjdwea.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gtbvncmuzz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.haohaochexian.top/Article/details/gtiabnifkw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtevpcsxtf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gtiuhnjshs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.kuanghao11.cn/Article/details/gtqavvdsmj.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbufiqmcd.html

Ruby: arr.index(x)
来源：http://dali.snrcjt.cn/Article/details/gtpyzxdadw.html

C#:   list.IndexOf(x);
来源：http://dali.kuanghao11.cn/Article/details/gtktjmfnys.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gtunylbuis.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gtpdqlocrg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gtszbsmajd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtmyzsxndt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtgvvvszud.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtmugdrhwi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgewfquvh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gtnjxzbcff.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gtbbjmitrd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gtjlyvtzaa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtyeroevti.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gtfqboewzm.html

JS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gtujdnhyzn.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtojjjqhke.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cashguo.top/Article/details/gtkbboytma.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gttjxguxml.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtqlmuftzf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmcdrbxh.html

[D15] 去重
来源：http://dali.shzxlz.cn/Article/details/gtsoupowug.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gtqpisfihx.html

PHP:  array_unique($arr);
来源：http://dali.chenzaomai.com/Article/details/gtmonoealk.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtvkjjclas.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtldnbladj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gtljuuugsg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xylfe.cn/Article/details/gtplmxazxi.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gtugiiucvw.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gtspnsgdqs.html

[D16] 求和与平均值
来源：http://dali.chenjidiqi.icu/Article/details/gtridxtssn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gttglutcrb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtghgoutkb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gtkhgvinry.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtskcahrqr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gtpmgxxdpe.html

Go:   // 手写循环累加
来源：http://dali.shuidangran.top/Article/details/gthyecghnb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gtskpooidp.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gteltbtrop.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtrrswpcqt.html

Py:   max(arr);  min(arr)
来源：http://dali.yueranfly.top/Article/details/gtdglwtrcc.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gtswlddqgy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtplwvutna.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gtveqcemhb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gtrrvagejx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.redwolf501.top/Article/details/gtjlwzkbel.html

Ruby: arr.max;  arr.min
来源：http://dali.zhengqikj.top/Article/details/gtbnfoyxeh.html

C#:   list.Max();  list.Min()
来源：http://dali.meibo888.top/Article/details/gtvqqkjqbk.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtujylfbkd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gtwyivmxfh.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gtfftiamnf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gtjfuuuueo.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gtrdvaijqw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gtaougudly.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gttnagaedm.html

Ruby: nested.flatten
来源：http://dali.jyoumei.cn/Article/details/gtbhtyjaaa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gtayhqpkwq.html

[D19] 按字段分组
来源：http://dali.wangshuangyany.cn/Article/details/gtaanoqzcq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gtgwsewgbq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.smart0.xyz/Article/details/gtorqfpzrr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yongpay.top/Article/details/gtfyvqvlcf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gtdtxocajh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gtxsucbroa.html

Go:   // 手写 map[string][]T
来源：http://dali.birdmap.top/Article/details/gttshehpgb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gtlqjrkiax.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ehwqpu.com/Article/details/gtemrbzska.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gtqvpmgxex.html

Py:   Counter(arr)
来源：http://dali.cdnleiting.top/Article/details/gtdfybqtxd.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtavmdzgaq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtihprvttt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtwzcmpcan.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gttryoydei.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gtnzzojuah.html

Ruby: arr.tally
来源：http://dali.hysaishi.cn/Article/details/gtxhitzwoh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cdnleiting.top/Article/details/gthvgfquex.html

[D21] 判断是否包含某元素
来源：http://dali.nanxuanxn.top/Article/details/gteasmuvmd.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gtfvaobupz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnapiuifm.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtcoidsaun.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcnywtgo.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtmclkgwny.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtlazddskx.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtyigmzdts.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtatkyagdv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xylfe.cn/Article/details/gtxwxqlqii.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dashuyun.cn/Article/details/gttofyszvk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gttxggofmz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gtzvqrvbgb.html

TS:   [...arr];
来源：http://dali.nanxuanxn.top/Article/details/gtmysyvvhp.html

Java: new ArrayList<>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtiwkyehex.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gtkafmyjxp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gtbgcuinmz.html

C#:   new List<int>(list);
来源：http://dali.jiagoushi.top/Article/details/gtgbgpetxo.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gtxzfadxos.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yvedp.cn/Article/details/gttfzhszje.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtuzevufjd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtjuwpxhrr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxwtcjkw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gtrigqckjt.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtbdyrixxm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gtmilnpiis.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tanke756.top/Article/details/gtwgrpsdon.html

[D24] 字典 / Map 基本操作
来源：http://dali.meibo888.top/Article/details/gtgcfsgpdv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gtyngimdde.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gtdjedmjqo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtqpszxgzd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtcesuazix.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gtgmmvjtzu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gotoacloud.top/Article/details/gtskjjalzp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aizwys.cn/Article/details/gtarmskuqq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gtwtiltshg.html

[D25] Set 集合去重与交并差
来源：http://dali.yuanzhike.top/Article/details/gtrvaizplc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gtcviosmwx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gtkqoxhprp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gtebljzghg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gtnoxjpveb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtvgylirgj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yanxiufei.cn/Article/details/gtgextbxjv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yangfankeji.com/Article/details/gtqrqbooat.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gtejrywlhf.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gtmwaywvjc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtrjqvfxyy.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtzlojurxi.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtwjogomfn.html

TS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtjrkkbmql.html

Java: String.join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtghajxqmu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.c1oappe.top/Article/details/gtcfdpxhti.html

Ruby: arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtxphhmyub.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtsnqwrpgl.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdrgbczup.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gtrpdewenv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtkpryuknd.html

[E01] 拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtqsqvumhq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuanzhike.top/Article/details/gtwfdruewg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgnduuih.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtcrpatmmi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gtrqpipckz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gtjkvpaxew.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gtfohbiypz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.316326.xyz/Article/details/gtwrwrvijw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gtrcbaipeq.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gtmouqqhnp.html

Py:   "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gtvtziuuay.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gtwuehuxqu.html

JS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtwkpueyan.html

TS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtrjnzjboy.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gteruukwxa.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jlsjyb.cn/Article/details/gtcryvdkvg.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtiuqddadh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gtdcfuetdf.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtyxrosiqd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gogol.net.cn/Article/details/gtnxknjzvx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtlrmnfrju.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtcmegfscn.html

TS:   s.slice(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtavbvgtpw.html

Java: s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gthiggwxxr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtmrfmbjgz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.meibo888.top/Article/details/gtoyqsaito.html

C#:   s.Substring(1, 3)
来源：http://dali.mhx1999.top/Article/details/gtkxnyuxto.html

[E04] 查找子串位置
来源：http://dali.yuanzhike.top/Article/details/gtolikjcbh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtwepghjgg.html

PHP:  strpos($s, "x");
来源：http://dali.pycfn.com/Article/details/gtgifrehjs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlpezlxh.html

TS:   s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtokejonnv.html

Java: s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtuirvnvfa.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gtueekfsal.html

Ruby: s.index("x")
来源：http://dali.tian-w.cn/Article/details/gtvgcvbibi.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtyovmaroj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuetiantiany.cn/Article/details/gtetkgwdqc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dashuyun.cn/Article/details/gthakffmcg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aibaodan.cn/Article/details/gtcpoydnny.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtflcbxvqp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gtgvnlcjcc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtpcgawpek.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jianghu66.top/Article/details/gtuoyygnpf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgdwlfqp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtfocgtucr.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gtddqmlkkx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtyailpvkf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xinyue.icu/Article/details/gtfyfopehk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtedcxllmr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtjqfswmxy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtycfbvqvl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtzzigguzo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtjjryoctu.html

C#:   s.Replace("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtcufbomqw.html

[E07] 按分隔符拆分
来源：http://dali.ehwqpu.com/Article/details/gtvwbdsofn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gotoacloud.top/Article/details/gtiblduefr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtrzmjvuiu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.meibo888.top/Article/details/gtuqeatwtn.html

TS:   s.split(",")
来源：http://dali.jqgfzy.top/Article/details/gtiwkulhhu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj202588.top/Article/details/gtsntbhcfw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gthgctkxsf.html

Ruby: s.split(",");  s.split
来源：http://dali.yuanzhike.top/Article/details/gtikurrnno.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.316326.xyz/Article/details/gtlprwwvnw.html

[E08] 数组按分隔符合并
来源：http://dali.gogol.net.cn/Article/details/gtbxpyaglt.html

Py:   ",".join(items)
来源：http://dali.tanke756.top/Article/details/gtcjxiefle.html

PHP:  implode(",", $items);
来源：http://dali.sysykeji.top/Article/details/gtsdgnflmy.html

JS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtthyvswqo.html

TS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtypikqxeo.html

Java: String.join(",", items)
来源：http://dali.yongpay.top/Article/details/gtdnphplks.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gtfuryylpn.html

Ruby: items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtsqsyhndd.html

C#:   string.Join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtoxfknoyg.html

[E09] 去除所有空白字符
来源：http://dali.hysaishi.cn/Article/details/gtjzjkmwtf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gtkfcbkbie.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtrsglvovb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtnuzrzunk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtprqfnswt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtwpdhmrld.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtireoczdb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtwayjjogt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gtmjaxlusk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gtjblwgwty.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtjwzwlfen.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aizwys.cn/Article/details/gthlhjbgdr.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtzkheltvf.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtekkfdpkx.html

Java: String.format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtfwxxvjzp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtycxpticg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtukrnczpl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuetiantiany.cn/Article/details/gtzjyswchv.html

[E11] 反转字符串
来源：http://dali.sysykeji.top/Article/details/gtionkpibv.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtvohmuuxp.html

PHP:  strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtqpxmxsqp.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtutndisod.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtnnsrampz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ehwqpu.com/Article/details/gtquasvgfy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtuaxlxzax.html

Ruby: s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtnxuatbto.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gtqpmyqawj.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gthsmdvdod.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gttvcjoisl.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gtdobvnzfe.html

JS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtpayfndsp.html

TS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gthchqkmcq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.redwolf501.top/Article/details/gtalfxrrcu.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gthcefndib.html

Ruby: s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtzlepkzjp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xziqi.cn/Article/details/gtcavsdtew.html

[E13] 逐字符遍历
来源：http://dali.hnxiangtu.top/Article/details/gtsgguakav.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gtcdwddxvb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gttaazfzsl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtyqpjuvho.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gteoxfdbhh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtymokkpwd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hysaishi.cn/Article/details/gtabgtwmnl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczhbaqqz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtyjupxsem.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gtlxcpdvfm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gtuxzyswzr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gteghcpjpu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.svipenyu.cn/Article/details/gtyjofyjyc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gtazmudcof.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtjqmmgdxw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.vqdsnc.cn/Article/details/gtqpgfkhxy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gtfpygexhb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gtlrppsnuf.html

[E15] HTML 转义 / 反转义
来源：http://dali.ivvv.top/Article/details/gtbhilngvp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gtpsgmittp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gtbfwhlygp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ehwqpu.com/Article/details/gtysngynso.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gtrynmfzqd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yvedp.cn/Article/details/gtopiiruhk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.havefunace.top/Article/details/gtsgddkfhu.html


<!-- 参考信息 -->