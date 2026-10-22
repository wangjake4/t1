代发 wailian999

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gttgkvjbrc.html

PHP:  count($arr);
来源：http://dali.dashuyun.cn/Article/details/gtawwgsmdk.html

JS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gtkeykclti.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtcoobrzdv.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gtpbmiwxni.html

Go:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtvkstehqt.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtntjumaom.html

C#:   list.Count;
来源：http://dali.chenlongwang.top/Article/details/gtmbitcldt.html

[D07] 切片 / 取子数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsgupvdj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gtydxbefti.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sxryk.cn/Article/details/gtcqflliel.html

JS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gttsslgamr.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtanhlbhjd.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtlutgvbeu.html

Go:   arr[1:4]
来源：http://dali.ydzc1.top/Article/details/gtocmawdsf.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtrtyqdgff.html

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gthkqipspd.html

[D08] 合并两个数组
来源：http://dali.havefunace.top/Article/details/gtexocklcr.html

Py:   a + b;  a.extend(b)
来源：http://dali.xylfe.cn/Article/details/gtmenbokpp.html

PHP:  array_merge($a, $b);
来源：http://dali.xuanzx.com/Article/details/gtklvffqah.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gtdrrcirtx.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gtnnrnwvdy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gtgwzggalf.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gtixhzgrib.html

Ruby: a + b;  a.concat(b)
来源：http://dali.feifeiyinyue.top/Article/details/gttikxxagy.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtmsujnnyq.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gtbxefquew.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtbylnrwla.html

PHP:  sort($arr);
来源：http://dali.aizwys.cn/Article/details/gtobgzntqk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shzxlz.cn/Article/details/gtufncaxcy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gtzutyjchb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gogol.net.cn/Article/details/gtpnopmaws.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gtfujlokvq.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gtckcxgifh.html

C#:   list.Sort();
来源：http://dali.feifeiyinyue.top/Article/details/gtglxoxjxv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gteykscrsv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.9152youxi.cn/Article/details/gtrmnwggbw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwrozzqe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflfmbtkn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtfhgrrkwx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gtdfuvimym.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gthquqqmwt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xziqi.cn/Article/details/gtfohhlluw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258.top/Article/details/gtzppveqlp.html

[D11] 反转数组
来源：http://dali.pengpengdd.cyou/Article/details/gthhvmjoow.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gtvhqqohim.html

PHP:  array_reverse($arr);
来源：http://dali.redwolf501.top/Article/details/gtrjhxytyg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuanzx.com/Article/details/gteoimnjgg.html

TS:   [...arr].reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrigqqyn.html

Java: Collections.reverse(list);
来源：http://dali.chenzaomai.com/Article/details/gtngqyyxvp.html

Go:   slices.Reverse(arr)
来源：http://dali.316326.xyz/Article/details/gttmsomekx.html

Ruby: arr.reverse
来源：http://dali.yangfankeji.com/Article/details/gtjnbfjxqq.html

C#:   list.Reverse();
来源：http://dali.fzhhl.top/Article/details/gtkokcezgi.html

[D12] 查找元素下标
来源：http://dali.jianghu66.top/Article/details/gtvuroylat.html

Py:   arr.index(x);  x in arr
来源：http://dali.guannengcc.top/Article/details/gtzoodybwo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtisryaivw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtvxklkqqt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtjmumecnp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guowangkeji.top/Article/details/gtgdugnmtn.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtrbfvfwap.html

