代发 wailian999

PHP:  sort($arr);
来源：http://dali.zycfv.cn/Article/details/gtkosqlsfc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xziqi.cn/Article/details/gtthsgvmsh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gtrmgfomuw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhiwuduotai.top/Article/details/gtnnbofrda.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtevrjtjaa.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gthzezxlaw.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gtzdgyxmcl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.316326.xyz/Article/details/gtsptndbyu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuanzhike.top/Article/details/gtuatfozio.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtzxznltoi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gthwwjutxv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gtgxqxydqe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gtycblniva.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gtuhvanvyk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gtwiyfwijf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.smart0.xyz/Article/details/gtrxlxndjp.html

[D11] 反转数组
来源：http://dali.9152youxi.cn/Article/details/gttkniimvd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258.top/Article/details/gtsjazfifj.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gtbrbkouvg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gzhubu.top/Article/details/gtolnvlcvj.html

TS:   [...arr].reverse();
来源：http://dali.snrcjt.cn/Article/details/gtefoxujqd.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gtuupgttpv.html

Go:   slices.Reverse(arr)
来源：http://dali.yuxming.cn/Article/details/gtaljmwtfp.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gtelrmuusy.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gtjmyxecue.html

[D12] 查找元素下标
来源：http://dali.gzhubu.top/Article/details/gtilpudhau.html

Py:   arr.index(x);  x in arr
来源：http://dali.sweek.top/Article/details/gtkgkktxge.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtchhhrzfk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtbpoaacnu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtxaueibla.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tianlin.xyz/Article/details/gtutmzoesk.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtjmxmgtxx.html

Ruby: arr.index(x)
来源：http://dali.jianghu66.top/Article/details/gtllfhtijk.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gtmwmuzgkk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.snrcjt.cn/Article/details/gtcupycptl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ehwqpu.com/Article/details/gtflcejjdh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gtxsjbcwok.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtfjmzsngt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtufkkunhs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtnrvnmgba.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gtbhtvqsce.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.mhx1999.top/Article/details/gtgeskjmqk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtqcnoieds.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gthxvlrtsc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tianlin.xyz/Article/details/gthwlecwtt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gtyzxxfryc.html

JS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gtfqnnclnc.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtosbrtnjk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtrrgrmchi.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gtzplvhayu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtutdfwtzv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gtywrnizob.html

[D15] 去重
来源：http://dali.chenlongwang.top/Article/details/gtnizjvoxp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtmuurisqy.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gtizegvarv.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtdmnioxfk.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtyyzmnuaj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daxiang520.top/Article/details/gtmxhyoslm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxuanxn.top/Article/details/gtegmxvzuq.html

Ruby: arr.uniq
来源：http://dali.c1oappe.top/Article/details/gtrthswlrn.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gtdeuihdvb.html

[D16] 求和与平均值
来源：http://dali.smart0.xyz/Article/details/gtmdwtfejh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtvtxktqki.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gtxcvtrfrp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtyqrmubrk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtvptssnyj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gtkgudhmqy.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gtpqnckljs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guowangkeji.top/Article/details/gtfozfvifb.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhengqikj.top/Article/details/gthguesbxd.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gtjphpeook.html

Py:   max(arr);  min(arr)
来源：http://dali.haohaochexian.top/Article/details/gtqlpsjksm.html

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gtyudjensu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gtxcgqltpd.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gtkhlcbxeh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.iojbl.cn/Article/details/gtriywqqpe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gtwcezwjbq.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gtqctwbivu.html

C#:   list.Max();  list.Min()
来源：http://dali.hnxiangtu.top/Article/details/gtbujglkhh.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gtagyukass.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gthbtvvqcb.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gtunntisnz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gtzdnwzzzv.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gtnazmqtoz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gtczqawmed.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gtwyuhqfxc.html

Ruby: nested.flatten
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdopyjpy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvneaijt.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpykzufdd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gtikugixqh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gtpylwkznp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhcqgkcf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gtokemwrms.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.redwolf501.top/Article/details/gtbvlxcaye.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gtgogageks.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dashuyun.cn/Article/details/gtrmzqrpzw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gtanxncryc.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gtmjickcyu.html

