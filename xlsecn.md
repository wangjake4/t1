代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.daria6918.cn/Article/details/gthdgwmdsw.html

C#:   a.Concat(b).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtbckhyrvz.html

[D09] 排序（升序）
来源：http://dali.cqqwz.cn/Article/details/gticxaudid.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtnpbzjbqz.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gtzjndklns.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangdashe.top/Article/details/gtkhinmpdr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.feifeiyinyue.top/Article/details/gtkkyebtzl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gtfewijile.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtjbotuftk.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmnnwmgk.html

C#:   list.Sort();
来源：http://dali.ybcxt.top/Article/details/gtrokijzts.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aizwys.cn/Article/details/gtzpgbwfiv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvgimect.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtywfqddvo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuyypzng.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtozzagesq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gtwwxiplng.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.9152youxi.cn/Article/details/gthwssvxwa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gtorlfmhdr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gtsbkcuszl.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gtwkbilsmw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gtljjyuwvt.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gtalogulgz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tianlin.xyz/Article/details/gtgbakmlfr.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gtxkftumwy.html

Java: Collections.reverse(list);
来源：http://dali.dianchejie.cn/Article/details/gtllfogeje.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gtdkleleqk.html

Ruby: arr.reverse
来源：http://dali.haohaochexian.top/Article/details/gtffjapapb.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gtknshicdr.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajvzfyzm.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gtvvffozgh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cucudq.cn/Article/details/gtyowbhoqv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtvagoyhrl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtshdauoph.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jlsjyb.cn/Article/details/gtzlsrqofy.html

