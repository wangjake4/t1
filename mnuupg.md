代发 wailian999

Java: list.size();
来源：http://dali.aizwys.cn/Article/details/gtqisahpcd.html

Go:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtpqljcxlb.html

Ruby: arr.length; arr.size
来源：http://dali.jianghu66.top/Article/details/gttnvtqvwv.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gtkjepwltm.html

[D07] 切片 / 取子数组
来源：http://dali.jyoumei.cn/Article/details/gtyoqtzowe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxdwqucw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.redwolf501.top/Article/details/gtybxnuehu.html

JS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtnykuckal.html

TS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtqyfyijdv.html

Java: list.subList(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtxoogmrjh.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gtkdbhtqpk.html

Ruby: arr[1, 3]
来源：http://dali.xylfe.cn/Article/details/gtkvrsdkak.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtditsdrkp.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gtkrurpbyy.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gtinyutfni.html

PHP:  array_merge($a, $b);
来源：http://dali.316326.xyz/Article/details/gtcwllwizj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.havefunace.top/Article/details/gtevorerfn.html

TS:   [...a, ...b];
来源：http://dali.jyoumei.cn/Article/details/gtibnmatcb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gtupyfwxgn.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gtenpcahwx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yonumen.top/Article/details/gtdtsmjraa.html

C#:   a.Concat(b).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtpfwtzhro.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gtsoavnwta.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtcojxmjsv.html

PHP:  sort($arr);
来源：http://dali.xylfe.cn/Article/details/gtxxzymilj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gtjursbjbl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcyvzrki.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tanke756.top/Article/details/gtqgprlfcr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gteqrgshjf.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtpsvocyht.html

C#:   list.Sort();
来源：http://dali.zdqjudy.top/Article/details/gtvxdsipuy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonhqgobr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258888.top/Article/details/gtsmjitrgq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtjtdqztsq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gthmhlomzj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtxxcnrglv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gtmpvgjkaw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guannengcc.top/Article/details/gtxminjteo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gtmiqassbf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aizwys.cn/Article/details/gtdlnxvqkv.html

[D11] 反转数组
来源：http://dali.jinqigufen.top/Article/details/gtyoymmzwr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hongshengwenyu.top/Article/details/gtpnmvtzkf.html

PHP:  array_reverse($arr);
来源：http://dali.xuanzx.com/Article/details/gtfmxskagx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jiagoushi.top/Article/details/gtlnsxegeb.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gtropqgequ.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gtwtffhzfx.html

Go:   slices.Reverse(arr)
来源：http://dali.xziqi.cn/Article/details/gttqsrxsgh.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gtakmpzihr.html

C#:   list.Reverse();
来源：http://dali.zhixingplan.top/Article/details/gtgblosjmk.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gtovxwanvm.html

Py:   arr.index(x);  x in arr
来源：http://dali.jiagoushi.top/Article/details/gttrfbtfss.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gtrtntgasf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gtrqarxuyg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtnfummocy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuetiantiany.cn/Article/details/gtujczogvp.html

Go:   slices.Index(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtyvlecjqa.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgragxjlz.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjdznnth.html

[D13] 过滤（保留满足条件的）
来源：http://dali.birdmap.top/Article/details/gtiyndclhg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ppjwa.cn/Article/details/gtpuvqjqdj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gtttahwtnn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtudthahwr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gttqppibwx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhwezmev.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gtqwwxasdk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtykiosisv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gtvyalwwlr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gtykgwogyt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gtibodjpsv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gtxkknfqup.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtmdpztcxp.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtnuimqxuy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.svipenyu.cn/Article/details/gtzflerwfh.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtuaswdbem.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xinyue.icu/Article/details/gtghnutoqx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtomofgdeh.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gtgerqdkvf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gtcykqzlqe.html

PHP:  array_unique($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtybmmsacs.html

JS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtvdalhltz.html

TS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gtrpkumgag.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yangfankeji.com/Article/details/gtzgmiaram.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gtrqtsdxyz.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gtqzgqpmbh.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtueyppkzi.html

[D16] 求和与平均值
来源：http://dali.shangyingyoupin.top/Article/details/gtbfyzosni.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtdvhqcmub.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hywenlv.cn/Article/details/gttotavwlc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtedfodbhd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gtojrijrrr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhengqikj.top/Article/details/gtkydqpafv.html

Go:   // 手写循环累加
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqastbdb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gtioifnngy.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtusaoatqc.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gtaetquhyb.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtkdtmohsj.html

PHP:  max($arr);  min($arr);
来源：http://dali.havefunace.top/Article/details/gthpsbxfut.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtanrdyesw.html

TS:   Math.max(...arr);
来源：http://dali.iojbl.cn/Article/details/gtuzkshwhg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ydzc1.top/Article/details/gtgquxyfoz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtuvsapbmn.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxinkj.top/Article/details/gtugumvttv.html

C#:   list.Max();  list.Min()
来源：http://dali.birdmap.top/Article/details/gtggddzerz.html

[D18] 扁平化嵌套数组
来源：http://dali.daxiang520.top/Article/details/gtkrjzhuqk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gtinxfnqji.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gtmcowillm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jiagoushi.top/Article/details/gtpfonmfbk.html

TS:   nested.flat();
来源：http://dali.zycfv.cn/Article/details/gtblsjydzj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jianghu66.top/Article/details/gttaxllprz.html

Go:   // 手写双层循环
来源：http://dali.nanxinkj.top/Article/details/gtteiybpat.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gtrylijpae.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtekwkzmlo.html

[D19] 按字段分组
来源：http://dali.gogol.net.cn/Article/details/gtendydbos.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gtiehdomxt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtmaiuxloj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.redwolf501.top/Article/details/gtbfslvtsm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtjltcnduf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhongyouzk.top/Article/details/gteoeavjgb.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gtagpgfroz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gtsvtbcxot.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gtzkzdlaah.html

[D20] 统计每个元素出现次数
来源：http://dali.shzxlz.cn/Article/details/gtkmvlwevs.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gtdjxytqzw.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gtynmikoek.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtovetrdjd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtsjthdora.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gtxugbgtum.html

Go:   // 手写 map[T]int
来源：http://dali.0kj1m.cn/Article/details/gtqwjbjhzj.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gtsugbndhj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gttgynlwlj.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gtmzandayj.html

Py:   x in arr
来源：http://dali.shuidangran.top/Article/details/gtezughmgc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gtjoqpafym.html

JS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtgampuguc.html

TS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtcewqcoyj.html

Java: list.contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtkpvrabyj.html

Go:   slices.Contains(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtrtxfxmsb.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gtqjoaoyka.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtjhsctokg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gtyoegqpvp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtgkawzovc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gtnhtvcgmo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gtyszyiloq.html

TS:   [...arr];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmaepxtk.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gtsrvkmysb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gttnvgrlqc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhongyouzk.top/Article/details/gtbxljpilp.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gtelgkuadu.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gtzucptcpa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouurllzs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangdashe.top/Article/details/gtgfniprta.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gtlvzdzoet.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtjzgqilxa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gtointjdgh.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtatoauirz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gtftamrcha.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangdashe.top/Article/details/gtbnirpqaf.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gtoxmuyxhz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.birdmap.top/Article/details/gtksziqmgt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gtryrwudhy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtajbzjklb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpzgcqmg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yangfankeji.com/Article/details/gtertasfwq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtehwyfqbg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftwnigak.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxuanxn.top/Article/details/gtssdufidt.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gtnpxbwydb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gtgfetaskl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gthomriitw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gaohongyu789.top/Article/details/gtepgbylrl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yueranfly.top/Article/details/gtxmwgxhiw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtyimhwvxz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gthmhirifm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gthpoxdchx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gthktfsnxw.html

[D26] 数组转字符串
来源：http://dali.c1oappe.top/Article/details/gtlpwfyjhk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtxqwhziec.html

PHP:  implode(", ", $arr);
来源：http://dali.shzxlz.cn/Article/details/gtreqooght.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtlftexjyv.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtsbgsbmkf.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtuvzfhwre.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtcbxnnlqx.html

Ruby: arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtwtnwvypm.html

C#:   string.Join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtkafwwsvr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgwvwmwzk.html

E. 字符串处理
来源：http://dali.shuidangran.top/Article/details/gtgwxribbl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtskyzrdpt.html

[E01] 拼接字符串
来源：http://dali.zycfv.cn/Article/details/gticwyknbf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.feifeiyinyue.top/Article/details/gtigjbafkt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gtvlwtnfki.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtvmiddlhj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gttksnfejg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hongshengwenyu.top/Article/details/gtggtejhxt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gtletsqdoy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gtqmesvdnd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gtrikphbjz.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gtcagarcyn.html

Py:   "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtiqddwxhe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtwunlgdtj.html

JS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqeojynsk.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtzdgywasz.html

Java: "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtbjdxnwui.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtqjmkjgvm.html

Ruby: "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gtpuwbnhcw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guannengcc.top/Article/details/gtykynvvlo.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtwgzdgicz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gtrucycwcr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtoscyserj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtigrxunvr.html

TS:   s.slice(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtvhwqufst.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtgdawdhcd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gttcxetbid.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gtvebisdwk.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gtyirvojrj.html

[E04] 查找子串位置
来源：http://dali.hammf.cn/Article/details/gtpelmnuvv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtqbjehvdi.html

PHP:  strpos($s, "x");
来源：http://dali.daxiang520.top/Article/details/gtamcgqfez.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guannengcc.top/Article/details/gtiflixpal.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtgtqjcnid.html

Java: s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtihvgjfiz.html

Go:   strings.Index(s, "x")
来源：http://dali.chenlongwang.top/Article/details/gtatppbdaq.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gtxzvgmlml.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gtmkjixaxo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaxiuzfh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtpvgmymch.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zdqjudy.top/Article/details/gtqozaxvba.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtpnpllhju.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gtsozdupii.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtzkdnfliz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigufen.top/Article/details/gtbxyjxjgx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gotoacloud.top/Article/details/gtfczddbrn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtnxrubvfx.html

[E06] 替换子串
来源：http://dali.daxiang520.top/Article/details/gtelmqrvyj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtnoqxhlpn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gtyqblwxzd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtduguunbt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtmyypyopm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtzwfjhuvp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtozurfsyr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtgnfrbier.html

C#:   s.Replace("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblywqnjl.html

[E07] 按分隔符拆分
来源：http://dali.xziqi.cn/Article/details/gtpxdxmmml.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gtigafbntv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtsgadncbw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tian-w.cn/Article/details/gtndtjnrci.html

TS:   s.split(",")
来源：http://dali.sxryk.cn/Article/details/gtmudsrtxh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gtdjewpzly.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tian-w.cn/Article/details/gtrdvxxghf.html

Ruby: s.split(",");  s.split
来源：http://dali.gzhubu.top/Article/details/gtztgpharg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpmyvqyz.html

[E08] 数组按分隔符合并
来源：http://dali.aizwys.cn/Article/details/gtkkmyqqve.html

Py:   ",".join(items)
来源：http://dali.nanxinkj.top/Article/details/gthkwnlpnk.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gtpwvjqhbb.html

JS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtsexanexh.html

TS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtdlqddhmc.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gtmdytkdmo.html

Go:   strings.Join(items, ",")
来源：http://dali.hammf.cn/Article/details/gtuhqwzcih.html

Ruby: items.join(",")
来源：http://dali.yongpay.top/Article/details/gtyrqookva.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtuvvbnlly.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gttejmiwgc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gtrswugmse.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aizwys.cn/Article/details/gtsruhbhap.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtbzxrgooy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtojppkdyu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gthturtbqw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gtdwaybojb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gtxfdjlcyj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtimfqntkv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gttyaaqtlj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tanke756.top/Article/details/gtkxicjhvz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hysaishi.cn/Article/details/gtqfclxnkq.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtvhajgicg.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtwdfhxdea.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtvppyfzfe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtetzvicai.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtkjajyoxn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gtkplluchg.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujkjqyws.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gthitnsyfl.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gtzbgvgefy.html

JS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtabxdhkmi.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtvyyrwvaf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cashguo.top/Article/details/gtahgvudiz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtzibpwegn.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtwhmpvnhp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtfovgqkav.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtouiwnwkt.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtmzaitwkt.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gtpbhqearz.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gtuljhupsm.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtlsmlzkyw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gtqiuecywz.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gtnrdkyhfa.html

Ruby: s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gtkwaodmdq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtfhdqrqbg.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtlijpfdui.html

Py:   for ch in s: print(ch)
来源：http://dali.quarkkingdee.top/Article/details/gtrfuhkeqb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gtqlibluva.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtopnnkxge.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtzpbvazbo.html


<!-- 参考信息 -->