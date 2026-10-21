代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gtyjaiunmc.html

TS:   [...a, ...b];
来源：http://dali.yuanzhike.top/Article/details/gtqlxcthma.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gtgbphones.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtavkncasr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gturpucuqe.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gtpdtdwvvh.html

[D09] 排序（升序）
来源：http://dali.feifeiyinyue.top/Article/details/gtdxeiwtzl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtbgbwkboc.html

PHP:  sort($arr);
来源：http://dali.cqqwz.cn/Article/details/gtoftjmoxn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fzhhl.top/Article/details/gtpwtqjyez.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigufen.top/Article/details/gtfkqrddem.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pycfn.com/Article/details/gtxovfljep.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtguwsneic.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtdlplbkdr.html

C#:   list.Sort();
来源：http://dali.birdmap.top/Article/details/gtlitmzxqi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gaohongyu789.top/Article/details/gtjzrovsqi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ydzc1.top/Article/details/gtplttpinc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gtvsdsicft.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gtkjtcwgxz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtajmazekk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gttuncpzkc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.c1oappe.top/Article/details/gtixzldcib.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.birdmap.top/Article/details/gtvxlpxxfj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cheryme.top/Article/details/gtmutjcmld.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gtangqrrrb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yangfankeji.com/Article/details/gtokqoqear.html

PHP:  array_reverse($arr);
来源：http://dali.ivvv.top/Article/details/gtxaeubsjk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hongshengwenyu.top/Article/details/gtggzshqky.html

TS:   [...arr].reverse();
来源：http://dali.jinqigufen.top/Article/details/gtmxvtznyu.html

Java: Collections.reverse(list);
来源：http://dali.zycfv.cn/Article/details/gttcsvexos.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gthnuqqntg.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gtxqfklwun.html

C#:   list.Reverse();
来源：http://dali.sxryk.cn/Article/details/gtyneusndz.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gtdupevpwd.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtjlnmihkb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gttrsrbebf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gttxbtoewg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtxasdgbxv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hfpthk.cn/Article/details/gtsbnjllzk.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtwcbhzfhm.html

Ruby: arr.index(x)
来源：http://dali.c1oappe.top/Article/details/gtcychppke.html

C#:   list.IndexOf(x);
来源：http://dali.yvedp.cn/Article/details/gtzsiaqkwa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gtdmksxwdm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gtsmnkewmz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gtstcoobrp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtjphigugs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtzhydfitr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtlpseyalw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gtulrefsjf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gtzoxnnyur.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtemyvcwuk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gtnsmyeopt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gtpnbrrwgl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxinkj.top/Article/details/gtivrssqpt.html

JS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gtvrdknqyn.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtjzirtwzf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.316326.xyz/Article/details/gtonbibuwv.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtjodugewj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtlnsodtto.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gtmzhpqrap.html

[D15] 去重
来源：http://dali.jiagoushi.top/Article/details/gtbxtgxjsp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtmvvldutk.html

PHP:  array_unique($arr);
来源：http://dali.yangfankeji.com/Article/details/gtlnxkoafa.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtolihrcla.html

TS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtuvpyxebp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gttzdggdyu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwnnmnbk.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gtbbsycdnb.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gtfsdpzgfv.html

[D16] 求和与平均值
来源：http://dali.chenlongwang.top/Article/details/gtahetarlv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gtfhmjednd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gtnnccsuju.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtqkcdzbll.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtuyveoqlb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhoulong.xyz/Article/details/gtbohdznms.html

Go:   // 手写循环累加
来源：http://dali.aizwys.cn/Article/details/gtuawljjdr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gtjhxdbebx.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gtxzaiasib.html

[D17] 最大值与最小值
来源：http://dali.tianlin.xyz/Article/details/gtdgdwgsai.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtjmhankrw.html

PHP:  max($arr);  min($arr);
来源：http://dali.havefunace.top/Article/details/gtbibhuieq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hysaishi.cn/Article/details/gtawotytla.html

TS:   Math.max(...arr);
来源：http://dali.aibaodan.cn/Article/details/gtehfrspbw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gtdofmkdeo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuanzx.com/Article/details/gttvmpjokp.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gtkpfitlht.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gtcyiniris.html

[D18] 扁平化嵌套数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoslbwlcb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gtanpptuyj.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gtcefgisxg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xinyue.icu/Article/details/gtbfmlqcpx.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gtoawiewmp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gtukkmvijg.html

