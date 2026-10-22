代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gtaitpftkx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xinyue.icu/Article/details/gtltqfrrmu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tian-w.cn/Article/details/gtxkrxxnvy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gtocewcbpq.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gttglarply.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ppjwa.cn/Article/details/gtsvhxuleu.html

PHP:  array_reverse($arr);
来源：http://dali.zhengqikj.top/Article/details/gtjvgcptza.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgufenzy.top/Article/details/gtlturluti.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gtbuanhvka.html

Java: Collections.reverse(list);
来源：http://dali.dashuyun.cn/Article/details/gthounwnmh.html

Go:   slices.Reverse(arr)
来源：http://dali.gotoacloud.top/Article/details/gtilmtfdlf.html

Ruby: arr.reverse
来源：http://dali.redwolf501.top/Article/details/gtblamnyme.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gtjmigwjbu.html

[D12] 查找元素下标
来源：http://dali.fzhhl.top/Article/details/gtmnrxwnee.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gtugjulpar.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtkcimdzxs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtokptmsij.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtuuadnyfa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gtcydnqrot.html

Go:   slices.Index(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtvadnwtme.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtcwmqdtjr.html

C#:   list.IndexOf(x);
来源：http://dali.yangfankeji.com/Article/details/gtklxoohcv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtfeevxxza.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gtxzdgjlft.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gtgwjzzzmc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gtgijnften.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gteyyigdwz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sufxvd.cn/Article/details/gteqnstcln.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtckaisewb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhoulong.xyz/Article/details/gtmdlirzis.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.smart0.xyz/Article/details/gtllgypbsj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cdnleiting.top/Article/details/gtjrshvswi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gtrikcrukg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gtaofnxuns.html

JS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtsjzljata.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtsgrzrvfc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gtnwrftgbb.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtrspiyums.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.havefunace.top/Article/details/gtrmxeekdd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtamtlpagy.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gtzfyuautp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtpcmnoibk.html

PHP:  array_unique($arr);
来源：http://dali.birdmap.top/Article/details/gtgpmvlkqj.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtifruwdma.html

TS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcotdzpis.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tianlin.xyz/Article/details/gtartcijkz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hfpthk.cn/Article/details/gtlreorhth.html

Ruby: arr.uniq
来源：http://dali.ivvv.top/Article/details/gtmkwxwdta.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtcawztfqx.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gtywwyppuy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtmzlboygd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yvedp.cn/Article/details/gtbemmfzpj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gthtnmlipo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gttkgdzoqb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpomsdsc.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gtuqmrjdfq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtwvtfhjop.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gtxrkvmhot.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtfquxmkot.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtinvvlgoa.html

PHP:  max($arr);  min($arr);
来源：http://dali.shzxlz.cn/Article/details/gtjbxrlxpe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtuezmqmfk.html

TS:   Math.max(...arr);
来源：http://dali.haohaochexian.top/Article/details/gtjulkdcfw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gtouomanhp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gtgtvenozo.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gtfzekokyg.html

C#:   list.Max();  list.Min()
来源：http://dali.daria6918.cn/Article/details/gtqpsoqovp.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gtinxrycxr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gtgtepgtib.html

PHP:  array_merge(...$nested);
来源：http://dali.jiagoushi.top/Article/details/gtogfttvec.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gaohongyu789.top/Article/details/gtvwgxoinp.html

TS:   nested.flat();
来源：http://dali.nanxuanxn.top/Article/details/gtwutpqzji.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sysykeji.top/Article/details/gtezbdsljn.html

Go:   // 手写双层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxfhzrzx.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gtxrszfjgb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtbgyzzxuv.html

[D19] 按字段分组
来源：http://dali.ydzc1.top/Article/details/gttvayizur.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnqzz.top/Article/details/gtuyzaxqtr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gtbyaludaw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ehwqpu.com/Article/details/gtuolaghjx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtbtxmzogy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gtwahhiopz.html

Go:   // 手写 map[string][]T
来源：http://dali.jiagoushi.top/Article/details/gtokotpjuw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cucudq.cn/Article/details/gtxqypbrjb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gtltkmokat.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gttxsfvzbx.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpmcvndq.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gtgwmjvfdk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtojohpkle.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqblrrljt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gtytpjbwnv.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gtptwgrsli.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gtibazohgb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gtavxikppp.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gtsmmivtgq.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gthljvrruj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gtkiojqwml.html

JS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtzrtpimzd.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gttfsjmgag.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gthcijipwo.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gttduumkcb.html

Ruby: arr.include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gthbdjzrqs.html

C#:   list.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtyqezrbtp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gtprcgwjwn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gtuqpukrhv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangshuangyany.cn/Article/details/gtiukmfdpy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gtgygahbsj.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gtklixkxfa.html

Java: new ArrayList<>(list);
来源：http://dali.yongpay.top/Article/details/gtplwfqyuo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gtrpyppsdu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gtgxflfcgv.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gtlnwgwowc.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gtqcztusix.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aibaodan.cn/Article/details/gtdusgobpm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gtsbqlfabm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtthjrztql.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtarkekpde.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gtkrgeohsb.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtoobtdlvy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gtuyjuharx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sxryk.cn/Article/details/gtnyqledyv.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gtznkwjerh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dashuyun.cn/Article/details/gteawthkjc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gtitvpyjsl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sysykeji.top/Article/details/gtgehahtgr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.meibo888.top/Article/details/gtlyzsxhse.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gzhubu.top/Article/details/gtytyxpkgz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zdqjudy.top/Article/details/gtkguofygs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yvedp.cn/Article/details/gtwdafajoo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhiwuduotai.top/Article/details/gtjuouatfq.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gtqmlvnitc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj202588.top/Article/details/gtdtyttysw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gtndrncyqn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gtjmetdnud.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gtwfwyledn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.0kj1m.cn/Article/details/gtgdfvmmok.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunmiccnu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gtixtkdmgg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtgriiorlz.html

[D26] 数组转字符串
来源：http://dali.hnqzz.top/Article/details/gtfghskseu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gtcdpwxopo.html

PHP:  implode(", ", $arr);
来源：http://dali.xylfe.cn/Article/details/gtimeehqmf.html

JS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtbesgyxpv.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtoniwagty.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtiuigdqvi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gtkjlgycbl.html

Ruby: arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtmgxiaukb.html

C#:   string.Join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gtkafydorm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtktbpviox.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gtwbkcrqnv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtwxapfmnz.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtguwdmgjm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gtwnmapyrp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hfpthk.cn/Article/details/gtujbdqlcl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtksvzjajo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtgjvlplfu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gtsruzxfxw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fzhhl.top/Article/details/gtxwbkqwux.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gttusmqnsn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tanke756.top/Article/details/gtjpmnrgqk.html

[E02] 重复字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocrskxtl.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtfnrvhffb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuanzx.com/Article/details/gtahmmgaul.html

JS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtdrcmpsqp.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtbxtimkwp.html

Java: "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtlmaiuuuh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ybcxt.top/Article/details/gtmmhytlsg.html

Ruby: "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gtsupvzwye.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gthzhsekrn.html

[E03] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtmguaqhmc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guowangkeji.top/Article/details/gtblluffgk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplhasqyw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtmhoxzyxk.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtdjzutxib.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtosixygpa.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gtgmmnodpc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.0kj1m.cn/Article/details/gtnrtuszzq.html

C#:   s.Substring(1, 3)
来源：http://dali.hfpthk.cn/Article/details/gtdotinvbx.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gtowfoajlq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtgohjmuop.html

PHP:  strpos($s, "x");
来源：http://dali.shzxlz.cn/Article/details/gttsfmlffm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhongyouzk.top/Article/details/gtjowzlrsi.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtsehqpjua.html

Java: s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtylsmralg.html

Go:   strings.Index(s, "x")
来源：http://dali.svipenyu.cn/Article/details/gtrodkbrev.html

Ruby: s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtknjtyfbj.html

C#:   s.IndexOf("x")
来源：http://dali.havefunace.top/Article/details/gtsipszecq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfavactuf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtappmyxku.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gtxpmsusgp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtucatdccj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxinkj.top/Article/details/gtgvmxpfyw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtmbxpszrp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xziqi.cn/Article/details/gtlvreryzt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigufen.top/Article/details/gtcqlrcxqm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cashguo.top/Article/details/gtsblsafzm.html

[E06] 替换子串
来源：http://dali.gaohongyu789.top/Article/details/gtpgfnfahn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtjcnwtj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncklaumr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtydjicdnv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtlxeqhyqg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtkooryuce.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtwzzagwil.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtjqckpahk.html

C#:   s.Replace("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtlcnxqfim.html

[E07] 按分隔符拆分
来源：http://dali.shzxlz.cn/Article/details/gtmwddfbjw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gtangyocvu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj202588.top/Article/details/gtiszdaopz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aibaodan.cn/Article/details/gtaxufqwpd.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gtwzvvrtbo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gtednzvqnd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yanxiufei.cn/Article/details/gttxhngwlc.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gtyuhsagbp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gtvddmhndt.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gtfqvnerxy.html

Py:   ",".join(items)
来源：http://dali.wangdashe.top/Article/details/gtghtjiydy.html

PHP:  implode(",", $items);
来源：http://dali.dashuyun.cn/Article/details/gtpvsburfj.html

JS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gttvdeenrz.html

TS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtyhqekqzn.html

Java: String.join(",", items)
来源：http://dali.birdmap.top/Article/details/gtlrkezgfy.html

Go:   strings.Join(items, ",")
来源：http://dali.havefunace.top/Article/details/gtsetlujtt.html

Ruby: items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtgfesisvl.html

C#:   string.Join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtislbthvq.html

[E09] 去除所有空白字符
来源：http://dali.hysaishi.cn/Article/details/gtcdtrhbqg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gtxtjwghyl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gtrqusalvc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtxkgesqje.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtncgntyii.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtkeqqygft.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xinyue.icu/Article/details/gtvkeerkpt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.c1oappe.top/Article/details/gtesdvkzxg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zycfv.cn/Article/details/gtxsaqnppv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gtugswxbdg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtaotkwwty.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gtowtuutpb.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtjdmpnphy.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtjcipiwxm.html

Java: String.format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gttzexxlru.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltscbikp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtmtafnyja.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gtmvmhdtrs.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtdvskfovg.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtpgqvjjtg.html

PHP:  strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtwcvgbjhg.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtjqiwynyn.html

TS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtmzbdmrcj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tanke756.top/Article/details/gtwtmcqfbb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ppjwa.cn/Article/details/gtsucwtofx.html

Ruby: s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtgykwlqls.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gthugsbbqv.html

[E12] 统计某字符出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gtsqxqyfib.html

Py:   s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtfcyfsnzx.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gtcxpeeuer.html

JS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtddjdrjlw.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gttglwxouk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gtdgmltvgl.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gtjvsbctmm.html

Ruby: s.count("a")
来源：http://dali.havefunace.top/Article/details/gtbbvkfrnn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gtpedosiro.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gtgpmdyunr.html

Py:   for ch in s: print(ch)
来源：http://dali.yanxiufei.cn/Article/details/gtwqbqizsv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gtziezpsue.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtmhkanpbg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtoulmtjfp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hammf.cn/Article/details/gtyhnfaoue.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxuanxn.top/Article/details/gtlyaenvab.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gtqpagfivc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pycfn.com/Article/details/gtmuubmili.html

[E14] URL 编码与 Base64
来源：http://dali.hfpthk.cn/Article/details/gtcshwasjd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gtcfaqfrwy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsawmyber.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gtjbprmzud.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gtecvxwlvy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtmbrecftj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gtjljllwnd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gtnyjrnjik.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gtodjruput.html

[E15] HTML 转义 / 反转义
来源：http://dali.zdqjudy.top/Article/details/gttyrobeug.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aibaodan.cn/Article/details/gtsmqwkdgv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yvedp.cn/Article/details/gtffowtpor.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuxming.cn/Article/details/gtyaxplxvf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gtroxkoxwm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gtzyoxeech.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtvuergdvn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gtujzgznuq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gtvuxkiwud.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtgkfhwzob.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttblhqrsh.html

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gtmwvxojar.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxitozjah.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtktixqnte.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtesuhcvco.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gtsmlfiasw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gtfxntlsic.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gtcvfqkatc.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gtfrvkgfkm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gtmsisbpvy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gtblmxoizn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtvkspyqeg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtmbkufkyw.html


<!-- 参考信息 -->