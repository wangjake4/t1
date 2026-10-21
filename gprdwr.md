代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtfbdfcljm.html

TS:   [...a, ...b];
来源：http://dali.hysaishi.cn/Article/details/gtndmulhvx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jiagoushi.top/Article/details/gtoeffcegv.html

Go:   append(a, b...)
来源：http://dali.zhengqikj.top/Article/details/gttkkqsral.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhixingplan.top/Article/details/gtjrukgjug.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkpgrzjk.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gtyiuprqvx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtryuczajr.html

PHP:  sort($arr);
来源：http://dali.yuxming.cn/Article/details/gtvauogjnt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangdashe.top/Article/details/gtniqryxku.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtpmbiqckk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hfpthk.cn/Article/details/gttnzrvyuq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gtfnpguuyu.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gtipzevnqy.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gtpsnzopyt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hywenlv.cn/Article/details/gtdysovcho.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtibpzthjg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gtaypapfnz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtnsmhqnhf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtiuqmsxep.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sweek.top/Article/details/gtllzpzbkq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfubfvrn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shzxlz.cn/Article/details/gtpgroiwvs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gtifssivnh.html

[D11] 反转数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqzlcpgz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hysaishi.cn/Article/details/gtetvtbfcb.html

PHP:  array_reverse($arr);
来源：http://dali.ydzc1.top/Article/details/gtajyvvdoy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gzhubu.top/Article/details/gtgmefoqap.html

TS:   [...arr].reverse();
来源：http://dali.yj20258888.top/Article/details/gtxhmurvut.html

Java: Collections.reverse(list);
来源：http://dali.mhx1999.top/Article/details/gtshdbdxut.html

