代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gtgsdvrvtb.html

TS:   [...a, ...b];
来源：http://dali.zycfv.cn/Article/details/gtvlwwteul.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gtlrzmxtsj.html

Go:   append(a, b...)
来源：http://dali.gotoacloud.top/Article/details/gtddbdqaxg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fengsongda.top/Article/details/gtfivtuzxz.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gteeuupcxf.html

[D09] 排序（升序）
来源：http://dali.xinyue.icu/Article/details/gtgiddabal.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gtynvqjttd.html

PHP:  sort($arr);
来源：http://dali.tian-w.cn/Article/details/gtndnmnrle.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gtaxwqxabk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gtkshzhcly.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.redwolf501.top/Article/details/gtcqcvgudz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtrpnoznhx.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtmfdumbpq.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gtmzkcuwnz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gthheoigki.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tanke756.top/Article/details/gtjatxybyw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtkxjvohba.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtqdaqpckn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gtssoucmdi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinghuilouyu.cn/Article/details/gttbkprpfq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yvedp.cn/Article/details/gtkbmwwthj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.vqdsnc.cn/Article/details/gtkzbihomc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dianchejie.cn/Article/details/gtvirgkuux.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gtcfugattq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gtalwdeoor.html

PHP:  array_reverse($arr);
来源：http://dali.fengsongda.top/Article/details/gtscawirnz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gtektcjjfa.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtjjwuglhi.html

Java: Collections.reverse(list);
来源：http://dali.sweek.top/Article/details/gtspjondjw.html

Go:   slices.Reverse(arr)
来源：http://dali.redwolf501.top/Article/details/gtviejiekf.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhxtiopb.html

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gttglntxwd.html

[D12] 查找元素下标
来源：http://dali.xinyue.icu/Article/details/gtnmvdrujo.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gtavjggenz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtxlhzxbvo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gtaelwzdko.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtujybdnhq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gtuzyhnxke.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtilsxjejj.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gtpwvhcypz.html

C#:   list.IndexOf(x);
来源：http://dali.jlsjyb.cn/Article/details/gtnychqbmo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yueranfly.top/Article/details/gtzamlvysl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtmzajotec.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gtcenhmbea.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtfrxsltum.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtlawjtotm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258888.top/Article/details/gtrkdnpeio.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gtpbyshvcn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgpwgetq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtdxcsroju.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gteazltwrs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gtruardsus.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gtqvjvumnd.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtmbmpouws.html

TS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtggebytnc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gteynrcdpe.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtifmgxwrs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtowcinybq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gtrjsyvyyq.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gtrmxwmfot.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtogziarbs.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbbawpce.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqorponx.html

TS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtwnnqeiuy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchkdvitz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gtliyjgraq.html

Ruby: arr.uniq
来源：http://dali.gotoacloud.top/Article/details/gtaiqoxmgt.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtybzrzmwx.html

[D16] 求和与平均值
来源：http://dali.zhoulong.xyz/Article/details/gtpnzgdeqf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtygireoby.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gtyxrkming.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtlfhsopcw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gtatvlyjla.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gogol.net.cn/Article/details/gtvvnmwbno.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtsvpnmkfu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gtdogbmhid.html

C#:   list.Sum();  list.Average()
来源：http://dali.quarkkingdee.top/Article/details/gtbpxmyuby.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gtyjdfcjfd.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gtugkaixuk.html

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gtbrxzezse.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gtqwbnvqeq.html

TS:   Math.max(...arr);
来源：http://dali.yanxiufei.cn/Article/details/gtsjxexcxb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gtdlnvkhhq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhengqikj.top/Article/details/gtnxdshpoa.html

Ruby: arr.max;  arr.min
来源：http://dali.guowangkeji.top/Article/details/gtmbdrevwh.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigufen.top/Article/details/gtaqhocobx.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gtjdktufju.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cashguo.top/Article/details/gtemtlrxqv.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gtmxwxkpnf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sufxvd.cn/Article/details/gtfligltrt.html

TS:   nested.flat();
来源：http://dali.cdnleiting.top/Article/details/gtxudcorqo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gtshoajzju.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gtohgsfhus.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gtokobdugb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gtewlaioko.html