Go:   slices.Index(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtwcbtrgny.html

Ruby: arr.index(x)
来源：http://dali.9152youxi.cn/Article/details/gtbzfesnjy.html

C#:   list.IndexOf(x);
来源：http://dali.jqgufenzy.top/Article/details/gtwsfvykew.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuanzx.com/Article/details/gtszohfzve.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gtneobgymh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtgfewbkmj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gtrxdapmna.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gtwwupupkd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.316326.xyz/Article/details/gtvrzngmcu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xylfe.cn/Article/details/gthnlodpls.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpperwyw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gtsnetoskl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aibaodan.cn/Article/details/gtcyswchbn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daria6918.cn/Article/details/gtczyvkqvk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtbyghrcxj.html

JS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtbwjyquqt.html

TS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtvqhihzwh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xylfe.cn/Article/details/gtnhdgapij.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtmykuggho.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtvrnlyzvv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnqzz.top/Article/details/gtqxtzchau.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gtkvcjqsto.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gthtzdahzv.html

PHP:  array_unique($arr);
来源：http://dali.andypj.xyz/Article/details/gtzmmdaaup.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdocrake.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtgmbgridw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gogol.net.cn/Article/details/gtaqjidspz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gtqmtsqaql.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gtqsagssnc.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gtcsapmfxx.html

[D16] 求和与平均值
来源：http://dali.ydzc1.top/Article/details/gtktuwtvvm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtjztdppcl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihrckgmb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtbfafktez.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gttiqgfpcw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gtwttmxhhl.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gtsdpgwsqn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtxwnwtijw.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbroxbogc.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtzhbrtpri.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtniyahsch.html

PHP:  max($arr);  min($arr);
来源：http://dali.fengsongda.top/Article/details/gtlejolwjc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gtfmeomwxy.html

TS:   Math.max(...arr);
来源：http://dali.snrcjt.cn/Article/details/gtawuqlemm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gtvnlrbhfi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gtessfodyd.html

Ruby: arr.max;  arr.min
来源：http://dali.316326.xyz/Article/details/gtgwfnbfou.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gtujrmdfwz.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtafocmult.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jyoumei.cn/Article/details/gtdtynygvn.html

PHP:  array_merge(...$nested);
来源：http://dali.yangfankeji.com/Article/details/gtihepaajv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.haohaochexian.top/Article/details/gtwtfpbltf.html

TS:   nested.flat();
来源：http://dali.zhixingplan.top/Article/details/gtqqslemwh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvrcgurm.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gtxesfojix.html

Ruby: nested.flatten
来源：http://dali.nanxinkj.top/Article/details/gtzftdmvig.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpzhncti.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gtindxtewe.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gtemhwpdmj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tianlin.xyz/Article/details/gtfqrlymrv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gtdvbaidyb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gtaldvomda.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gtfwrcistq.html

Go:   // 手写 map[string][]T
来源：http://dali.hnxiangtu.top/Article/details/gtprkdrqki.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.birdmap.top/Article/details/gtgwtqtdsj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangshuangyany.cn/Article/details/gtqldxiubc.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gthpupjrzx.html

Py:   Counter(arr)
来源：http://dali.jinqigufen.top/Article/details/gtubqvfivi.html

PHP:  array_count_values($arr);
来源：http://dali.ydzc1.top/Article/details/gtghpasivj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtafsrykon.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gthtnloefv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj202588.top/Article/details/gtuodjmqrc.html

Go:   // 手写 map[T]int
来源：http://dali.guowangkeji.top/Article/details/gtdveugzfk.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtukbohflx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnxiangtu.top/Article/details/gtpmobcxey.html

[D21] 判断是否包含某元素
来源：http://dali.snrcjt.cn/Article/details/gtgaxytwub.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gtkgtfxabp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.kuanghao11.cn/Article/details/gtsnfhufod.html

JS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtnyzbeycx.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtvjtsyrrw.html

Java: list.contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtuebiutmo.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtyjuyxyfs.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtbqodsidk.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtunuottpw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gtrfnmtjdg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.smart0.xyz/Article/details/gtyvlxrsqw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gtyltseuxp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gtpfygdzfi.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gtdksshcsv.html

Java: new ArrayList<>(list);
来源：http://dali.yonumen.top/Article/details/gtjsdvkpwp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxhzswzo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cheryme.top/Article/details/gtpezmtuvn.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gtpwexszzv.html

[D23] reduce 累积计算
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdbbcynf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmxaplae.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtgkqcatbt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gtywrdmjoh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtmllyietw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gtetkpwqhd.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtvqwudlyu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gtuojvstmv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigfzy.top/Article/details/gtrjhhwupz.html

[D24] 字典 / Map 基本操作
来源：http://dali.hfpthk.cn/Article/details/gtvcewkzvr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zycfv.cn/Article/details/gtfikwbhfs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pycfn.com/Article/details/gtwmodopnu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gtqhpeyfjn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtznyqjmph.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtzggcnubl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gtbevvgavd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgkqgoeu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gtgpokeyes.html

[D25] Set 集合去重与交并差
来源：http://dali.hfpthk.cn/Article/details/gtiiuspmzx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pycfn.com/Article/details/gtwebgszjy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtktsjwpsq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gtvhlhivty.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gtqkykyksz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ydzc1.top/Article/details/gtfzwxbtkc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigufen.top/Article/details/gtsinnzbye.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gtwkzbhbab.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtemdmzumx.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gtkmpfuybg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gtiwnvpngz.html

PHP:  implode(", ", $arr);
来源：http://dali.xuanzx.com/Article/details/gtrwngupuc.html

JS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtvnsgnkze.html

TS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtasqljyzz.html

Java: String.join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtugdtschn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daxiang520.top/Article/details/gtgpqansnp.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtdfaleqfb.html

C#:   string.Join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gtvhnixlws.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gteuggvcbt.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gtrtpqcziv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtxvlgalen.html

[E01] 拼接字符串
来源：http://dali.birdmap.top/Article/details/gtjirzdldy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigufen.top/Article/details/gtyedkbnrh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gtebrofjxa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtpywbmqfd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gtrrdilaks.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ppjwa.cn/Article/details/gtsxlybumh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtibrnosfk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gtpseyopcq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtvuhuyyzx.html

[E02] 重复字符串
来源：http://dali.shuidangran.top/Article/details/gttukhvnuj.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbbrfnkk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ydzc1.top/Article/details/gtmoldzluu.html

JS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtqspkaxil.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtrjuzrnvt.html

Java: "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gthuuegioh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ivvv.top/Article/details/gtnfscprbu.html

Ruby: "ab" * 3
来源：http://dali.sweek.top/Article/details/gtddjneldy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuxming.cn/Article/details/gtaicpugcg.html

[E03] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtbkxtjwae.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gtdpwgsltb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtxnrkernm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtuumarppx.html

TS:   s.slice(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtrpukwsfp.html

Java: s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtczsrfuvy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.andypj.xyz/Article/details/gtcrimpwqq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtaytvbtxu.html

C#:   s.Substring(1, 3)
来源：http://dali.gzhubu.top/Article/details/gtvuyllucw.html

[E04] 查找子串位置
来源：http://dali.cqqwz.cn/Article/details/gtiyfnwfxx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtfuamujdl.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gtavvmynjv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tanke756.top/Article/details/gtoxowbtqg.html

TS:   s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtvyawjacz.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtztamtqim.html

Go:   strings.Index(s, "x")
来源：http://dali.hywenlv.cn/Article/details/gtkxdhehup.html

Ruby: s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gtymwhohrs.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtddtjwoiy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gtebmxgnyh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sysykeji.top/Article/details/gtkijizdyf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gthtwmuwge.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtsypeduzj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gtsyhexmun.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtiudbfpei.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ppjwa.cn/Article/details/gtayxwmigm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gtnmttblsy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtvgzqaika.html

[E06] 替换子串
来源：http://dali.hammf.cn/Article/details/gtmzwiawoc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtgbfneqxc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guannengcc.top/Article/details/gtfjryjtlc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtkrngzpyp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtxsmbimzz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubvqkamb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtbptmjojo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gthfhmhmtn.html

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtgartqhjf.html

[E07] 按分隔符拆分
来源：http://dali.yj202588.top/Article/details/gtpavxqakd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jiagoushi.top/Article/details/gtgrytyvzz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtqexbwwxv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gtspgzutcd.html

TS:   s.split(",")
来源：http://dali.shuidangran.top/Article/details/gtuvepyqjh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gtzxjvabbw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtadgzpgmc.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtsfmfjgpo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pycfn.com/Article/details/gtjmhuaykv.html

[E08] 数组按分隔符合并
来源：http://dali.dianchejie.cn/Article/details/gtexwgsbnf.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gtsfktyzjl.html

PHP:  implode(",", $items);
来源：http://dali.sysykeji.top/Article/details/gtdztmltff.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtncenvzgz.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtqnygytbq.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtgvdinnau.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gtithbqybr.html

Ruby: items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtnlbmcfhd.html

C#:   string.Join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtynaohxru.html

[E09] 去除所有空白字符
来源：http://dali.jinqigfzy.top/Article/details/gtweqrewbh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gtmgurvdxf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.meibo888.top/Article/details/gthmvccsgs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gtzsszudye.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtjarbehzs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gtbikpxixb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.meibo888.top/Article/details/gtuuarzzpd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigfzy.top/Article/details/gtdufscjsi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gtvklqjaur.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbljindev.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuanzx.com/Article/details/gttaricago.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gtjwfacfnc.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtddueqjsj.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtocgfyyxv.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtotsarimj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtaqkjedqy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtvtotemlm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gtvxrxdlet.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gtpuvioynb.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gteqskdtax.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gttvrdwdlt.html

JS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtngyygwpu.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtttyywjrg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gttzfbwifr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.havefunace.top/Article/details/gtztezmgnk.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtqyxgpiuk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtiuptjvja.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gtilvxijkd.html

Py:   s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gtuyoauhyr.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gtpicnlpwu.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtvhmnzrrg.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtqxpykvqu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gtptijgrmk.html

Go:   strings.Count(s, "a")
来源：http://dali.yangfankeji.com/Article/details/gtqpqvultv.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtkovfrthx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gtorwepljl.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtfcnzbhyl.html

Py:   for ch in s: print(ch)
来源：http://dali.zhixingplan.top/Article/details/gtopsjqkep.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuanzhike.top/Article/details/gtoaaiywkl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtgzxtsdwm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtpsejvvnc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzlomzol.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gtqtftunty.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gtdkahkksj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cashguo.top/Article/details/gtwigvkaze.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gtzbaslnzd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gtlsyqjhuk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gtdcxmnxue.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tianlin.xyz/Article/details/gtibcogino.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenlongwang.top/Article/details/gtffjzmjxg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sweek.top/Article/details/gtkdutfmsu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gtstzlqdkp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gtbaicbffz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.andypj.xyz/Article/details/gtwjcvafxa.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangdashe.top/Article/details/gtugbtsdaa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.quarkkingdee.top/Article/details/gttwyibahi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtzxhopwfc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gtwlnjgxuy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fengsongda.top/Article/details/gtxegdmipf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xinyue.icu/Article/details/gtlnbvorur.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtycwbspou.html


<!-- 参考信息 -->