代发 wailian999

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gttpikclsg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.kuanghao11.cn/Article/details/gteaadwatx.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gtlbjcnwrm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gtvfmgcvtg.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gtpnvdjedd.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtevjsfklt.html

Go:   slices.Reverse(arr)
来源：http://dali.316326.xyz/Article/details/gtclnljjca.html

Ruby: arr.reverse
来源：http://dali.ehwqpu.com/Article/details/gtcluypjda.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtlvhrbuic.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gtaijiruna.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxinkj.top/Article/details/gtfaxsolrl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtazrfpyze.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gthpuqosvc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtlveoddot.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zycfv.cn/Article/details/gtezwqtpwf.html

Go:   slices.Index(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtbefjoiyt.html

Ruby: arr.index(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwclrmwld.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzwlqftt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuanzhike.top/Article/details/gtizwdekii.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gtsvlhqlok.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tian-w.cn/Article/details/gtbbkjwpms.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtrogimmms.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtpozglaow.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtchmltrnj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gtggcfyanm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258.top/Article/details/gtwsggyrwu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gtslpjaqfm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gtqdjyubii.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.0kj1m.cn/Article/details/gtqccuppyf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fengsongda.top/Article/details/gtussqkypa.html

JS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtxbuloaqt.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtqgytnzty.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yvedp.cn/Article/details/gtogazidqx.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtovxqszzx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtoqibalei.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtnsyzyyry.html

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtlwdkhpnr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtmevbfyvy.html

PHP:  array_unique($arr);
来源：http://dali.smart0.xyz/Article/details/gtvtkaxlda.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtmvmpryfu.html

TS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gtcbfoojvj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gtexjjduzp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.feifeiyinyue.top/Article/details/gtlepwxght.html

Ruby: arr.uniq
来源：http://dali.haohaochexian.top/Article/details/gtmajcaexl.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtlkitmevi.html

[D16] 求和与平均值
来源：http://dali.shangyingyoupin.top/Article/details/gttktrgrrx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtpihgvnpc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.iojbl.cn/Article/details/gtpdavkyxh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtvrzybrwx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtjjdixxer.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.iojbl.cn/Article/details/gtingfzdmx.html

Go:   // 手写循环累加
来源：http://dali.chenlongwang.top/Article/details/gtbotliuxg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gtdujgepnq.html

C#:   list.Sum();  list.Average()
来源：http://dali.hywenlv.cn/Article/details/gtjtbjfetx.html

[D17] 最大值与最小值
来源：http://dali.smart0.xyz/Article/details/gthzpcmwvm.html

Py:   max(arr);  min(arr)
来源：http://dali.havefunace.top/Article/details/gtdaqttcos.html

PHP:  max($arr);  min($arr);
来源：http://dali.yangfankeji.com/Article/details/gtlmpemuml.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtbujznwca.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gttdkcdapa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgufenzy.top/Article/details/gtgjofpzeu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gtugrxftrp.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflxsixtu.html

C#:   list.Max();  list.Min()
来源：http://dali.xuetiantiany.cn/Article/details/gtsenhytps.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gtkbouysfp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gtrblykkaw.html

PHP:  array_merge(...$nested);
来源：http://dali.redwolf501.top/Article/details/gtxwyhustt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.kuanghao11.cn/Article/details/gtmpfblxfj.html

TS:   nested.flat();
来源：http://dali.snrcjt.cn/Article/details/gtpddncafv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gtfxhqakbx.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtdzbzovss.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtoqnwbj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtieibkpiv.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyspraaza.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzucrebvt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtqticke.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gtizowowmf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gtfolueyqt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zycfv.cn/Article/details/gtxuqfbznd.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gtounuvpvm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gtlbvwatpu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangshuangyany.cn/Article/details/gtngmnaogg.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gtjdomrgss.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gtmbovsrpi.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtntrnrdmi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtjndubzzp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtabxypwpc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhengqikj.top/Article/details/gtqzsheagr.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gtzkganomr.html

Ruby: arr.tally
来源：http://dali.nwbrower.top/Article/details/gttivvefyk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gttoezeyea.html

[D21] 判断是否包含某元素
来源：http://dali.snrcjt.cn/Article/details/gtwevzgwhu.html

Py:   x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtpavqywoz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ydzc1.top/Article/details/gtzsgdyxut.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtyniajufb.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtaazxqhlq.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gtodjxovbz.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtmpnhpmnj.html

Ruby: arr.include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gtulcbblbi.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtvkjazzmi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gtrezbcspb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gteyvgegfu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gtxvlxhrlr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.9152youxi.cn/Article/details/gtudqfbjcl.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gtdlaxrkot.html

Java: new ArrayList<>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtzkqdvsbd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gtutpxrqiy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hammf.cn/Article/details/gtptluziuy.html

C#:   new List<int>(list);
来源：http://dali.yueranfly.top/Article/details/gtjxqtuuru.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gtaxaiykzv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gtsucdnbdx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gtnwdljmqw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtfrdfpiee.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtxxbjxecj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ybcxt.top/Article/details/gtpljxpocn.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtjhdaqikd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gtmupywxmp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gtjvbfekmc.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gtaecccwgt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guowangkeji.top/Article/details/gtfygieuvt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigufen.top/Article/details/gtrmhmyfjq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtrwmgjtul.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtjjnltpnt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gtbufsniif.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xziqi.cn/Article/details/gtmitqwemo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gtyrherbzb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtftkwldln.html

[D25] Set 集合去重与交并差
来源：http://dali.chenlongwang.top/Article/details/gtswmspxlb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aibaodan.cn/Article/details/gtkjuoqvwg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtezejbxdq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xinyue.icu/Article/details/gtywzbrbkq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cdnleiting.top/Article/details/gtijlzgykp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuanzhike.top/Article/details/gtrihjjuze.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gtsgjespgg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cashguo.top/Article/details/gttjywnhgt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtixqdclse.html

[D26] 数组转字符串
来源：http://dali.0kj1m.cn/Article/details/gtznsaapgm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gtsmnylibg.html

PHP:  implode(", ", $arr);
来源：http://dali.9152youxi.cn/Article/details/gtldcexwqi.html

JS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtjlcuojww.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gttxphpkun.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtobrrhgrk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplyqsdsv.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtmqsusleu.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtabvvuvvb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtizcwfmmn.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gtjknmghtm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtohzxjdci.html

[E01] 拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gttmrvxcxi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yangfankeji.com/Article/details/gtejxaskeq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xinyue.icu/Article/details/gtvvgthdev.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtdeivdpgt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtjadjcjsb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fengsongda.top/Article/details/gtjflizhci.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gtqmsrylvj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gtgqtiratz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtrhwgvarl.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gtvvudggky.html

Py:   "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtdmfuhdfm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.0kj1m.cn/Article/details/gtghvrvezt.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtsnjogatt.html

TS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtsaqmmeja.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszyytfts.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gtakxlcmmj.html

Ruby: "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtaxwistfm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtuxvrbjfz.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtevuyhhkd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gtymenskdq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoigwobnr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtuzbibpdr.html

TS:   s.slice(1, 4)
来源：http://dali.meibo888.top/Article/details/gtovujlfxt.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtcxhntgub.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.bjfxy.top/Article/details/gttosxvqjg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sxryk.cn/Article/details/gtrxlawycl.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gtlckpswdm.html

[E04] 查找子串位置
来源：http://dali.nanxinkj.top/Article/details/gtppedxeqr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtyatsddko.html

PHP:  strpos($s, "x");
来源：http://dali.nwbrower.top/Article/details/gtdjqglltk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.c1oappe.top/Article/details/gtrrddxwgc.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtzirxptzk.html

Java: s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtbvpfmuxk.html

Go:   strings.Index(s, "x")
来源：http://dali.zhengqikj.top/Article/details/gtwxlsdzev.html

Ruby: s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtayohbhfh.html

C#:   s.IndexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtqsoimqtq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gtntsjhmsn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jyoumei.cn/Article/details/gtwetvskqh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gtdmugdrgv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtxypolzgb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gturaawiki.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtopntgguh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sxryk.cn/Article/details/gtiorjonqq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtfubzwiut.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtltftcdug.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gtlsrcsbjo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtbblxaxiz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhengqikj.top/Article/details/gtcrlocrtt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtnozqtvcf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtgmsbjomn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtcsadiqwu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtgmyjpomr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtbwvvemjl.html

C#:   s.Replace("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtejhbeocq.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gtdeeshabu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.iojbl.cn/Article/details/gtaocwflpy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ivvv.top/Article/details/gtavvvfemq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xinyue.icu/Article/details/gtfyhdrucr.html

TS:   s.split(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjiqlvjh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cdnleiting.top/Article/details/gtcmcausmh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gtxpukoiue.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gtcidpcgli.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gtcwnkjhmn.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gtukrxztfv.html

Py:   ",".join(items)
来源：http://dali.hysaishi.cn/Article/details/gtmjwmjqat.html

PHP:  implode(",", $items);
来源：http://dali.sysykeji.top/Article/details/gtwrbowfod.html

JS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtshcdwwav.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtldheehei.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtjbrebmiv.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gtsupzpfjk.html

Ruby: items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gthvhvtavx.html

C#:   string.Join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtenxeajhj.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gtxufhztes.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gtrqhgqhqp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgfzy.top/Article/details/gtpmhsukur.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtnjwatrbn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gtdqqqdrko.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtuuylrzjk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigufen.top/Article/details/gtnvbyttwj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtudqukttv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtpkktwvkt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgufenzy.top/Article/details/gtvbyglgdl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtmprkolgj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gtzpvmwqle.html

JS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtwnakncoo.html

TS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtomvuzfhz.html

Java: String.format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtigndkfzm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtnuypgqes.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtfqpwmfdi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.bjfxy.top/Article/details/gtxdcnrtum.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gthufqvqfv.html

Py:   s[::-1]
来源：http://dali.sxryk.cn/Article/details/gtetahbsij.html

PHP:  strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtgyrsoelz.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gttlyhlvww.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtfxelpnei.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gtcxxwttes.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gtuvwbuycy.html

Ruby: s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtbpczfyfi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtchqsvjtr.html

[E12] 统计某字符出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtunyugfjr.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtdfcrxesv.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtwcwmmbim.html

JS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtsxivspmk.html

TS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtkbnspeqo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gtvimzkqqi.html

Go:   strings.Count(s, "a")
来源：http://dali.ybcxt.top/Article/details/gtgnbhivrv.html

Ruby: s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtskmxnbau.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yanxiufei.cn/Article/details/gtffwgbwur.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gtosvgbgtb.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gteikekrxw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zdqjudy.top/Article/details/gtrmltjidn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtnbjtiwca.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtsnkcsjyk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuanzx.com/Article/details/gtylfjiwif.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gtyonejtvu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsjmfslm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gtlruxgjvp.html

[E14] URL 编码与 Base64
来源：http://dali.zhixingplan.top/Article/details/gtullgpjsg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizmocacz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gogol.net.cn/Article/details/gtqgufrfkz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gtiuxqpmor.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtszjhttwh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtnolhyaqz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gtfzmpjcnq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.9152youxi.cn/Article/details/gtorkhwkho.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gtgvnilydv.html

[E15] HTML 转义 / 反转义
来源：http://dali.sysykeji.top/Article/details/gtpsljlyml.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gtylmppmti.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aibaodan.cn/Article/details/gtyrimbmor.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gthoxzwacz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zycfv.cn/Article/details/gtzybvtfme.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.vqdsnc.cn/Article/details/gthbtlsftz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtqycygmmu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dashuyun.cn/Article/details/gtmkenhpfo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnsueumd.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gtgwaxnshp.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gtkermotil.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gtcolzlfnw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtthxntuts.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gtpqyvwlig.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtrrpqikwk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuxming.cn/Article/details/gteaiveqac.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gtxdspdnui.html

C#:   1234567.ToString("N0")
来源：http://dali.jyoumei.cn/Article/details/gtgdwtixra.html

[E17] 首字母大写
来源：http://dali.mhx1999.top/Article/details/gtirouqyrj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gtvmwubxna.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gtyzivydfy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtsscnljoi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtyjvitrgf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gtlptskwjy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gtyjaecqbs.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyqffghg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenlongwang.top/Article/details/gtryzozhqg.html


<!-- 参考信息 -->