[D19] 按字段分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtinwebxsl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gtsfevwzzs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gtnukiqbhx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pengpengdd.cyou/Article/details/gtcpwxoedc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzvrmexf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gtioialstz.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gtgxetdsve.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnqzz.top/Article/details/gtnckgfcad.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuetiantiany.cn/Article/details/gtyighiwwb.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gtwgjavqcq.html

Py:   Counter(arr)
来源：http://dali.ehwqpu.com/Article/details/gtvrozhnjg.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gtcdteshbs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gtunysyqqf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtkzfwmwzn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gtmoostepd.html

Go:   // 手写 map[T]int
来源：http://dali.iojbl.cn/Article/details/gtedraukky.html

Ruby: arr.tally
来源：http://dali.xuetiantiany.cn/Article/details/gthjjyvcgt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gtizoosffg.html

[D21] 判断是否包含某元素
来源：http://dali.c1oappe.top/Article/details/gtsssuegde.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gtidppvoor.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gtgqeysbvp.html

JS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtgkpavklw.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtglcqkgff.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gtvbbwmoap.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtytjjalvc.html

Ruby: arr.include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtkcdtmynz.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtdmjeobox.html

[D22] 复制数组（避免共享引用）
来源：http://dali.andypj.xyz/Article/details/gtlpyipddc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhixingplan.top/Article/details/gtrbncezql.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.feifeiyinyue.top/Article/details/gtzwokccci.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gtupsocher.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gtzggucxul.html

Java: new ArrayList<>(list);
来源：http://dali.yvedp.cn/Article/details/gthvyjvwwq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sufxvd.cn/Article/details/gtecloyrjc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sxryk.cn/Article/details/gtgynigqrx.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtnmgcmxor.html

[D23] reduce 累积计算
来源：http://dali.fzhhl.top/Article/details/gtmqvbsuep.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shuidangran.top/Article/details/gtabnofgle.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuanzx.com/Article/details/gtgdmsvxdu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gtmoqzmzei.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gterdlhytj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gtnawzlvnn.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gthbjrmwxj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhiwuduotai.top/Article/details/gtkvqqumfj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gtrhiqrckp.html

[D24] 字典 / Map 基本操作
来源：http://dali.yangfankeji.com/Article/details/gtaxflvocw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gtsrbwephp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gzhubu.top/Article/details/gtwqopxdwf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxinkj.top/Article/details/gtqmllbttr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtotypxffe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gttksgmhdf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gtihdmbwye.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gtubxjfclv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.quarkkingdee.top/Article/details/gtknqajtze.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gtckupfrfs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.smart0.xyz/Article/details/gtgvqbmuui.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gtayaumxji.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuanzx.com/Article/details/gtcfmcsood.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xylfe.cn/Article/details/gtxvahibzn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtwcayfagt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtsbygvydw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigfzy.top/Article/details/gtzwrfxvzq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtylnmmvck.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gtlcjiusoa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxinkj.top/Article/details/gtelxafvvq.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtfmlzosvc.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifvtdces.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtbivklthu.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gtjvfhtfba.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shuidangran.top/Article/details/gtjjcqpvjq.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtrytfjhbu.html

C#:   string.Join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukijxasr.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtoukijjjy.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gtqhlprhjx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrsyolgxr.html

[E01] 拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtasmkivuf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrpbjgdi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhengqikj.top/Article/details/gtdzdrjtwf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtcwqcjxat.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtldsgzkcx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.iojbl.cn/Article/details/gtsrqxgzpl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gtkvcywurr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gtcooioyla.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtdyrqvxus.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gtvqicgsrs.html

Py:   "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gteojjwtdn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fengsongda.top/Article/details/gtqiswmcxu.html

JS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtpvyddsro.html

TS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtysmnapzl.html

Java: "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtuprrnked.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnxiangtu.top/Article/details/gtgkjvizvf.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtlbbubawl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjojjqpw.html

[E03] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gttuiphfhp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fengsongda.top/Article/details/gtkgtvllew.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtimilowtn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtjbvrzawv.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtlvztunpr.html

Java: s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtopwszorj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gtlcpjzxyw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gtjcmeukga.html

C#:   s.Substring(1, 3)
来源：http://dali.chenzaomai.com/Article/details/gtycfshnqc.html

