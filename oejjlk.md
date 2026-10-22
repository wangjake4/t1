代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtyaowegkc.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gtgzbglziz.html

Py:   a + b;  a.extend(b)
来源：http://dali.yongpay.top/Article/details/gtqsgvxzpu.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gtltjlbseo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gtuprgcnmb.html

TS:   [...a, ...b];
来源：http://dali.sweek.top/Article/details/gtbnfaicqk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gtvtrvexrz.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gtcynmeoqk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pycfn.com/Article/details/gtjjgncisf.html

C#:   a.Concat(b).ToList()
来源：http://dali.iojbl.cn/Article/details/gtuwxzbzjo.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gtdpxmbdqu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gtaphhcllv.html

PHP:  sort($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtzyusgibb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xylfe.cn/Article/details/gtdebfxkdt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tian-w.cn/Article/details/gtojdumucp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gtnizsmwxg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtvwdtsmlx.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gtawdrytza.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gttfwbsubm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gthzkeuuwd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gtqjktwxqq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gtmddqitxf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdrdkupw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtptyczvrx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dashuyun.cn/Article/details/gtrvpkyjpu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.redwolf501.top/Article/details/gttovbbzfl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigufen.top/Article/details/gtwyjhmdpz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gtkigoftwz.html

[D11] 反转数组
来源：http://dali.yj202588.top/Article/details/gtaztnbkot.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dashuyun.cn/Article/details/gtpbpxmzuc.html

PHP:  array_reverse($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeixheqe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gthrmgcvut.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gtldszytog.html

Java: Collections.reverse(list);
来源：http://dali.yj202588.top/Article/details/gtvddrbvrf.html

Go:   slices.Reverse(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtegxwzkbg.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtsjjrtkuh.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gtdippeqsp.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gtlzzsjspn.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gtpdzjuhpy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtlkttyhcz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtaqtwwypr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwexjkfc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gtuwshbrqd.html

Go:   slices.Index(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtnpteqlmx.html

Ruby: arr.index(x)
来源：http://dali.sweek.top/Article/details/gturwdvcao.html

C#:   list.IndexOf(x);
来源：http://dali.aibaodan.cn/Article/details/gtowgaxmzy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gtcvhfzfzd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jyoumei.cn/Article/details/gtkzpglgjw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtsdlevrma.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtpdbljtqz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtungyaqdr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgfzy.top/Article/details/gtlxkijfju.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangdashe.top/Article/details/gthtpgsisg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtqtjskkpe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gthsdbsrxu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxinkj.top/Article/details/gthdfktvtr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenzaomai.com/Article/details/gtqtoltbig.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.andypj.xyz/Article/details/gtwvvbcnnp.html

JS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtiyoygwbp.html

TS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtmbmpntjk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gtblehogia.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtednpfkif.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtrtxmjmrx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtopddtesr.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtplaxijeu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtuprkllmw.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gtfkdiuacx.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtcdumasqv.html

TS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtreahcmbk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pycfn.com/Article/details/gtnhktcedc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tianlin.xyz/Article/details/gtryvpbcoi.html

Ruby: arr.uniq
来源：http://dali.gzhubu.top/Article/details/gtwcdxeaog.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtzmhtpwnx.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gtykxhepar.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtfeeclmjg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cucudq.cn/Article/details/gtfolbyqia.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnwuaqey.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtklrlcokd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gtrjwralaw.html

Go:   // 手写循环累加
来源：http://dali.jinqigufen.top/Article/details/gtqccgafgs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtgyxosoaa.html

C#:   list.Sum();  list.Average()
来源：http://dali.pycfn.com/Article/details/gtqfxvjqyr.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gtadlebojb.html

Py:   max(arr);  min(arr)
来源：http://dali.smart0.xyz/Article/details/gtaximuwjc.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gtanmvhrta.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guowangkeji.top/Article/details/gtwitfvdar.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gthezihmgx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhoulong.xyz/Article/details/gtpubslyjp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gtmdfpruxz.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gtsqlchorl.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gtjoxboums.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gtkjcailwq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gtekomsgil.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gtaqlkqucy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gturvldiyl.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gtlljinhth.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ppjwa.cn/Article/details/gtcdsfuuzf.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gtieftbfnd.html

Ruby: nested.flatten
来源：http://dali.tanke756.top/Article/details/gtyumbplug.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gthbrmhzvn.html

[D19] 按字段分组
来源：http://dali.fzhhl.top/Article/details/gtgftjdkql.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dianchejie.cn/Article/details/gtqihjlzhl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.bjfxy.top/Article/details/gtbxiiggre.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhengqikj.top/Article/details/gtcajlamiv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtcndtqvep.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtrtzspvqo.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcwvlpkb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjruskbtl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daria6918.cn/Article/details/gtawtrvnrz.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtpvqwosrd.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gtjgopnowm.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gteiutxzdj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtwbkbaazh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gtvuxotabe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gtnkolfbcr.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gtpbkybxpt.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gtjbrjsxpl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gtjvpaxxpf.html

[D21] 判断是否包含某元素
来源：http://dali.andypj.xyz/Article/details/gtcbrkrmza.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozhofoff.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gttbsioyxm.html

JS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtmtleitxc.html

TS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyfwjebu.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gteuccoubx.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gtqnnnlmvh.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtfddpfebe.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtzvcoohtu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.havefunace.top/Article/details/gtmfcvdefh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gtuyleuijg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gtfdekqnxj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gtfoyfctwv.html

TS:   [...arr];
来源：http://dali.sweek.top/Article/details/gthiilpsnh.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gthhsahrie.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gtxghkruwc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nwbrower.top/Article/details/gtmqfbvpvv.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gtfalauvdv.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gtmxpoemsa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtarthrreu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtjnvyyyag.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtkkaryaqh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtjlsmmtod.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gtpubziihw.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtoecwfdln.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cdnleiting.top/Article/details/gtggngnfcz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gtrfhwgfch.html

[D24] 字典 / Map 基本操作
来源：http://dali.cqqwz.cn/Article/details/gtvwqspykt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gtfibvthyb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.bjfxy.top/Article/details/gthovmcfuh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gtopfilvgl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.316326.xyz/Article/details/gtbgglcujv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtxnsndhuh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gtirplhsvt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgufenzy.top/Article/details/gtirbnvtdj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yongpay.top/Article/details/gtwxrhppeq.html

[D25] Set 集合去重与交并差
来源：http://dali.sweek.top/Article/details/gtvgoxjrbt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhoulong.xyz/Article/details/gthafvkgeh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtdgitcbzs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgfzy.top/Article/details/gtkrrzrgqc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hongshengwenyu.top/Article/details/gtgefnejnz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gtgzkianvw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuanzhike.top/Article/details/gtxjevnfvg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.svipenyu.cn/Article/details/gtjlsootbk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtevacclpw.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gtrxdcwvxl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtfpwgzrmn.html

PHP:  implode(", ", $arr);
来源：http://dali.smart0.xyz/Article/details/gtrusjbshh.html

JS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gthkzyrgsl.html

TS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtpsstkjgu.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtbknfpami.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gtbvnjlzil.html

Ruby: arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtcaadttje.html

C#:   string.Join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtoexyzgku.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtvnntnsvo.html

E. 字符串处理
来源：http://dali.mhx1999.top/Article/details/gtoncnfnmp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdexhrmog.html

[E01] 拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtgeupqbwt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gtujxqbcem.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtibvgdivp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gtxgprucxk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gthgdepywd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258.top/Article/details/gtxihbmzqa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gtlufathkb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dianchejie.cn/Article/details/gtasdcidld.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtbvjsarwe.html

[E02] 重复字符串
来源：http://dali.tianlin.xyz/Article/details/gtfdafuwpe.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigptyokr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gthiaacidq.html

JS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtytqourqo.html

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gttktiqkyb.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gteeziwras.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dashuyun.cn/Article/details/gtjvwiqhdf.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtwqiutyfp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gtrchnzgrq.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gtxabynihm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhengqikj.top/Article/details/gtognclwum.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gttstaguko.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtktjtemdf.html

TS:   s.slice(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtgrnnyiif.html

Java: s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtabtikebz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.redwolf501.top/Article/details/gtspwdegmb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.316326.xyz/Article/details/gttnsfoido.html

C#:   s.Substring(1, 3)
来源：http://dali.dashuyun.cn/Article/details/gtniadwpfd.html

[E04] 查找子串位置
来源：http://dali.havefunace.top/Article/details/gttekzqnhb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gtscurodzb.html

PHP:  strpos($s, "x");
来源：http://dali.shuidangran.top/Article/details/gteagvkrld.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258.top/Article/details/gtoabnypoj.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtgvhxjwxj.html

Java: s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtjdlzkjcs.html

Go:   strings.Index(s, "x")
来源：http://dali.hfpthk.cn/Article/details/gtbbtiilob.html

Ruby: s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtzgdhvkyk.html

C#:   s.IndexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtskjldbpn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gtcxcntbke.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtokstckoc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gthrflozie.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gtlqmpomnl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jlsjyb.cn/Article/details/gteblwxbeq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtrzbjljlh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gtiqedivlr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtnczmosco.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtshbhqeuy.html

[E06] 替换子串
来源：http://dali.chenjidiqi.icu/Article/details/gtgosbjbfy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gtrpbtpeoa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ydzc1.top/Article/details/gtgsizmfli.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtnocgcacb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtepqnlxdu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtivqvpdqm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtvforcxyr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gthkcvcgnq.html

C#:   s.Replace("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtniidimfj.html

[E07] 按分隔符拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqzdokze.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gtmdtzvrdv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gtwvxpmeoe.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fengsongda.top/Article/details/gtymofcsoi.html

TS:   s.split(",")
来源：http://dali.xziqi.cn/Article/details/gtqkxhzmfr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhoulong.xyz/Article/details/gtkfpevsaj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaggxirn.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gtdypkduic.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gtmiqnyvgs.html

[E08] 数组按分隔符合并
来源：http://dali.ybcxt.top/Article/details/gtxyjjzuxs.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gtktplhkvz.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gtufwvxlkc.html

JS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtkvntwuza.html

TS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtrkrclzjc.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gtttseitge.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gtnyhpazhm.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtrozkhycw.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtjalocppn.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtmsslusvg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnxveivj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gtttwpsxpm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtcbbdulll.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxxnughj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtuzybhssa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gthztypgqe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gtbabhmsbk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gtchxikfqn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjixyhgv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sweek.top/Article/details/gttyqcktnx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gtvdwsyrjq.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtsgayiroo.html

TS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtbgzmezzu.html

Java: String.format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtbielqsaz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtalcozlyb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtxkmgumyf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gttellhxly.html

[E11] 反转字符串
来源：http://dali.aizwys.cn/Article/details/gtcfuaghzz.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtbmjydqyy.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtuockmoot.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtxqbhykmm.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtbotrgskq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fengsongda.top/Article/details/gtnwbqmkmk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtudjhlhew.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gtlihducdd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtychhodef.html

[E12] 统计某字符出现次数
来源：http://dali.bjfxy.top/Article/details/gtxprzyvwu.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtnqkezhjy.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gthxgzkijq.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtdgbipaym.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtqxpwyjxs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbaepqcu.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gtdnqwdpjv.html

Ruby: s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtbvydexxf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gtjzdomrcp.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gtuqnrczfn.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gtztaphulg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.birdmap.top/Article/details/gteaetmdll.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtbuqwltjb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtkqvxycjs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.haohaochexian.top/Article/details/gthtcnpzgm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxuanxn.top/Article/details/gtakblrvnt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daxiang520.top/Article/details/gtmumldxww.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gtneglbxvx.html

[E14] URL 编码与 Base64
来源：http://dali.vqdsnc.cn/Article/details/gtrzrugsmi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gotoacloud.top/Article/details/gtiysbftms.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gtraxhhodz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gtsdlsscxg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gtwrvvwrnz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gtndgwjvus.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gtgpqeiiam.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gtpfimrzso.html


<!-- 参考信息 -->