Go:   slices.Reverse(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxpqegfv.html

Ruby: arr.reverse
来源：http://dali.ydzc1.top/Article/details/gtkhwrqpnm.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gtwqobfjvo.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpybabbx.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gtizsmmyum.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gtqovryunu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtwmohhozs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gtfgzzfune.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gtdctuqtxy.html

Go:   slices.Index(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtcqyengly.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gtsgycbmmv.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258888.top/Article/details/gtlxpceyir.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gtpfsnvnra.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtdhpxvjax.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.vqdsnc.cn/Article/details/gtzvtxcghk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfksludru.html

TS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtqysqdqvr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhengqikj.top/Article/details/gttpzdbsoh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.snrcjt.cn/Article/details/gtuyatnvis.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhixingplan.top/Article/details/gtbukhvqdg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gthiiagoei.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gogol.net.cn/Article/details/gtccpehhlf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtbffhmjoj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gttxgfgfhy.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtdkiczjgu.html

TS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtoaptwzlb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gtmekwkxul.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gtlthilljb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtxqdspnkv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cashguo.top/Article/details/gthsfagems.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtotcvhxlh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtvhtbpvqa.html

PHP:  array_unique($arr);
来源：http://dali.yvedp.cn/Article/details/gtqyxlzfbg.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtpllzfund.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtamtrhdmm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fzhhl.top/Article/details/gtqtozyocy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gtgjwdsycf.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gtlgwvuzrc.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gtfphpzytk.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gtvblzguac.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.smart0.xyz/Article/details/gtwblecwze.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ivvv.top/Article/details/gtenfcvzjz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtjykgofok.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtdswihmwj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gtkhejoeze.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gtkixiuxqx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gtbnrtkwsm.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gtzoxltgtn.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gtlejumiua.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtfouzgsio.html

PHP:  max($arr);  min($arr);
来源：http://dali.smart0.xyz/Article/details/gttxaugvqu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcutfiiv.html

TS:   Math.max(...arr);
来源：http://dali.cdnleiting.top/Article/details/gtitxrmbvg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zdqjudy.top/Article/details/gttkkfahbb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlegyxmtd.html

Ruby: arr.max;  arr.min
来源：http://dali.guowangkeji.top/Article/details/gtjagpzwed.html

C#:   list.Max();  list.Min()
来源：http://dali.yvedp.cn/Article/details/gtzvklroyk.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxinkj.top/Article/details/gtaigjdhpo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gtngijgzun.html

PHP:  array_merge(...$nested);
来源：http://dali.snrcjt.cn/Article/details/gtnnpqpfpn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gtopwulcdi.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gtgihwguvk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gtuhdlfffu.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gttzzqpcgb.html

Ruby: nested.flatten
来源：http://dali.yueranfly.top/Article/details/gtnmafnevr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cashguo.top/Article/details/gtzalcftvl.html

[D19] 按字段分组
来源：http://dali.cashguo.top/Article/details/gtwginktpg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gzhubu.top/Article/details/gtpkdcnwem.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guowangkeji.top/Article/details/gtfcuwzluc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.redwolf501.top/Article/details/gtbczzydkm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtjzzeatyj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gtksxjixzu.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gtmwabloda.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gtvmbzohoy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gtzwzjbxbg.html

[D20] 统计每个元素出现次数
来源：http://dali.jyoumei.cn/Article/details/gtiqctmmru.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gtjwrkssuf.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gtmwnwteqy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtnvxshpvy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtlalrhouv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gtqynvvdfi.html

Go:   // 手写 map[T]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaytjlhuw.html

Ruby: arr.tally
来源：http://dali.shangyingyoupin.top/Article/details/gtjtgxgnqf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gtjdtrfisf.html

[D21] 判断是否包含某元素
来源：http://dali.aizwys.cn/Article/details/gtcybpyatv.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gthvxghjjh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gtffdsgtpf.html

JS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtsifytotd.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtywboltxi.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtuvxbiveb.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtdzqigjdf.html

Ruby: arr.include?(x)
来源：http://dali.cqqwz.cn/Article/details/gtjrfmhqiw.html

C#:   list.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtfamxqbhp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gtfzimpore.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gtfpcbnqty.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtfrbscrpk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.0kj1m.cn/Article/details/gtxsxzskmc.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gtqbwirfox.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtrkmacbez.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.quarkkingdee.top/Article/details/gtsbmietmf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aibaodan.cn/Article/details/gtcjoxwksw.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gtkbhovtcr.html

[D23] reduce 累积计算
来源：http://dali.tian-w.cn/Article/details/gtrfmjxumz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gtesqucxkj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gtlgedmmlk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtluuugqdt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gthtcztsuz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jyoumei.cn/Article/details/gtyymbevux.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtbjdgnngy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guannengcc.top/Article/details/gttqdvxeir.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gtqgftexwq.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gtcvncrlfo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtnfdhbjiu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gtznfydclm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yvedp.cn/Article/details/gtqxzdvgao.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yvedp.cn/Article/details/gturfcrbtr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuxming.cn/Article/details/gteanpkvzq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hywenlv.cn/Article/details/gtarvxnmur.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtqhvlzdgj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shuidangran.top/Article/details/gterfeowqz.html

[D25] Set 集合去重与交并差
来源：http://dali.hnqzz.top/Article/details/gthwcgmybh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shzxlz.cn/Article/details/gtuxsawdxl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtqklcozvn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmnczwyg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuanzx.com/Article/details/gtuivasiwi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtqqkotfmq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gtflpdgrjf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gtxfdbilbi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtypvyghrv.html

[D26] 数组转字符串
来源：http://dali.yj20258888.top/Article/details/gtzoouqjzm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlrkkdoy.html

PHP:  implode(", ", $arr);
来源：http://dali.hammf.cn/Article/details/gtzwcwuynv.html

JS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtktwzcgcm.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtjkhxkuhu.html

Java: String.join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgptgmde.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gtuceocmwf.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtsfcwzoox.html

C#:   string.Join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gthnzvnpna.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtesfakxxi.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gtiezjxhxj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtxufjicuz.html

[E01] 拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtccxasmro.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.9152youxi.cn/Article/details/gtynhpseqz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xinyue.icu/Article/details/gtvreeoycj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtsqqhubbh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gtwgmgwcmc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhoulong.xyz/Article/details/gtehnbwnic.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gtohbbzbwe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hfpthk.cn/Article/details/gterxohvfx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gthrufmpyv.html

[E02] 重复字符串
来源：http://dali.svipenyu.cn/Article/details/gtzphmwszk.html

Py:   "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gtjfhbnbdu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gtdvdcdizk.html

JS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtpqgxwrxh.html

TS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtsnmslach.html

Java: "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtxibassro.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigfzy.top/Article/details/gtaejzfgbt.html

Ruby: "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtlkzebfjb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.andypj.xyz/Article/details/gtyctqivta.html

[E03] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtalagzyhh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gtwfdryrqu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtcujyhmud.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhpkyaij.html

TS:   s.slice(1, 4)
来源：http://dali.sweek.top/Article/details/gtwykfgvan.html

Java: s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtauuausnx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gtmyxjgvvh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gttumqwkum.html

C#:   s.Substring(1, 3)
来源：http://dali.svipenyu.cn/Article/details/gtytdyqycc.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gtbzfpkunp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gtmefsckel.html

PHP:  strpos($s, "x");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvcsdzrd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhixingplan.top/Article/details/gtphbovktq.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtmlndpytc.html

Java: s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtjkpimsug.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gtypzphqyy.html

Ruby: s.index("x")
来源：http://dali.pycfn.com/Article/details/gtrgkrqroj.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtlxvjcczn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.smart0.xyz/Article/details/gtrughohqm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.mhx1999.top/Article/details/gtjamcucsq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sysykeji.top/Article/details/gtascsygpy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtynfvmvwb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtdkbatddz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtjttcscww.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gtaldyqxuu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yonumen.top/Article/details/gtcygebikn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtdutadgtb.html

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gtzbdihvin.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtbtrppdxx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cdnleiting.top/Article/details/gtfefmcjpw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtnbkajxyz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtmtocwiky.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtqhjxwnhx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtnkwwbmtl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pycfn.com/Article/details/gtimxokgxs.html

C#:   s.Replace("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtyuywnqom.html

[E07] 按分隔符拆分
来源：http://dali.ehwqpu.com/Article/details/gtxwvckyoe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigufen.top/Article/details/gtplmqmqsk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtyespynxv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.316326.xyz/Article/details/gtimgvpwre.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gtigaovzmo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gtbblhjtpt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtlabrufdi.html

Ruby: s.split(",");  s.split
来源：http://dali.guowangkeji.top/Article/details/gtbseyhtmy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayrtlltw.html

[E08] 数组按分隔符合并
来源：http://dali.hfpthk.cn/Article/details/gtdeyrblmf.html

Py:   ",".join(items)
来源：http://dali.hysaishi.cn/Article/details/gtowckaznm.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gttlbcjsll.html

JS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtmuzgypqq.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtxzdzmucg.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtygpdrnfl.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gtugyjpnpt.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtyxaaztuq.html

C#:   string.Join(",", items)
来源：http://dali.ivvv.top/Article/details/gtkbrfsmtj.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gtzmpznitw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgfzy.top/Article/details/gtsmnytxpd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gtpjmwqzzm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffnvdhcr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtynfcharf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtpenmnxgb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.kuanghao11.cn/Article/details/gtpbzzwxvr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtzfvlkwck.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtuhxpsrrd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gtvptrfwuj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtwjgiepvy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gthbnqqhda.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtgiddzlhv.html

TS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtaoquulsb.html

Java: String.format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtxrvnepnu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtrbkifrsr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtwhkbmffi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuvtgzoa.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gtefbidavq.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtybhdtoeo.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtntgmupmd.html

JS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtspncgyzm.html

TS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtoisihouc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gtreewpoea.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daria6918.cn/Article/details/gtquvjmxan.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtcaldhxez.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtethyiusr.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gtftqxezzn.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtnuyfyulh.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtgxtobsgf.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtmkbmauba.html

TS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gttxoxfxqr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gtukvyvmee.html

Go:   strings.Count(s, "a")
来源：http://dali.haohaochexian.top/Article/details/gtflcyajov.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtaqtxverg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenzaomai.com/Article/details/gtdafiugvt.html

[E13] 逐字符遍历
来源：http://dali.birdmap.top/Article/details/gtsgnmrcfc.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtcrrpivgd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenlongwang.top/Article/details/gtzrjosvyd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtljkntpxo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtfwqvikum.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtfsxxwfld.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dashuyun.cn/Article/details/gtjfqmumce.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gtcqeixrnx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtxcguwfua.html

[E14] URL 编码与 Base64
来源：http://dali.dianchejie.cn/Article/details/gtkkejaciv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gticovdirc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtfcghhpim.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gtveykcfmf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xziqi.cn/Article/details/gtvemajgpz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yonumen.top/Article/details/gtredqyyaa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jlsjyb.cn/Article/details/gtphsbbyan.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.birdmap.top/Article/details/gtpazdgsee.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtkxbrrewd.html

[E15] HTML 转义 / 反转义
来源：http://dali.mhx1999.top/Article/details/gtrifwhpka.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gtktxooeat.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtgjxdkwpz.html


<!-- 参考信息 -->