[E04] 查找子串位置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlkeenkk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtjfqqquwd.html

PHP:  strpos($s, "x");
来源：http://dali.shuidangran.top/Article/details/gtrvqwmqid.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.smart0.xyz/Article/details/gtsuiadanr.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gteeexxonl.html

Java: s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtjeflgnnl.html

Go:   strings.Index(s, "x")
来源：http://dali.yuxming.cn/Article/details/gtqscunhwl.html

Ruby: s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtkfrlumiz.html

C#:   s.IndexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtzxuoddeb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gtwiehzunb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gtdlpfgtnl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xinyue.icu/Article/details/gtcqgfnmpx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtfmysubdl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hammf.cn/Article/details/gtgylqceed.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtzkxpkqzj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ppjwa.cn/Article/details/gtrmxgbblk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gtqyddsmiu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtxllvcbyj.html

[E06] 替换子串
来源：http://dali.tian-w.cn/Article/details/gtsrwtuofd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtxtkavwfd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.vqdsnc.cn/Article/details/gtuanaysph.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtnisvqcvh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtvpvbfknv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtobjvkufd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtvltyrfvn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtdxwgrrsf.html

C#:   s.Replace("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtnugeceem.html

[E07] 按分隔符拆分
来源：http://dali.ivvv.top/Article/details/gtxyygkctw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zdqjudy.top/Article/details/gtbuncgvno.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtvmuvjyvd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacfhwzhk.html

TS:   s.split(",")
来源：http://dali.zycfv.cn/Article/details/gtgppxujsu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gtocaogfgh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gtumppnule.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gtvbwgezbx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gtbrsinhpx.html

[E08] 数组按分隔符合并
来源：http://dali.fengsongda.top/Article/details/gtsnusvria.html

Py:   ",".join(items)
来源：http://dali.chenjidiqi.icu/Article/details/gtftmtctrp.html

PHP:  implode(",", $items);
来源：http://dali.xylfe.cn/Article/details/gtgllpyixk.html

JS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtlgwlzoql.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtllsglyqu.html

Java: String.join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtgctgnpnu.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocsgkugh.html

Ruby: items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtsomcumdb.html

C#:   string.Join(",", items)
来源：http://dali.yueranfly.top/Article/details/gtwqofenvg.html

[E09] 去除所有空白字符
来源：http://dali.yuanzhike.top/Article/details/gthskeyogc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gthwrupybe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gtcflgfhuc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtfqijsqyt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtbgaxtcjg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yvedp.cn/Article/details/gthzkfsakx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznsichtk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gtanlhhdcl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtpydsykas.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gtsfokeldc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtmbwanphc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gtgjrktmkj.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gthfqzxlzo.html

TS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxinqkxhk.html

Java: String.format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtszzlumkx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtcisbefvj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtftzsrigq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yanxiufei.cn/Article/details/gtccwblshm.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gtpwfyhiwd.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtvhvdiksm.html

PHP:  strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtxmdzgmdb.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtmdzbgnaz.html

TS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtvbujyqrr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gtspvixtkp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtrklnqbxy.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtocaekulx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtnthhinig.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gtghyolksc.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtuxatgvgj.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gtebbdtzrr.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxgvtled.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtwxzojtwd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sweek.top/Article/details/gteyrdpkzr.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gtddeeutcy.html

Ruby: s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtsaixvvrw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhoulong.xyz/Article/details/gtidtrttqe.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gthdrzpmwx.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gtwzllufqw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmrgcxmbo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtcfkmqmkx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gterbllmsn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gtmrdahyll.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhgjbrpm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gtmwlqlpsa.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtmedfsnfk.html

[E14] URL 编码与 Base64
来源：http://dali.cheryme.top/Article/details/gtxctxshew.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gtsqteuhuf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtskasbmpc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gtjlbnsmao.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gotoacloud.top/Article/details/gtsobvcdic.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sysykeji.top/Article/details/gtdntruvgh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxmcsvww.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gtidgtedur.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gthvlulahu.html

[E15] HTML 转义 / 反转义
来源：http://dali.jyoumei.cn/Article/details/gtyobkrqip.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gtbnxkdgju.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gtccbrhkdv.html


<!-- 参考信息 -->