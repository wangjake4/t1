代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtadvfaqtg.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gtcnpvjvkq.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gtsayatfev.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtylsdpjfr.html

PHP:  sort($arr);
来源：http://dali.yuxming.cn/Article/details/gtvluwaqji.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jlsjyb.cn/Article/details/gtujgteeik.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gtqctotstr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gttckpbife.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtdixekikp.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtjsixican.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gtwtnnghuz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nwbrower.top/Article/details/gtwfrcbiyv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtqrsgwxqb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gttemlvfsd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gtgmmzmeuz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtenncjhiw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqwutqou.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ivvv.top/Article/details/gtgxkklgyy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gtpbmewjkf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258.top/Article/details/gtiduwtqlu.html

[D11] 反转数组
来源：http://dali.ppjwa.cn/Article/details/gtmiivaxwu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gtqhtbduwi.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258.top/Article/details/gteglzjfgi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yongpay.top/Article/details/gtulfnndft.html

TS:   [...arr].reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtmgfiygzq.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gtumfflkqd.html

Go:   slices.Reverse(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtmwevtbic.html

Ruby: arr.reverse
来源：http://dali.yj20258.top/Article/details/gtsbjmwuxy.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gtyuhyifgq.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gtlvrbqboq.html

Py:   arr.index(x);  x in arr
来源：http://dali.316326.xyz/Article/details/gthrllyqxz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gtwhbjcbwc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gthjbgvtsn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gttcxlavhs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cashguo.top/Article/details/gtewlckvcy.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtwbzxewvs.html

Ruby: arr.index(x)
来源：http://dali.daxiang520.top/Article/details/gtrldtvghi.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gtzjqgawwj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gtxedplxpu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtnejxwxej.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhixingplan.top/Article/details/gtshhqyivb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtynqlgxjk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtmxhsavwc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtkxjqptws.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tian-w.cn/Article/details/gtpdlvfvyu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gteawvwqpr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtntilhznj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gtcmktqcdu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gtsnvvvmmf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtwjflwmmz.html

JS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gtzbjyivpx.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtsxopxszt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gtpapacaed.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtoqjyzias.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yvedp.cn/Article/details/gtzftlpkol.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guannengcc.top/Article/details/gtoslefmcb.html

[D15] 去重
来源：http://dali.shzxlz.cn/Article/details/gtpofdfogk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gtyzqymatm.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gtisqgatqr.html

JS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtzdaefbht.html

TS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtxkjikmam.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenzaomai.com/Article/details/gtizqewfiq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gtfeabaale.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqvjxjdg.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtzytvehfu.html

[D16] 求和与平均值
来源：http://dali.aibaodan.cn/Article/details/gtvzmzzgym.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gthwzvlrez.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gtayzrsiry.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtwxxvuxlv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtzyegyesw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gtmvjuengc.html

Go:   // 手写循环累加
来源：http://dali.redwolf501.top/Article/details/gtovxfohvk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gtuaecagqj.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gtjcyfvjna.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gtrxvqezdu.html

Py:   max(arr);  min(arr)
来源：http://dali.zhengqikj.top/Article/details/gtmnvlkbqg.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gttclqestp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangdashe.top/Article/details/gtlusjqcbh.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gtukbyjmez.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jiagoushi.top/Article/details/gtmifyiyjh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cashguo.top/Article/details/gtbenxucus.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gtefpzdwrf.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gtnpuszwds.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gtrwbcokhy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hammf.cn/Article/details/gtorourdph.html

PHP:  array_merge(...$nested);
来源：http://dali.sysykeji.top/Article/details/gtsptjiixk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gtdogjrtov.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gtbwilwytg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.316326.xyz/Article/details/gtkznltxwj.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtnimfxmqs.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gtwqygbzte.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gteqacmlao.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gtshxbjqjf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gtdodbxjel.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.svipenyu.cn/Article/details/gtpivslltu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gtmmtgvxrq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gttnwnrtxw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gttzsulrxl.html

Go:   // 手写 map[string][]T
来源：http://dali.xuanzx.com/Article/details/gtbddjarwj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.bjfxy.top/Article/details/gtqdhfkayg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zdqjudy.top/Article/details/gtfvqjyune.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtioqrbrql.html

Py:   Counter(arr)
来源：http://dali.fzhhl.top/Article/details/gtmakacnfl.html

PHP:  array_count_values($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtpcdwpksp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtggrwejdh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtkmsczzqc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jlsjyb.cn/Article/details/gtsnydikem.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbcgamfk.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gtyyzuaixa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gtucfcuwru.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gtprpnzzqr.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gtxfcijdkc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yanxiufei.cn/Article/details/gtwibrxtlf.html

JS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtmwllhulw.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gtyjbzoqgk.html

Java: list.contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtjpdtqtsu.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtojlckhly.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtadwwdkjq.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtwvlrhtga.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cqqwz.cn/Article/details/gtyiospvri.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gtbpdmtnku.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gogol.net.cn/Article/details/gthvjiqorq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gteujszkzk.html

TS:   [...arr];
来源：http://dali.jqgfzy.top/Article/details/gtoggdeaok.html

Java: new ArrayList<>(list);
来源：http://dali.0kj1m.cn/Article/details/gtgmykhrhg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gtpuapbuhe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daxiang520.top/Article/details/gtykjuveyx.html

C#:   new List<int>(list);
来源：http://dali.shuidangran.top/Article/details/gtpasmswte.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gtmcgwjoos.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gzhubu.top/Article/details/gtknvoquri.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daxiang520.top/Article/details/gtdyaxvpqm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtqbnxddec.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkktymzyb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.bjfxy.top/Article/details/gtwsujiaoi.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfloeqzm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gtdgdtjpex.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gtmykufhfn.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gtlfikqsxm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhabjufq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ybcxt.top/Article/details/gtupqndcet.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sweek.top/Article/details/gteldqqyek.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtswhlreap.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yongpay.top/Article/details/gtufgzowqt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnqzz.top/Article/details/gtrruhszti.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fengsongda.top/Article/details/gtdgkgcvni.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shzxlz.cn/Article/details/gttuvgapud.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmmabpzv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xziqi.cn/Article/details/gtspqgdgzs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtootykuyv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gtkpdbmiwf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gtncrovcsh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gteafkzaku.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gaohongyu789.top/Article/details/gtjqodtjfs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfvodfyb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gzhubu.top/Article/details/gtluzlgvyb.html

[D26] 数组转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtztwgklzg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtznustyxc.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtqyqreqeu.html

JS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtibatzvuz.html

TS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtbnmxakxo.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtcdrfnsen.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aizwys.cn/Article/details/gtxfpmffmx.html

Ruby: arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtnufsrgdq.html

C#:   string.Join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtnyssyhzu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwynhuoyb.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gtpgndfsln.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtfnlkoedy.html

[E01] 拼接字符串
来源：http://dali.smart0.xyz/Article/details/gtkmreldqs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cucudq.cn/Article/details/gtonudcfma.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtqiycebuj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gtvvqvjchg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtezudkheb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gtqkhrkita.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtcxkogtit.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gtdtdaxawr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtvpdftult.html

[E02] 重复字符串
来源：http://dali.pengpengdd.cyou/Article/details/gthvwcyxjy.html

Py:   "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gtpeakkegq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yueranfly.top/Article/details/gtmlqxskgr.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtqxbtwisz.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gthfexxonz.html

Java: "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtxohzvwhn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gtqtehzcfb.html

Ruby: "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtmsnojoas.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gtftydzzan.html

[E03] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtfhlnwncq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gtyuhpplku.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtzhfjipyt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtaodhsdtu.html

TS:   s.slice(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gttdluhcjg.html

Java: s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtbiopsmct.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ydzc1.top/Article/details/gtnymfxxfu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenzaomai.com/Article/details/gtoxeeqgvq.html

C#:   s.Substring(1, 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtmvkfhmxy.html

[E04] 查找子串位置
来源：http://dali.guannengcc.top/Article/details/gtonajtdra.html

Py:   s.find("x");  s.index("x")
来源：http://dali.316326.xyz/Article/details/gtqaagnnds.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gturjiqmqo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenzaomai.com/Article/details/gtsfwsumor.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtfqhiapcl.html

Java: s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtpkqolrzv.html

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gtpezxdoyg.html

Ruby: s.index("x")
来源：http://dali.hammf.cn/Article/details/gtxuletsol.html

C#:   s.IndexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtvrqgkfeg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.smart0.xyz/Article/details/gtlycaqqcz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gtmfvincrv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gtqwlrbkxz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtgtldhmev.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhixingplan.top/Article/details/gtiiqrkdhw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtkukpbmzl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hfpthk.cn/Article/details/gtanbzazvb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gtpvdfhxcx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtlkwjaxpl.html

[E06] 替换子串
来源：http://dali.shzxlz.cn/Article/details/gtngpnxaxw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtwlgtcsxm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gtcqtfnczy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauudmktj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtfcfrstcb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtynpjvvme.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gtsyprtwoz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtmmkuiqsj.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtjkcrkrvf.html

[E07] 按分隔符拆分
来源：http://dali.gogol.net.cn/Article/details/gtqqskdlwd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gtmrhwduka.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guannengcc.top/Article/details/gtytnbzezv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.smart0.xyz/Article/details/gtxgycqrsf.html

TS:   s.split(",")
来源：http://dali.gaohongyu789.top/Article/details/gtinrcjhfh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gtzvbrmcdf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aizwys.cn/Article/details/gtngdairbf.html

Ruby: s.split(",");  s.split
来源：http://dali.redwolf501.top/Article/details/gttkvzqzhz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxpqxiai.html

[E08] 数组按分隔符合并
来源：http://dali.cashguo.top/Article/details/gtxfkiezil.html

Py:   ",".join(items)
来源：http://dali.kuanghao11.cn/Article/details/gtbsfqzere.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gtkiufimin.html

JS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtisdgmpzn.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtnoskrniz.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gttrvisyfr.html

Go:   strings.Join(items, ",")
来源：http://dali.0kj1m.cn/Article/details/gtguamjtsh.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtorjakbat.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtvqrtvrgh.html

[E09] 去除所有空白字符
来源：http://dali.kuanghao11.cn/Article/details/gteaawrukw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gtwspnqnof.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gtqmrvqwgn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gttigkzpmc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gtoyffskok.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xinyue.icu/Article/details/gtaopixcyv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gtlwfrkyee.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtehdralyz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtkbllifbt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gtbcydkrfn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtyexoybrl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gtfqciyhll.html

JS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtytzyzplh.html

TS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtwsidfenh.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtobndueci.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtznnsmjlw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtmfusmbmq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pengpengdd.cyou/Article/details/gtnjnseewt.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gtwjonnwah.html

Py:   s[::-1]
来源：http://dali.ydzc1.top/Article/details/gtslhshapt.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gtjfyjzwgk.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtqifzflqv.html

TS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtowsjzlcn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtopqximfa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cheryme.top/Article/details/gtosxxduoa.html

Ruby: s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtgjtunqgf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtvauvntyj.html

[E12] 统计某字符出现次数
来源：http://dali.xziqi.cn/Article/details/gtyaceebxw.html

Py:   s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtezvsgljf.html

PHP:  substr_count($s, "a");
来源：http://dali.zhoulong.xyz/Article/details/gthvzniyhn.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtvfccbsss.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtmccwyrge.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgufenzy.top/Article/details/gthjkhsryt.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gtaikleyzo.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtjhyuopbn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhoulong.xyz/Article/details/gtmfvibcjh.html

[E13] 逐字符遍历
来源：http://dali.jianghu66.top/Article/details/gtpyugosox.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gtslqrerjz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jyoumei.cn/Article/details/gtsajadrve.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtzjtesevj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusyvfntp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xinyue.icu/Article/details/gtagowvdcx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gtcqftrmwn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefekvpsw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.redwolf501.top/Article/details/gtjapweadr.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gtfgwqqjqm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tanke756.top/Article/details/gtamwgmfau.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gtwvvbgext.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gtyggbncqd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cucudq.cn/Article/details/gtigbfsvly.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtldzbjtrd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gtsmpxcjql.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daria6918.cn/Article/details/gtgmvwdevf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fengsongda.top/Article/details/gtakrjoksf.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gtaogvxahq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hywenlv.cn/Article/details/gtjshhizxv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtwkxmonce.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtwwvqechj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtnuzoehgi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gteaiatidy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gtqjuqbszt.html


<!-- 参考信息 -->