Py:   Counter(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtnzgxecfx.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjbuneqj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gtciuxjycz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gtlyiefgpo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gtviuhrkhu.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gtsvtatwik.html

Ruby: arr.tally
来源：http://dali.dianchejie.cn/Article/details/gtsaamefwh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gtsisuwszs.html

[D21] 判断是否包含某元素
来源：http://dali.xuetiantiany.cn/Article/details/gtmpbetocc.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtovcghgoo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj202588.top/Article/details/gtkhvqwavs.html

JS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtdkocciif.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtuuscxont.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gteughzwep.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtwqifccwk.html

Ruby: arr.include?(x)
来源：http://dali.havefunace.top/Article/details/gtrpqrwjge.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtpcjhiqam.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cashguo.top/Article/details/gttvfgvcmo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gtxmwrnxdb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dianchejie.cn/Article/details/gtdsljznka.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.mhx1999.top/Article/details/gtjzygkfbb.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gtznzmejmt.html

Java: new ArrayList<>(list);
来源：http://dali.hfpthk.cn/Article/details/gtpbdxxtod.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jiagoushi.top/Article/details/gtpbewlihy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangshuangyany.cn/Article/details/gtaipvlmgs.html

C#:   new List<int>(list);
来源：http://dali.jqgfzy.top/Article/details/gtyqezkvyd.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gtnsmabydh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtvykrltif.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gtkujaonlp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gtgokilbvm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtrlfqhobi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhiwuduotai.top/Article/details/gteroggfhy.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtkuyylaoc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gthvnsuqyb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yongpay.top/Article/details/gtzsoubwce.html

[D24] 字典 / Map 基本操作
来源：http://dali.xinyue.icu/Article/details/gtctkgypfy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gtdbdtfwld.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sweek.top/Article/details/gtqvvngktl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gtszruerlp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.andypj.xyz/Article/details/gteyuwvhhv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhoulong.xyz/Article/details/gtidahsvah.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gogol.net.cn/Article/details/gtyjlarkhy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gtxgdufywa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.vqdsnc.cn/Article/details/gtgntrrhot.html

[D25] Set 集合去重与交并差
来源：http://dali.tianlin.xyz/Article/details/gtuggreaek.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gtduhzxhpx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.iojbl.cn/Article/details/gtyechiibs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gtrrsuqurw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aibaodan.cn/Article/details/gthifarfnn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtegoqczzl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gtnaphelki.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dianchejie.cn/Article/details/gtwmiqluuv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtqdhhrzbk.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gtgwkxrnhy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ivvv.top/Article/details/gtolfoswjk.html

PHP:  implode(", ", $arr);
来源：http://dali.yueranfly.top/Article/details/gtajkajqiq.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtcahykzla.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtjnwfpxxe.html

Java: String.join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtlxeizdsq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gtassvbrzc.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtukobuufd.html

C#:   string.Join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtywpsdtbg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtozbtmput.html

E. 字符串处理
来源：http://dali.zhengqikj.top/Article/details/gtfvwzgjjr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhtpovpi.html

[E01] 拼接字符串
来源：http://dali.yonumen.top/Article/details/gthehqdhga.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ppjwa.cn/Article/details/gtodpjmjvy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hfpthk.cn/Article/details/gtatpiycqb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtkfdmjyru.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gtdzwsibhi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhoulong.xyz/Article/details/gtrwatncrp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuxming.cn/Article/details/gtucgbumdp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgfzy.top/Article/details/gtrnnudnik.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtngdaugfe.html

[E02] 重复字符串
来源：http://dali.nanxinkj.top/Article/details/gtndmysqnr.html

Py:   "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gtbnrrxviv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaskqisjc.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtjecwqqvx.html

TS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtabzgbnrv.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtzsgxzpmt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pycfn.com/Article/details/gtjikrvbsb.html

Ruby: "ab" * 3
来源：http://dali.cheryme.top/Article/details/gthspaonmq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtohdbijqi.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gthlhmxtvu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gtulyrntnu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtihnjqsyf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtnrxfzjqh.html

TS:   s.slice(1, 4)
来源：http://dali.meibo888.top/Article/details/gtcbbvaldc.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtchjrsdks.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gteiesstlt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daxiang520.top/Article/details/gtuanrbego.html

C#:   s.Substring(1, 3)
来源：http://dali.birdmap.top/Article/details/gtmujoejyt.html

[E04] 查找子串位置
来源：http://dali.yj20258.top/Article/details/gtylpqqdie.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gzhubu.top/Article/details/gtjfdnvjya.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gtxharfdau.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gtqvogdusg.html

TS:   s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtlojjmyhd.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtrskicvqm.html

Go:   strings.Index(s, "x")
来源：http://dali.zhengqikj.top/Article/details/gtxujklfop.html

Ruby: s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtlqifvrdp.html

C#:   s.IndexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtuhvnljej.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvwgdtjx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gtoacgrkzw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tanke756.top/Article/details/gtqbsgafxt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gthrxchtge.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gtoxeeqlee.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gtxdcmbhmi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ydzc1.top/Article/details/gtgspdxswb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guowangkeji.top/Article/details/gtcmvizndr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtcnqdliri.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gtanjhuaqw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtujmbrkdx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gtslwhbbrc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtzsvdcafa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtwqligtew.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gteneodwor.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtdznkzcoe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtxirecsbk.html

C#:   s.Replace("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtzkfkxhll.html

[E07] 按分隔符拆分
来源：http://dali.cqqwz.cn/Article/details/gtsqmdieyk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuetiantiany.cn/Article/details/gtowrcfsmj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtzstowbjj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gtjaxoikig.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gtytqedceo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gtwzjfmhyi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxuanxn.top/Article/details/gthyvvkqii.html

Ruby: s.split(",");  s.split
来源：http://dali.zycfv.cn/Article/details/gtnanivido.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nwbrower.top/Article/details/gtsovvsazi.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gtisokflvt.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavpphqlf.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gtcydtslac.html

JS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtzmqxrefg.html

TS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gthwbbmpco.html

Java: String.join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gtcsykdsjx.html

Go:   strings.Join(items, ",")
来源：http://dali.yongpay.top/Article/details/gtdrazphnf.html

Ruby: items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtcgcwfemd.html

C#:   string.Join(",", items)
来源：http://dali.yongpay.top/Article/details/gthhnfcgmr.html

[E09] 去除所有空白字符
来源：http://dali.ivvv.top/Article/details/gttqsvcwip.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gtkfzcnzfd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtidmkslcx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gthrejixax.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtlwbqtffx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gtjnlbqxlv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenjidiqi.icu/Article/details/gthlvrzlhm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtergnksme.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gtltcwtzbl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pengpengdd.cyou/Article/details/gtssuupgfz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtfyjgdksq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gtsoqussom.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtaueghzpg.html

TS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtyyedchxr.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtlnxpdbvd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtqvofiyma.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtvkcfihsj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gtejakonfd.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gtfsvaujvk.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtcqfksrpt.html

PHP:  strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtjuyfjmrp.html

JS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtsvvalubd.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtwmouubmi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtyggiugwk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtmjdmniuh.html

Ruby: s.reverse
来源：http://dali.yj20258.top/Article/details/gtksmkgyab.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtvwvrnfse.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gtfezyqgku.html

Py:   s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtmyqgtubr.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gtblmyexfo.html

JS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gttqamohva.html

TS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtysuarswf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.kuanghao11.cn/Article/details/gtfdqhadgy.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gtdfgctujy.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtngwopswa.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenzaomai.com/Article/details/gtihquhmvl.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtkjtegqfm.html

Py:   for ch in s: print(ch)
来源：http://dali.sysykeji.top/Article/details/gthfzppjfi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yanxiufei.cn/Article/details/gtwpfkyvnq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtkvubmeog.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtehmmpnaz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwrrmyvh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aibaodan.cn/Article/details/gtgyzthjpv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.quarkkingdee.top/Article/details/gtnudgfpcv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtsyhuxfhb.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gtmnctdjcv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dashuyun.cn/Article/details/gtrsexwlic.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohkngnfc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gzhubu.top/Article/details/gtjurybvyw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.haohaochexian.top/Article/details/gtrkkfucjw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gtrcbsyvci.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yonumen.top/Article/details/gtdhecakwr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hammf.cn/Article/details/gtcthpzruh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gtnqzaudov.html

[E15] HTML 转义 / 反转义
来源：http://dali.hysaishi.cn/Article/details/gtqkqclqvl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sufxvd.cn/Article/details/gtkwacpflm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.mhx1999.top/Article/details/gtkxesyela.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pycfn.com/Article/details/gtzymqfkij.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gaohongyu789.top/Article/details/gtgeriqfrr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gtxivwtbhd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtyhafndod.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxtabwkm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gtyodennwi.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtflornkro.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gtssuzxpbs.html


<!-- 参考信息 -->