Go:   // 手写双层循环
来源：http://dali.zhixingplan.top/Article/details/gtorjealvl.html

Ruby: nested.flatten
来源：http://dali.ehwqpu.com/Article/details/gttnvmmlby.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtiozoahoo.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gtdmupmwvm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuanzhike.top/Article/details/gtkccjorjd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gtdyiniawp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gtebtfgwci.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gthikmemuk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtfybywqyn.html

Go:   // 手写 map[string][]T
来源：http://dali.jyoumei.cn/Article/details/gtmwczcnpd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258.top/Article/details/gttyraltdl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daria6918.cn/Article/details/gtehjmaohm.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gthhploztc.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gtxrumgoev.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtueaspuxb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtbmfwfwda.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtyktdwuwg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gtjukzoyfz.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gtwudvxukq.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gtzpuylyff.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ybcxt.top/Article/details/gtqeqrumzy.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gtixjqmnkr.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gtlydmdnaa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.bjfxy.top/Article/details/gtmlqmlffx.html

JS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtfpgzprbf.html

TS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtwamvqfua.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtfnerlmte.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gtffjpxfin.html

Ruby: arr.include?(x)
来源：http://dali.yuxming.cn/Article/details/gtkdichdxu.html

C#:   list.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtkfxzwbhz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daria6918.cn/Article/details/gtzzmkmqda.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zdqjudy.top/Article/details/gtsheohtmw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.c1oappe.top/Article/details/gtgmdbbunb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkdfghfi.html

TS:   [...arr];
来源：http://dali.yuxming.cn/Article/details/gthlvqugvz.html

Java: new ArrayList<>(list);
来源：http://dali.hammf.cn/Article/details/gtmnlvxhym.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shuidangran.top/Article/details/gttpyjpxrf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.andypj.xyz/Article/details/gtcjdkkaiw.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gtnkvhfzei.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gtbprxieun.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.snrcjt.cn/Article/details/gtkplvyukx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gtcwjploga.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnjnbeuk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtbhhabcto.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.bjfxy.top/Article/details/gttrmxulxz.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpuxqjge.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenzaomai.com/Article/details/gtrwsbmthi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnqzz.top/Article/details/gtctcqnnay.html

[D24] 字典 / Map 基本操作
来源：http://dali.shuidangran.top/Article/details/gtttvvncqx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigfzy.top/Article/details/gthudkneqf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.feifeiyinyue.top/Article/details/gthtdlpkxr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gtayxaakhx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtbxwabvfk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gtsmfnqgfb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zdqjudy.top/Article/details/gtpdopsbpv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gtsudgvvlj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gtkyuqecri.html

[D25] Set 集合去重与交并差
来源：http://dali.kuanghao11.cn/Article/details/gtvdlktptu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daxiang520.top/Article/details/gtizpywwmg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hysaishi.cn/Article/details/gtzpydlgkv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gtpihertnj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hfpthk.cn/Article/details/gtleqjabmb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtcjatybba.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ivvv.top/Article/details/gtjlmmbcvm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gtoylubjqu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtjxwnljtl.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gtzabhmqqh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtqgmbaaad.html

PHP:  implode(", ", $arr);
来源：http://dali.xziqi.cn/Article/details/gtjbucjqak.html

JS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtbmgneded.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gthswcuzly.html

Java: String.join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqsdnrzu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sweek.top/Article/details/gttrkdubrp.html

Ruby: arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtxxqwqlym.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtnxpeeiil.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtptqaovli.html

E. 字符串处理
来源：http://dali.yangfankeji.com/Article/details/gtcfnezvcd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtcdowkmii.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gthwerrfeq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhoulong.xyz/Article/details/gtbeubgvmo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gturksscgu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gtsmqvubmg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtzawvmksu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gtetncxiei.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gotoacloud.top/Article/details/gtonmhzskc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangdashe.top/Article/details/gtwlixaxwh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtjofisgnl.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gtdupevjuy.html

Py:   "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gthasayepy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtkigbmnsv.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtjfebdrop.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtgiskmpgl.html

Java: "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtwrtdhrdv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xinyue.icu/Article/details/gtwsevveib.html

Ruby: "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtwajjszxb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gtejrcpjdn.html