Ruby: arr.index(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtrfwqqtcb.html

C#:   list.IndexOf(x);
来源：http://dali.cashguo.top/Article/details/gtgkgvejfe.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gtuseqblwn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zdqjudy.top/Article/details/gtnjbrnwiq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zdqjudy.top/Article/details/gtxxrhvxtf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtsharsfds.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gtfwflycnu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvwxsxkm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sweek.top/Article/details/gtivamuwgv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.smart0.xyz/Article/details/gtkuafvunz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwmdlpsb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sxryk.cn/Article/details/gtfpzblxpz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fengsongda.top/Article/details/gtjortbrrf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuytvbvs.html

JS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtxvrccupr.html

TS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gtvkutmolj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gtrlkrvvui.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtnjbuetlr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.havefunace.top/Article/details/gtehabeimg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cashguo.top/Article/details/gtwdzuisyh.html

[D15] 去重
来源：http://dali.yj20258888.top/Article/details/gtvohzsrvd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtadtdbfff.html

PHP:  array_unique($arr);
来源：http://dali.havefunace.top/Article/details/gtpununlpx.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtikgzzxql.html

TS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtumrhicqa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guannengcc.top/Article/details/gtqloojebs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gteyymxidf.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gtveecpbtw.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gtbupoouvo.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gtykysrzoo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtagtozwdr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gzhubu.top/Article/details/gtfieglglw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtadwwjmgz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtuqqfjlbs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtcwuefklk.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangtech.top/Article/details/gtqimansgc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gtkmjjgoxh.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtqgdljgtg.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gtfmwdshxq.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtpnguedet.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtwgunwyeh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtybfnxpbz.html

TS:   Math.max(...arr);
来源：http://dali.aibaodan.cn/Article/details/gtobmucxcg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gtaihvzltk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.birdmap.top/Article/details/gtgulecnbe.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gtkitrqqjw.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gtwlxiiwiu.html

[D18] 扁平化嵌套数组
来源：http://dali.redwolf501.top/Article/details/gtebfdhdbw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuxming.cn/Article/details/gtyldtuhsa.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gtdbmtmzwd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gtkvkjfchn.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gtbuerklqh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gtmqzijlfa.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtoshlrqlq.html

Ruby: nested.flatten
来源：http://dali.fengsongda.top/Article/details/gttzayxxkj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtatpijsmx.html

[D19] 按字段分组
来源：http://dali.yanxiufei.cn/Article/details/gtsxckfbva.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.smart0.xyz/Article/details/gtpdavykah.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.meibo888.top/Article/details/gtjervbxnp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zycfv.cn/Article/details/gtpaafdyqh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtucsefkfy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fengsongda.top/Article/details/gtuedvpyli.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gtdsidvrcl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyhdicab.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gtehlbvsmq.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gtfnaiftvk.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gtivpvrvoc.html

PHP:  array_count_values($arr);
来源：http://dali.snrcjt.cn/Article/details/gtjqiuugja.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtzmzhuljr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gtopjxtbrv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hammf.cn/Article/details/gtxjmppxjb.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gtkekdberx.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gtqaplxnkr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gtjduvwawp.html

[D21] 判断是否包含某元素
来源：http://dali.cdnleiting.top/Article/details/gtivlildia.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtyazhbpos.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgufenzy.top/Article/details/gtzigareqk.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtefxijbdh.html

TS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtgibxscvf.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gttlrmicup.html

Go:   slices.Contains(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtdapajtko.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gttzrfsvew.html

C#:   list.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtkjuhxgsa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gtvuorbtee.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gtdqoawlqv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gtglfvswje.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gtszdpfxpj.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gtaekcmckp.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gtdnfaacad.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sysykeji.top/Article/details/gtmlejhhsv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gtoverehkz.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gtcxnxyhko.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gtkxcvunzw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.iojbl.cn/Article/details/gtqpwdwkqe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gtpwlbphej.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtzgdeebxt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtktefugme.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gthchwvfrm.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gtfhhmuavp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbvnhuyv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gtreuzieba.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gtvnhetmzx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtwpaiucoh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guannengcc.top/Article/details/gtlxexfpzn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtthxmqhqq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtghtaqobs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gtziwtczao.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hywenlv.cn/Article/details/gtfjytjtaq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hysaishi.cn/Article/details/gtcsriilxj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.haohaochexian.top/Article/details/gtixsxpktf.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gtkgnuselz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtqmlsylok.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtwxvdykhm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cheryme.top/Article/details/gtkojhbppe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gtlgiqsetd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sweek.top/Article/details/gtmgapsvqz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gogol.net.cn/Article/details/gtfrvtqame.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.bjfxy.top/Article/details/gtcspjzsqm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtugicwclw.html

[D26] 数组转字符串
来源：http://dali.bjfxy.top/Article/details/gturxkfdzs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtmvdsqxnq.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gtxwexhziq.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtaalhdqos.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtkadkppat.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtojubsifl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtmciwyetk.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtbkppoafz.html

C#:   string.Join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gtahhqrogg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtknngmuzv.html

E. 字符串处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxaiwejl.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwxouwwen.html

[E01] 拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtdyzotvvm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sxryk.cn/Article/details/gtoxxaebod.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ppjwa.cn/Article/details/gtrqryagdt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtjdllnjqo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtvofnkfnh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dashuyun.cn/Article/details/gtrpgchiax.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.iojbl.cn/Article/details/gtauklhsaf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gtzxmtoswo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gtbzyozrte.html

[E02] 重复字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtjzhcjixo.html

Py:   "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtytizizsh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gtkmvijrpy.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtqewldlwd.html

TS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtkxxuvtus.html

Java: "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtyeesamzb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gtwakpfkye.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtcsezxduk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gtksxwlwyo.html

[E03] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtfhwxbrne.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sufxvd.cn/Article/details/gtuvnzfpdz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtmtgsornq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtcwypmvbi.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtwabueumk.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtoyzxfzsy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflhymdub.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxbntjki.html

C#:   s.Substring(1, 3)
来源：http://dali.yj202588.top/Article/details/gtywahktvg.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gtvbqhwolg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtkgrywsab.html

PHP:  strpos($s, "x");
来源：http://dali.hysaishi.cn/Article/details/gtsamzkhit.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gtafxlmghe.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtliojkibs.html

Java: s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtihhkwdtu.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gttoxlwwvv.html

Ruby: s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudujbbgv.html

C#:   s.IndexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtpzwznfbw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxinkj.top/Article/details/gtaivspkth.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yongpay.top/Article/details/gteincddym.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gtavdazukh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gttivwodlj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fengsongda.top/Article/details/gtsaiuxjqj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtocfdbwbh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gtebzeljbr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pycfn.com/Article/details/gtmuyixhki.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gthxbjzqzp.html

[E06] 替换子串
来源：http://dali.hnqzz.top/Article/details/gtefprrote.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtbacdbgdu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ivvv.top/Article/details/gtxjrxxtml.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtxuscudya.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtgbfeqvvs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtryavqjbq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtatptohlc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtaybucygy.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtlsfamvaw.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtgppopxgk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guowangkeji.top/Article/details/gtqhqacmuf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtsxsdieqh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gtzpusuwqm.html

TS:   s.split(",")
来源：http://dali.hammf.cn/Article/details/gtwdjejhzb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenzaomai.com/Article/details/gtrlzmsqcx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daxiang520.top/Article/details/gtwooggsuj.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gtqbfgyjiq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjeewevbf.html

[E08] 数组按分隔符合并
来源：http://dali.aibaodan.cn/Article/details/gtwzpecqqa.html

Py:   ",".join(items)
来源：http://dali.cdnleiting.top/Article/details/gtgooqhjbc.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gtlelgfvia.html

JS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtiqetyrrh.html

TS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtzjlxwcvq.html

Java: String.join(",", items)
来源：http://dali.redwolf501.top/Article/details/gtxfyvdvpv.html

Go:   strings.Join(items, ",")
来源：http://dali.dianchejie.cn/Article/details/gtqmhvndgq.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtkfpnabfd.html

C#:   string.Join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gttwpbnrun.html

[E09] 去除所有空白字符
来源：http://dali.chenjidiqi.icu/Article/details/gttmzprhmz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxinkj.top/Article/details/gtpeazruma.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ivvv.top/Article/details/gtzvryrzth.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtvooqccqw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gtlkozltbw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtklnsdaqz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yonumen.top/Article/details/gtwxjrkggh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gtirqsufck.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtodjufxkt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gtwvxogidc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gthgowwbcc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gtshdttmij.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtqdjgocta.html

TS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gttheujjzi.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtqkmdjwtw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtwtdpetxx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtdadwsrwh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gtsckleyoj.html

[E11] 反转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtuawrdnto.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtemgddtpu.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtufhkehta.html

JS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtsjsoytae.html

TS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtswzdlkni.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtoypijlkg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtutkhflaq.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtytvgvxbl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtmwdlzifi.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtmmpdcmof.html

Py:   s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwhlduxd.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gtskyidafg.html

JS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtjryvebhf.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtnvbdevwj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gtjhhyosfn.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gtuodzpysk.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtwwkaubij.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daxiang520.top/Article/details/gtcztkbcgt.html

[E13] 逐字符遍历
来源：http://dali.smart0.xyz/Article/details/gtuyxfmzgo.html


<!-- 参考信息 -->