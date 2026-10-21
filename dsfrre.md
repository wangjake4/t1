代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.haohaochexian.top/Article/details/gtjqmyvvlg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gtbkzimfee.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gteiabqqrm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gtndknubcx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guannengcc.top/Article/details/gtjblepmgb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.c1oappe.top/Article/details/gtttpumrxv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yvedp.cn/Article/details/gthxcjhoxy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gtztnrcmoo.html

[D11] 反转数组
来源：http://dali.shuidangran.top/Article/details/gtqinfdqxt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.haohaochexian.top/Article/details/gtjuwnkpce.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtuhacrkgu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gthfkdobre.html

TS:   [...arr].reverse();
来源：http://dali.hysaishi.cn/Article/details/gtljtiiqmh.html

Java: Collections.reverse(list);
来源：http://dali.tian-w.cn/Article/details/gtwngawady.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gtyicnvorm.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtkthfuzkr.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gtlpgmhbep.html

[D12] 查找元素下标
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrxghfxm.html

Py:   arr.index(x);  x in arr
来源：http://dali.gotoacloud.top/Article/details/gtaknqnfea.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zycfv.cn/Article/details/gtovacwbfn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlqqobji.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gtjcwjpoye.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xinyue.icu/Article/details/gtwjijoilr.html

Go:   slices.Index(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtuyqdtxpf.html

Ruby: arr.index(x)
来源：http://dali.meibo888.top/Article/details/gtsnvavbnw.html

C#:   list.IndexOf(x);
来源：http://dali.nanxuanxn.top/Article/details/gtzihdcupc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhixingplan.top/Article/details/gtwpyrxctb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gtzcgsztdh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yongpay.top/Article/details/gtjysvklsp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtshoguwpc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtpbuzcuxu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gtofotpztn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlnvxouw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gtupvqiawm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.c1oappe.top/Article/details/gtyiqnqozl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdopgysa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gteqaamsjo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtceayrcdd.html

JS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtqciscqzm.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtfosrqxsk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ivvv.top/Article/details/gtufyyvled.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gttkdoxabe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtquumxgnz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtrzrjtrxu.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gtqrbqyqbi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtpahxxaqs.html

PHP:  array_unique($arr);
来源：http://dali.yvedp.cn/Article/details/gtjxjublaw.html

JS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtfqnmlcew.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtmyqvwmvc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenlongwang.top/Article/details/gtshsmpctm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gtzstgwsdz.html

Ruby: arr.uniq
来源：http://dali.mhx1999.top/Article/details/gteuxjucxv.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gtxsevbyoy.html

[D16] 求和与平均值
来源：http://dali.c1oappe.top/Article/details/gtnzuccaho.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gttdwctzky.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkyxjusa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gtvhtmjsor.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtkkovyrwn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jlsjyb.cn/Article/details/gtzwcdvpqr.html

Go:   // 手写循环累加
来源：http://dali.ppjwa.cn/Article/details/gtslwzsbgk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxinkj.top/Article/details/gtbttrahrn.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gtcymlbnmp.html

[D17] 最大值与最小值
来源：http://dali.ehwqpu.com/Article/details/gtpcsozvwj.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gthlxswhdy.html

PHP:  max($arr);  min($arr);
来源：http://dali.316326.xyz/Article/details/gtejhzxbez.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgfzy.top/Article/details/gtryrzwuiq.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gtxlypjknp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigfzy.top/Article/details/gtefmnpigi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtvjyqvsav.html

Ruby: arr.max;  arr.min
来源：http://dali.svipenyu.cn/Article/details/gtzughncor.html

C#:   list.Max();  list.Min()
来源：http://dali.zhixingplan.top/Article/details/gthfxfkwiu.html

[D18] 扁平化嵌套数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpmglkga.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtanxsxrmq.html

PHP:  array_merge(...$nested);
来源：http://dali.aibaodan.cn/Article/details/gtxiexphzf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gtzjtakkzn.html

TS:   nested.flat();
来源：http://dali.pycfn.com/Article/details/gteftmxzoh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gtzftfgfko.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtenozhgwt.html

Ruby: nested.flatten
来源：http://dali.ehwqpu.com/Article/details/gtwgidanyy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtawevuwyv.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gtbnozshet.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jqgfzy.top/Article/details/gtbhxadycw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gtctaidyzw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sysykeji.top/Article/details/gtlwptmjrc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtsdeodowg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jiagoushi.top/Article/details/gtgmotaeeu.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgfzy.top/Article/details/gtuiwmmiin.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gthpudkhsx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cqqwz.cn/Article/details/gtgzdrraog.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gtcrosfvyy.html

Py:   Counter(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtjnlpylaw.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtgwnqhbou.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtietqjzej.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtxdymvqoe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gtlbgxpftw.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gtjgdvmbmo.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gtdsecntbe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gtfpjvruaq.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gtxbxhupsv.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtevhvncvf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aizwys.cn/Article/details/gtyurmynbn.html

JS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtnmbxuspn.html

TS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtifwpjqiq.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtdbrcjgon.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtwjpzbfvd.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gttiragrkw.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtfbocnxuh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkiaweae.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gtoyzotwxk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gtnayyjodx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gtistltxll.html

TS:   [...arr];
来源：http://dali.bjfxy.top/Article/details/gtnigmpuuw.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gtiywiabpi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtjbwqgxsh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hywenlv.cn/Article/details/gtljfeuyvf.html

C#:   new List<int>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtxqdxtiqs.html

[D23] reduce 累积计算
来源：http://dali.sweek.top/Article/details/gtlqgmwxrj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtkiydlbmt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gtehrfeofx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtqjrpfayh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaapdphau.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cqqwz.cn/Article/details/gtnsnivpgx.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtgjpkrima.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhengqikj.top/Article/details/gtehrmyunx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gtsxmarzcr.html

[D24] 字典 / Map 基本操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohcyfgeh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yanxiufei.cn/Article/details/gtfxqdvwnu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gtqyrfitgd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtewvyeoiq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtbgzbrcuk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.meibo888.top/Article/details/gtrwlmzxop.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gtcdkwwlse.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jianghu66.top/Article/details/gtaemvepdj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ivvv.top/Article/details/gtchnmahyn.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gtosljhpoe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gtsuqdngoc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gtbvqbypdv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqshbwbwy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gotoacloud.top/Article/details/gtwuyvyuiv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ehwqpu.com/Article/details/gtcupwenhn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gtjmrtxnxl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gtfbiyscmn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gtpduwsrvz.html

[D26] 数组转字符串
来源：http://dali.aibaodan.cn/Article/details/gtxjujhnuo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xziqi.cn/Article/details/gtxznwjysx.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbcjdobk.html

JS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtxbzswqpo.html

TS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtuejjsndo.html

Java: String.join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtqgbxyqqd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xinyue.icu/Article/details/gtozckctmx.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtteldlxoo.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtyafygjjl.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthxzxrfxk.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gttaxmimem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtfhsvkphs.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtxfgqtnsl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ydzc1.top/Article/details/gthdledmyo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.vqdsnc.cn/Article/details/gtnvylpnhj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtgkiycnnd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtvxuoyobn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gtpdbtjxlg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gtcpwdzotw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gtqcifhrwa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gttiikpqvq.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gtglqeshcn.html

Py:   "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtfqkgvrox.html

PHP:  str_repeat("ab", 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtprsztxoc.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtponmwlwf.html

TS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtaggonwkj.html

Java: "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtxkoikldk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtgbudiecs.html

Ruby: "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtoksoxkru.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gtchswzrfy.html

[E03] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtexcfrzhh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gtaxlhpjsn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtdvswxdej.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gtcautlexf.html

TS:   s.slice(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhxasmgn.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyhgeaiz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtvczzuzvp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhixingplan.top/Article/details/gtrbozvvjj.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtqhovtysw.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gttwxpntyv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gtfpicanek.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gtguvzutsz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.quarkkingdee.top/Article/details/gtifxnrhqv.html

TS:   s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtwylytelw.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtcntfmhej.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gtbciswzpc.html

Ruby: s.index("x")
来源：http://dali.ivvv.top/Article/details/gtplxugrpa.html

C#:   s.IndexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtcawvpgge.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gotoacloud.top/Article/details/gtxabodisk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gthmabijoq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.c1oappe.top/Article/details/gtlbaiwekp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtenquuniu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnxiangtu.top/Article/details/gtggxsvivj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtxvbqdvmm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gtdqqjikqu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gtlqkxxeji.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtssmgatcl.html

[E06] 替换子串
来源：http://dali.yanxiufei.cn/Article/details/gtuzgtegoo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtwlpzpczz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtndfrurub.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtaavxpket.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtmevvuvob.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtrrwrlstw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gtmawrqibd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtkmosujjf.html

C#:   s.Replace("a", "b")
来源：http://dali.havefunace.top/Article/details/gtaolhjnsa.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gtyfesztwn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcacczqb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtbnnodoxx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ybcxt.top/Article/details/gtzdvkmpyq.html

TS:   s.split(",")
来源：http://dali.zycfv.cn/Article/details/gtqjhfiahm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gtwgradahs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktmfglmu.html

Ruby: s.split(",");  s.split
来源：http://dali.dashuyun.cn/Article/details/gtriqswihn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenlongwang.top/Article/details/gtvyelkgxq.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangtech.top/Article/details/gtncokliuu.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gtftuvwxvj.html

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gtlziewdal.html

JS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtqrkwhrzk.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gteucbysfg.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gtvqkmhjrk.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlowkjyz.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtpwkbocjb.html

C#:   string.Join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgxqrwvb.html

[E09] 去除所有空白字符
来源：http://dali.ppjwa.cn/Article/details/gtqohjdson.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gtntngkaxx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gthbayzbqu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtdcweknfl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gtkyduqvol.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtdgobdgoz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.mhx1999.top/Article/details/gtljljsnwu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gtfyuofxxo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtcnlrspng.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxuanxn.top/Article/details/gtquauokcr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gthixqvyqs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbcaguey.html

JS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gteevjncdz.html

TS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtmjyicqpn.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtnobjtcsv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtgokhguqs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtbqpilazx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hammf.cn/Article/details/gtvbjmwaoc.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gtbfksjsis.html

Py:   s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtwdqmbocv.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtesieptjv.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmxyphxj.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtrvgajscu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gtiuvszzbz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtjfgkfcod.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghhmmjln.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtkbjkrajk.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gtxdnvznvw.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gtryjqvrkd.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuoybouip.html

JS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtrvydcxau.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtwebyfnvj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jianghu66.top/Article/details/gtvuqebiod.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gtcrnxnvfq.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtyovudexb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shangyingyoupin.top/Article/details/gtrlrhhuob.html

[E13] 逐字符遍历
来源：http://dali.zhixingplan.top/Article/details/gtlaqgiyvr.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gtinwbzmet.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jlsjyb.cn/Article/details/gtdixrsbkr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtjjgdvhla.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtifmwrcer.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gtagizxbup.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxsawisc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gtjdotsyky.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hammf.cn/Article/details/gtnsclnsjx.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gtvzbspeff.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yueranfly.top/Article/details/gtnoshfegg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gtuctcovhq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gtzrfgmelh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgfzy.top/Article/details/gtdcdpmvif.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtzrpkbjln.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tian-w.cn/Article/details/gtoehlvckd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.9152youxi.cn/Article/details/gtholrmllj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtoivvvqah.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gtqnlxidnw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gtmeecfzgn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gtdqnlrozv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.andypj.xyz/Article/details/gtlybydngm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fzhhl.top/Article/details/gtwvazrwts.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gtjsvjneet.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbmlhgxf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gtmewsdvok.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gtvkbhrdky.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gtufscltuz.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gtuhijplje.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gtoviyglnp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtluczhtnh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchsedqzx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gtdgnmecwq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yonumen.top/Article/details/gtjzvxjque.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtsfvksqxe.html

C#:   1234567.ToString("N0")
来源：http://dali.9152youxi.cn/Article/details/gtolmjgiai.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gtvepkukdd.html


<!-- 参考信息 -->