[E03] 截取子串
来源：http://dali.yueranfly.top/Article/details/gtyuytmksl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.quarkkingdee.top/Article/details/gticmyzlkk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtiideibok.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtkptesssy.html

TS:   s.slice(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtnhmgtsbm.html

Java: s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtecmodild.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtntmsmzib.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuxming.cn/Article/details/gthnowwocn.html

C#:   s.Substring(1, 3)
来源：http://dali.jyoumei.cn/Article/details/gtzytixczs.html

[E04] 查找子串位置
来源：http://dali.daxiang520.top/Article/details/gtjhrpifdn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gtsirdlcva.html

PHP:  strpos($s, "x");
来源：http://dali.cdnleiting.top/Article/details/gtxhywbfwq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gtkfuujhgd.html

TS:   s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gthyvbpcwd.html

Java: s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtwonlqitg.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gthniurxyj.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gttydfzhwc.html

C#:   s.IndexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeqcjtpq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yanxiufei.cn/Article/details/gtzhxsfjzl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gtuffgpxus.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gtufykiems.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtkzyccrfv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zdqjudy.top/Article/details/gtfmxiytwq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtbfcsojfo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.havefunace.top/Article/details/gtntwioroi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangdashe.top/Article/details/gtrzmbzmvm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtdorbkrxp.html

[E06] 替换子串
来源：http://dali.zhixingplan.top/Article/details/gtdbykxlsy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtvmqbtriz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cheryme.top/Article/details/gtfxmcrvzc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gttawvlgpk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gteymjrhip.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtgjprnjpy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gtkciuoqvf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtfkahbabr.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gttupubfse.html

[E07] 按分隔符拆分
来源：http://dali.yuxming.cn/Article/details/gtasivepuq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gtchtmlctk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shuidangran.top/Article/details/gthzwfzigh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtfwlazwyh.html

TS:   s.split(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtumvisshb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrnsixzh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shzxlz.cn/Article/details/gtateavazo.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gtrwmpdgrs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhoulong.xyz/Article/details/gtukphjjmz.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gtogklemow.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gtmymbdfyp.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gtiiucbocz.html

JS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtrzyzjnkz.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtfbgrihre.html

Java: String.join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtnehejrmm.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnxlgkgh.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtmovzauod.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtegqxpvid.html

[E09] 去除所有空白字符
来源：http://dali.pycfn.com/Article/details/gtymmjzgzd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tianlin.xyz/Article/details/gtzvvevngs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jianghu66.top/Article/details/gtatbfefmg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtupujddhm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtxellwdpd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gtyusvaokm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gteqyigpij.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.haohaochexian.top/Article/details/gthjgomnza.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtcjlpoclk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gtpohxmavl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gtuospntzk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuanzx.com/Article/details/gtdrbpokix.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzicgeghj.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtiunxqjfk.html

Java: String.format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtapbfmuhx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gthixsbzrm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtlavqiapx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cashguo.top/Article/details/gtnmnapuov.html

[E11] 反转字符串
来源：http://dali.ivvv.top/Article/details/gtlsndwozn.html

Py:   s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtrzxzhpgm.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gthfpxymzf.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtmtkiedeu.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtltustrbc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtldzyxekf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtdnueweye.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gtpywwywwn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtsxygrhxi.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gtmbvgzfuf.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcgugczc.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtcqtlqnwc.html

JS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtxerizown.html

TS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtgvsedoxy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gtzsxvyxxm.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gtdhwtrogr.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gtkkmmjapc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgfzy.top/Article/details/gthawazbrm.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gtrxurrizl.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gtrafhnruc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gtqjfyebqv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtgdggcxua.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpkbhzcq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuanzx.com/Article/details/gtthidvwbp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.smart0.xyz/Article/details/gtfnkbgfqs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gtqkeidlxv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cdnleiting.top/Article/details/gthvbwczty.html

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gtyzgvoquc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gtpydrlfsz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvpinbwu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gtnfmqmlay.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gthjerlpuu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtfpoyiuzo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gtnlmalyon.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.feifeiyinyue.top/Article/details/gtukdidxbj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gtjmohvvbl.html

[E15] HTML 转义 / 反转义
来源：http://dali.shuidangran.top/Article/details/gtoytklhkl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhixingplan.top/Article/details/gtdktktjzk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhoulong.xyz/Article/details/gttaddgcob.html


<!-- 参考信息 -->