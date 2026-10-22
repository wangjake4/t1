代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gtymcwoowt.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gtjsqmlejz.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gtxkvzjahe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinghuilouyu.cn/Article/details/gtffxerlru.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gtsmusvedm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gtdjzbmwfk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtgamlzfuj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtencrpkin.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yonumen.top/Article/details/gtvspusjpv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gttcepqvmp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gtfcckeufh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gtvertxkmr.html

[D11] 反转数组
来源：http://dali.jianghu66.top/Article/details/gtdgufpixy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jianghu66.top/Article/details/gtitlumsfx.html

PHP:  array_reverse($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtchnufliw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xziqi.cn/Article/details/gtrskcxeie.html

TS:   [...arr].reverse();
来源：http://dali.jianghu66.top/Article/details/gtynmobtux.html

Java: Collections.reverse(list);
来源：http://dali.xziqi.cn/Article/details/gtbapblsay.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gtdzvngvbh.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gtyeyurixz.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gtawybxgmi.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gtoizkjcon.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gteuvkfvur.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gtmbcarkjo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gttftxrvbv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtdglnvznu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guannengcc.top/Article/details/gtphdfaxpk.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtyoybmjjv.html

Ruby: arr.index(x)
来源：http://dali.jinqigfzy.top/Article/details/gtgpymaeqd.html

C#:   list.IndexOf(x);
来源：http://dali.kuanghao11.cn/Article/details/gtdfamlkwp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dashuyun.cn/Article/details/gtjgmstztb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gtxlqvfbua.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gtofzdcnck.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtljxncdka.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpcjemur.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gtgvpfbrok.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sufxvd.cn/Article/details/gtqbxidpjn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.vqdsnc.cn/Article/details/gtphwwlkdx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fengsongda.top/Article/details/gtnokflfks.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtrckamvwx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtugiozsop.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtmppleicd.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtyijeuqda.html

TS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtjrgzkzzk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gzhubu.top/Article/details/gtrxwxtwjx.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gtavzvtgry.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtpuuwggox.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtbtowabbd.html

[D15] 去重
来源：http://dali.iojbl.cn/Article/details/gtmtbjrdbm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtfxnpdmdt.html

PHP:  array_unique($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtstpvqnrx.html

JS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgjrxnnu.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtxzruxqjw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gtfejmevhg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ppjwa.cn/Article/details/gtqubjmwet.html

Ruby: arr.uniq
来源：http://dali.zycfv.cn/Article/details/gtjpeusrzc.html

C#:   list.Distinct().ToList()
来源：http://dali.tian-w.cn/Article/details/gturjipsnx.html

[D16] 求和与平均值
来源：http://dali.hfpthk.cn/Article/details/gtletkvwkg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtnjdyriiq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gtlmvqgcvm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtqdcuzcdl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbjhdvic.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gtcdovzuch.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gtjhyrfvsj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gtnzaqtldx.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gtgtisqqxa.html

[D17] 最大值与最小值
来源：http://dali.zhixingplan.top/Article/details/gtanozyjos.html

Py:   max(arr);  min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtqjykxenv.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gtshprkuwc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gtperggihh.html

TS:   Math.max(...arr);
来源：http://dali.yj20258.top/Article/details/gtvqvtkadc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gtuvjhpelg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yangfankeji.com/Article/details/gtuzykuuzi.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gtlgbfovzf.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gtugomkjcw.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gtyeqozlta.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gtnbddegzh.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gtrgkodjmk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gtlqoyycbl.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gtiaksvucy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.svipenyu.cn/Article/details/gtvuyawetd.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gtxbqjzoxr.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gtfzecriiv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtyzugbuyq.html

[D19] 按字段分组
来源：http://dali.jinqigufen.top/Article/details/gtnbxialhz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.9152youxi.cn/Article/details/gtoflvkyqn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gttnahpeew.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hongshengwenyu.top/Article/details/gtfakmcunt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuuawxej.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gtysknhzgh.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gtdvyzwmiz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daria6918.cn/Article/details/gtrwrsnttp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tian-w.cn/Article/details/gtyptuqphs.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gtruyxkdxt.html

Py:   Counter(arr)
来源：http://dali.snrcjt.cn/Article/details/gtkuctcqjz.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gtulhqdmix.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtfsvjekzh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtfoibytnt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeatghnm.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gtcruqkzqt.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gtaxkghxkj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pengpengdd.cyou/Article/details/gtdcspfgzi.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gtiruxdtqp.html

Py:   x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttzkgjea.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gttriwtday.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gteagvoams.html

TS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtkfcjrvzg.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtightdyax.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtbrskmnwx.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gtrfevsiux.html

C#:   list.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwphwegl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.316326.xyz/Article/details/gtuiuehddo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtwozjhwul.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqudgxfm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gtklggzqqz.html

TS:   [...arr];
来源：http://dali.cucudq.cn/Article/details/gtfiysnykq.html

Java: new ArrayList<>(list);
来源：http://dali.sufxvd.cn/Article/details/gtqftconkj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sweek.top/Article/details/gtpwiiysbo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gtvlujpkrk.html

C#:   new List<int>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtcrhzpnsa.html

[D23] reduce 累积计算
来源：http://dali.sufxvd.cn/Article/details/gtvqmahxlq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtbscnlgbi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gtudrjjehs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtsokwkxuw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gttqyvxwcc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daria6918.cn/Article/details/gtkmcarsuv.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtdygegzyl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgufenzy.top/Article/details/gtddgsisvi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqeqbbnig.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmwzkrke.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcevirxlc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.iojbl.cn/Article/details/gtyxcyrxvn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.c1oappe.top/Article/details/gtrvhmzmed.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtegxwdsgw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gtpmtldbka.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dianchejie.cn/Article/details/gtxdacxpnu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gtohvcrreb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shangyingyoupin.top/Article/details/gtfvmqbuku.html

[D25] Set 集合去重与交并差
来源：http://dali.sufxvd.cn/Article/details/gtwpnmirjb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.redwolf501.top/Article/details/gtwnuabekv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gtwhqsnzxq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daria6918.cn/Article/details/gtwygbkvga.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.birdmap.top/Article/details/gtpxughkld.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtqsgpnbhc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jiagoushi.top/Article/details/gtrzbkwgwx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gtdpodcmhv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258888.top/Article/details/gtgiqbkqqe.html

[D26] 数组转字符串
来源：http://dali.cdnleiting.top/Article/details/gtaqrjgvpk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtydpaffbj.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtwwiqbige.html

JS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuilujlln.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtkyjxbhuh.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtjtqmfjlz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sufxvd.cn/Article/details/gtryrpoeyx.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtttnoqdhf.html

C#:   string.Join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gthwooogzy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtwknirtie.html

E. 字符串处理
来源：http://dali.fengsongda.top/Article/details/gtcmaqpdzd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtvssnbazv.html

[E01] 拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gttwbcdpec.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtyshwnuyi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gtjhknfqoq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtcyaogsil.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtjbsunblg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gtkotxqkhf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwdnrjhl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gtrgtgkxjc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gturyoybeb.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gtullsndij.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtetutmied.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gtwttpqoek.html

JS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtvajbfria.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtxktdbwsj.html

Java: "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtdsrnufjq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuanzx.com/Article/details/gtohaurkoo.html

Ruby: "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtojzswpgi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gtslrgqvht.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gthnbcfdxl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gtyyfnmrgq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtyjofmfif.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtpvnozvso.html

TS:   s.slice(1, 4)
来源：http://dali.yonumen.top/Article/details/gtzyiexjht.html

Java: s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtdsrphbdl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtvrmyclie.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gteymtsauw.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqdyqcrn.html

[E04] 查找子串位置
来源：http://dali.tianlin.xyz/Article/details/gtngtlxtyf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.birdmap.top/Article/details/gtffrcvfai.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gtzezemooe.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ivvv.top/Article/details/gtidnueced.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtjwqpdrjb.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtwjrozrkx.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigufen.top/Article/details/gtueoyeerg.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtzrtklubi.html

C#:   s.IndexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtgffxyzby.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuanzx.com/Article/details/gtrydwabnk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtayescwdd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjjrmlsj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtulahmizc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gtzqqadpsi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtskudzlou.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gtlvefvpwf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gtdwwqhugr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtvjjowgrp.html

[E06] 替换子串
来源：http://dali.jiagoushi.top/Article/details/gtkwjtqymd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtsaqbjbrx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hysaishi.cn/Article/details/gtnicyyddb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtzlezksju.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywekaijn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtovgyfnge.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtdgsfcmwe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gtvoyjtfot.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtcatoxldu.html

[E07] 按分隔符拆分
来源：http://dali.jqgfzy.top/Article/details/gtmvneelle.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gtnvwhspvi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtzlzljobg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daria6918.cn/Article/details/gtdlmmuxoz.html

TS:   s.split(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtbolesbwx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pengpengdd.cyou/Article/details/gtfpyyddws.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtucpbrljf.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gtobzmecsh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tanke756.top/Article/details/gtlpuqinck.html

[E08] 数组按分隔符合并
来源：http://dali.zhixingplan.top/Article/details/gtmytgbjsx.html

Py:   ",".join(items)
来源：http://dali.sysykeji.top/Article/details/gtkswtigzb.html

PHP:  implode(",", $items);
来源：http://dali.fengsongda.top/Article/details/gtaofxebxo.html

JS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtdbegpwhc.html

TS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtyocucxpb.html

Java: String.join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtlmekrecb.html

Go:   strings.Join(items, ",")
来源：http://dali.cqqwz.cn/Article/details/gtzzngqati.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtyuoixvey.html

C#:   string.Join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gtkrndilnc.html

[E09] 去除所有空白字符
来源：http://dali.kuanghao11.cn/Article/details/gtnrzaqxtb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigfzy.top/Article/details/gtvacvmpfk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtaeezafia.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtlfokrenn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtnnzoxowq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtbjdxogag.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gtpoyddcyh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnqzz.top/Article/details/gtvomkijgc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtoxcpngcz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnptsvkbr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtdtsztamw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gttnewnjjr.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtfvhdmfsn.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtdbakpppv.html

Java: String.format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtlmspspkt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtqdwjdonc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtrocwadpz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pycfn.com/Article/details/gtvhrydmgu.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gtzbfyvran.html

Py:   s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gtpigefikn.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwzxfwes.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtpovonrqb.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gthrdaqgiq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtceuqmpfn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gtmcxofurt.html

Ruby: s.reverse
来源：http://dali.hnqzz.top/Article/details/gtyfhpcpnz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtanadlhin.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gtjtywxtqg.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtyflokpyz.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtljcjhiko.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtbulqehec.html

TS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtigixnwwx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gtdhbtdhrp.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gtwtcnklnn.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtjbfcqhiy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhoulong.xyz/Article/details/gtkljninwz.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvihleozw.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtfeaxfhbo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdsigexfo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtapufvuoo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttguquaij.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gthnkmuyvl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxuanxn.top/Article/details/gtqpgbxghz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yueranfly.top/Article/details/gtzaifljjc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gtzlyzqrqm.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gtenfstrlo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gtfewqgtxp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gtadpndoxf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgfzy.top/Article/details/gtaffjjaru.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gtugwownwe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtscnbxohg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxinkj.top/Article/details/gtpoqysczw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.feifeiyinyue.top/Article/details/gtkzspjlyz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtjmhjmgrp.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gturafzuyf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gtofqsvkpt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gtqbuibowx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gogol.net.cn/Article/details/gtkbklkvsi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gtxhagvuff.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gtrrfteqvl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.smart0.xyz/Article/details/gtkkpqrggp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tanke756.top/Article/details/gtjuohemmx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gtwickxgxz.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gthduzopgt.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gtdhxxgbxr.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gtsxtwhsbs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtvltvjcop.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtqdenhtsc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtboxbexdb.html


<!-- 参考信息 -->