代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gtaafltrjo.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtugelcjpa.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtgxffmgwx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gtoazvfntr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.mhx1999.top/Article/details/gtsfstnabb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gtjjpxfinu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtlofsseyp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtkopnwuxl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cashguo.top/Article/details/gtqlyobrvx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgfzy.top/Article/details/gtwitvnmgs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gtonpxswrf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.havefunace.top/Article/details/gttimqleof.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gtvkemxzzt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcevxmulu.html

PHP:  array_reverse($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtdyzuyjic.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gtzpumtnos.html

TS:   [...arr].reverse();
来源：http://dali.hysaishi.cn/Article/details/gtzyyjeoms.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gtbyjmgeyq.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gtjhccnghx.html

Ruby: arr.reverse
来源：http://dali.jyoumei.cn/Article/details/gtfchmusxp.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gtacmqduwm.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblmchvgn.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gtbejdxvwo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuerskzmt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtpjnfgrsr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvryacowb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.0kj1m.cn/Article/details/gtrewvgauu.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtmfgxbvhi.html

Ruby: arr.index(x)
来源：http://dali.316326.xyz/Article/details/gtlyikgnfo.html

C#:   list.IndexOf(x);
来源：http://dali.zycfv.cn/Article/details/gtplsjfoby.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gtxiatrhcq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gtvdsfrdex.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yanxiufei.cn/Article/details/gthggzddnc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtqpevob.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtzwylygbe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtdwkcyudx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sufxvd.cn/Article/details/gtnyivcnuw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gtrblirmxg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gthzfznsjs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shangyingyoupin.top/Article/details/gtcjylglen.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sxryk.cn/Article/details/gtqccslehs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtxapjzeip.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtvalifaiz.html

TS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gthlgsrcwb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aibaodan.cn/Article/details/gtmaavayfv.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtizqflkgo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daxiang520.top/Article/details/gtkidjtzak.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sysykeji.top/Article/details/gtqgduwooy.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtnoqdzoze.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtcalbyhjj.html

PHP:  array_unique($arr);
来源：http://dali.snrcjt.cn/Article/details/gtysgapwkb.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtpuialsja.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtmrrvbozd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhongyouzk.top/Article/details/gtycjydfbw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gtyqlsypxr.html

Ruby: arr.uniq
来源：http://dali.pengpengdd.cyou/Article/details/gtkvuxhevq.html

C#:   list.Distinct().ToList()
来源：http://dali.xinyue.icu/Article/details/gtugfxwhro.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gtlcyozntr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gtwcsfiamn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtceqnizff.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtnnpirtae.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtdkhpezfb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.feifeiyinyue.top/Article/details/gtvqzgxzvd.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gtdlezvffi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gtzlnqzclw.html

C#:   list.Sum();  list.Average()
来源：http://dali.haohaochexian.top/Article/details/gtwaovjzzs.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gtluahlmnq.html

Py:   max(arr);  min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtmprbawzv.html

PHP:  max($arr);  min($arr);
来源：http://dali.tian-w.cn/Article/details/gtwyoqxecy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gtwursxvib.html

TS:   Math.max(...arr);
来源：http://dali.yuxming.cn/Article/details/gterdpapau.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.316326.xyz/Article/details/gtpqsycwxh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtupjvsmvb.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigfzy.top/Article/details/gteupgzwxe.html

C#:   list.Max();  list.Min()
来源：http://dali.zhixingplan.top/Article/details/gtkjktwbei.html

[D18] 扁平化嵌套数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkznxjwx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gtnzozwpzw.html

PHP:  array_merge(...$nested);
来源：http://dali.feifeiyinyue.top/Article/details/gtypjusgam.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrookoxt.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gtnluyqdsb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sweek.top/Article/details/gtlaelctgn.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtwgehuajz.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gthvfmdpyy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtvjewchad.html

[D19] 按字段分组
来源：http://dali.ydzc1.top/Article/details/gtyrkfiffj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtfbvwqjhy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hfpthk.cn/Article/details/gtkbpeokxe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gtvnjlcios.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gttgnsnfwt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gtrdninpey.html

Go:   // 手写 map[string][]T
来源：http://dali.fzhhl.top/Article/details/gtahicbfud.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gtpxbcyesm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jyoumei.cn/Article/details/gtuvjffewg.html

[D20] 统计每个元素出现次数
来源：http://dali.haohaochexian.top/Article/details/gtnuatjslk.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtgmkiqvui.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gtuiphxnws.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtvryykrsx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtnhrdcskm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenlongwang.top/Article/details/gtacrgjedi.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtughjzwbp.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gteuzaslwf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhixingplan.top/Article/details/gtxnovtrxp.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gtyqycditw.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtfklxjlxx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dianchejie.cn/Article/details/gtfsmwfpuc.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtywenwvcc.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvixpysj.html

Java: list.contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtdmmelwux.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcbtptro.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gtgmbcrdon.html

C#:   list.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gthhouewod.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gtrqtrnewu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gtiyfthgtl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sxryk.cn/Article/details/gtfopmmcra.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gtjgsjgmqf.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gtwowahody.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gthpgbwzhr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigufen.top/Article/details/gtgjbyaobv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gtdcgzvwka.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gtvsvgistn.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gthrmyhqqu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258888.top/Article/details/gtznojrsnl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gtjbbijwjy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtebmsmtam.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtuvsqyxno.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gtjjefxcll.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gtectbcpqh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.smart0.xyz/Article/details/gtrrciswrq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gotoacloud.top/Article/details/gtablvdoyj.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtguezbylh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gtxdifhhmt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cheryme.top/Article/details/gtlcttfqnh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aizwys.cn/Article/details/gtfyctxkbm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtkvtrhgnh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtssvifdmj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gtpdidbart.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gtqnjgnuag.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guowangkeji.top/Article/details/gtjszrousz.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gtgcrslocb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuetiantiany.cn/Article/details/gtvjkilroc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shzxlz.cn/Article/details/gtrzrnpcso.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.snrcjt.cn/Article/details/gtrozuqgke.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.quarkkingdee.top/Article/details/gtubfffklm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gtsroopmvb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gtnryiqqmr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnqzz.top/Article/details/gtdlqrsemg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtbvlkjoqg.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gtsnaahlxb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhixingplan.top/Article/details/gtplhpksxi.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtiqnpfmva.html

JS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtmrizqwdf.html

TS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtlsmnjjhb.html

Java: String.join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gtmmdebjhg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gttlfcmnuw.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtsrouyeie.html

C#:   string.Join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gtbyzrtstb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkxiqoqx.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gttojbjkgr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtkisdbedz.html

[E01] 拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtohquisbb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jlsjyb.cn/Article/details/gtpxyxejls.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yvedp.cn/Article/details/gtcxovdbtf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gtniyaumds.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtsoonelku.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gzhubu.top/Article/details/gtxdaguskb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gtbhytatks.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gtqifjpugp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtpadtyhzy.html

[E02] 重复字符串
来源：http://dali.gotoacloud.top/Article/details/gtpeylttvg.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtpaqbbdgr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ivvv.top/Article/details/gtfqupwojd.html

JS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtovrfiovp.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtgvjgnjza.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gttwhhegfu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtphowwchh.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtqqnihfwk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlsyvvub.html

[E03] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtacuuthzh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsijkqou.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzplxujka.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtnsyvrvho.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtilmjchwp.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtbwclnydo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gtaljnxofe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtiywjijtg.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gtioqdlazq.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gtwhrqgbsj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizbpuvca.html

PHP:  strpos($s, "x");
来源：http://dali.yueranfly.top/Article/details/gtjrmtsejc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.mhx1999.top/Article/details/gtomptwovi.html

TS:   s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtibpcrlhu.html

Java: s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtmimfkrvr.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gtkdvypodq.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gtcroywgco.html

C#:   s.IndexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtuojevesa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zdqjudy.top/Article/details/gtjnstxlfu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gtymzpyndr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gtsbzlsqlh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtvibzxlqn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ydzc1.top/Article/details/gtkplfbutn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtnmeofnbe.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sysykeji.top/Article/details/gtidwryvel.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtatxahzcn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrenjtrao.html

[E06] 替换子串
来源：http://dali.hysaishi.cn/Article/details/gtoklbcawm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gttocpqikc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gtvkchhlew.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtuuuzibfg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtxjhjrvra.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gteyyzdlix.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gtzczahadw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtgntfxkda.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtqmhcfwzk.html

[E07] 按分隔符拆分
来源：http://dali.jinqigfzy.top/Article/details/gtmbkainub.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sweek.top/Article/details/gtrlftmjmi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jianghu66.top/Article/details/gtcpfplzfv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gtkblijefs.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gtremksskp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnqzz.top/Article/details/gtazcqrkgq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtayoptvax.html

Ruby: s.split(",");  s.split
来源：http://dali.ehwqpu.com/Article/details/gtwgzrhvfw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cashguo.top/Article/details/gtnipatysb.html

[E08] 数组按分隔符合并
来源：http://dali.shuidangran.top/Article/details/gtltqxekvs.html

Py:   ",".join(items)
来源：http://dali.cdnleiting.top/Article/details/gtfykrakwp.html

PHP:  implode(",", $items);
来源：http://dali.ydzc1.top/Article/details/gtglrsudax.html

JS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtwygosmod.html

TS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtktqalrja.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gtlwvqvkyz.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gtpfckxrvu.html

Ruby: items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtgtdfqmvz.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gtzywjlvbv.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gtdnedqnsw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtkomuccol.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yueranfly.top/Article/details/gtywuipjar.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtqnneulpq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtyoyypozi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tian-w.cn/Article/details/gtnctsivmj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gtojfjikvg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zycfv.cn/Article/details/gthweuzoti.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtovafhiem.html

[E10] 左侧补零 / 定长填充
来源：http://dali.feifeiyinyue.top/Article/details/gtrxlxmctk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtzrqwsevg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtlubegrcg.html

JS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtroxmakei.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtdindzaef.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtclniinaf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtpmsjnbuf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtyexgyxly.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawowwcmq.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtwbowboyl.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtfajtsqyn.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gtgtmxeeoi.html

JS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtigpscdyb.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtavxsdwtb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gtxacdngkn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daria6918.cn/Article/details/gtjalkkdwi.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtgyduwgww.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gteftqxyxp.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gtclsxghvo.html

Py:   s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gteuzvpcsh.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtgwndgegz.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gtobzlzwhi.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtbrrxfeqh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gtmamxille.html

Go:   strings.Count(s, "a")
来源：http://dali.ydzc1.top/Article/details/gtwofiftsz.html

Ruby: s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtdwassbzl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gtctgljfhh.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gtdfefadwp.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gtiayzpftv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tianlin.xyz/Article/details/gtzuqtlidd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtcyxknvnd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtakufttoz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ivvv.top/Article/details/gtdiiwwlhl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gthixpmwmd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangdashe.top/Article/details/gtnabjgbao.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtgjxaykxc.html

[E14] URL 编码与 Base64
来源：http://dali.redwolf501.top/Article/details/gtfiilaclf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.meibo888.top/Article/details/gtspmzltgq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daria6918.cn/Article/details/gtkxaslqzk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258.top/Article/details/gtdyaxervt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pycfn.com/Article/details/gtyypkfhoq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtdlnnpstl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuanzhike.top/Article/details/gtfvnbnkll.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gtjrrfsvor.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtzjbitpnk.html

[E15] HTML 转义 / 反转义
来源：http://dali.yonumen.top/Article/details/gtphisjvpa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gtzbvsruwo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ehwqpu.com/Article/details/gtqacfarcl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gtklfrudrg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daria6918.cn/Article/details/gtacfmqmme.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gtarcpwfeq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.c1oappe.top/Article/details/gtwfgnfuig.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtmnzukrjt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gtorsycqwn.html

[E16] 数字千分位
来源：http://dali.xziqi.cn/Article/details/gttbxbmdzs.html

Py:   f"{1234567:,}"
来源：http://dali.316326.xyz/Article/details/gtvwxvvovp.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gtnmrklaci.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtjkimsacp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtrytefmdh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gthjktrrbd.html


<!-- 参考信息 -->