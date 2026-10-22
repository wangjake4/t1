代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gtequnpjir.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cheryme.top/Article/details/gtfcdededh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzylwpmd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gtqqsvzxot.html

[D11] 反转数组
来源：http://dali.chenjidiqi.icu/Article/details/gtvkopzsoy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gtleypghma.html

PHP:  array_reverse($arr);
来源：http://dali.birdmap.top/Article/details/gttzqatwzx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yvedp.cn/Article/details/gttlfcxxtw.html

TS:   [...arr].reverse();
来源：http://dali.hysaishi.cn/Article/details/gtdolwzcpr.html

Java: Collections.reverse(list);
来源：http://dali.jinqigufen.top/Article/details/gtwtyvbaji.html

Go:   slices.Reverse(arr)
来源：http://dali.ybcxt.top/Article/details/gtdkjjtnqx.html

Ruby: arr.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtngrpchwu.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gtkzffbmab.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gtwakizajv.html

Py:   arr.index(x);  x in arr
来源：http://dali.xylfe.cn/Article/details/gtupvzbycc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtxfktdmfv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gtjuqfyilp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtrraulvea.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gtjosrwafk.html

Go:   slices.Index(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtvgmxlgmz.html

Ruby: arr.index(x)
来源：http://dali.jianghu66.top/Article/details/gtfamfovms.html

C#:   list.IndexOf(x);
来源：http://dali.c1oappe.top/Article/details/gtovqyzoym.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dashuyun.cn/Article/details/gthsijoeac.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yongpay.top/Article/details/gtqbprgcud.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yangfankeji.com/Article/details/gtqvbxdaca.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtrqyghgtc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtxgubufxy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.birdmap.top/Article/details/gtjssdqtaz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhiwuduotai.top/Article/details/gtplhzqnwd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hysaishi.cn/Article/details/gtduapbzut.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.316326.xyz/Article/details/gtzmysmdog.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhixingplan.top/Article/details/gtvnyceyvy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnqzz.top/Article/details/gtxybnnlal.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtiynuzwxh.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtqfgbzoul.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gthjhoseji.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gttcvtizso.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtcorrpznu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gttocfdmaa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.iojbl.cn/Article/details/gtwkpxmpwd.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzrwfcrn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gtrderkwjd.html

PHP:  array_unique($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtlqxnwyxx.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtuewfmurv.html

TS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtdxishcxu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gtkifvgpnd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.iojbl.cn/Article/details/gtgiahxnau.html

Ruby: arr.uniq
来源：http://dali.vqdsnc.cn/Article/details/gtbvehlkyk.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gticpkzjyf.html

[D16] 求和与平均值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdthnhtxc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtfqosbglp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtnenzjpif.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtarvcpwii.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gtsaseozje.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.havefunace.top/Article/details/gttyugehlx.html

Go:   // 手写循环累加
来源：http://dali.zhixingplan.top/Article/details/gtgztneeej.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtejsnhgnq.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gtbuyhegss.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gtywexmuro.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtyejyplyp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zycfv.cn/Article/details/gthqhxzejc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sufxvd.cn/Article/details/gtxvebwpgp.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gtzosqthew.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258.top/Article/details/gthlilrjoi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gtoapcefwk.html

Ruby: arr.max;  arr.min
来源：http://dali.aizwys.cn/Article/details/gteexvkhye.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthqtueny.html

[D18] 扁平化嵌套数组
来源：http://dali.feifeiyinyue.top/Article/details/gtjdyxzgfb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxinkj.top/Article/details/gtpmzyxxyk.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjsaylxx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytwlvgap.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gtkbamobju.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxinkj.top/Article/details/gtndcbcpfj.html

Go:   // 手写双层循环
来源：http://dali.havefunace.top/Article/details/gtbfqinivx.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gtwsebkqzm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtrwrpleci.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gtncitfijv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gzhubu.top/Article/details/gtlaabfrgf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gtgzbieogg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sxryk.cn/Article/details/gtvlhdzxjk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gtoxuvwgwt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.vqdsnc.cn/Article/details/gtfvzipouo.html

Go:   // 手写 map[string][]T
来源：http://dali.cqqwz.cn/Article/details/gtvtiolbol.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtmqubrnxe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gteoljuqxb.html

[D20] 统计每个元素出现次数
来源：http://dali.hysaishi.cn/Article/details/gtimhnbbly.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gtontnoank.html

PHP:  array_count_values($arr);
来源：http://dali.cqqwz.cn/Article/details/gtfklnaljr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtarhrejpe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtoufskics.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cdnleiting.top/Article/details/gtmeqqsrvc.html

Go:   // 手写 map[T]int
来源：http://dali.svipenyu.cn/Article/details/gtvtdprqgk.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gtuymfpqel.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcjohtxp.html

[D21] 判断是否包含某元素
来源：http://dali.wangshuangyany.cn/Article/details/gtgpgkqtmx.html

Py:   x in arr
来源：http://dali.yvedp.cn/Article/details/gtavbxgrot.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtpouaxaci.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtbfqroxvk.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtpwrorxrh.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtlbckksfx.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtvnakqqkg.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gthmryfplh.html

C#:   list.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gtabqtrviu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gtlbembvjx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtlfsjfeks.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangdashe.top/Article/details/gtwdnnxxsm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gtssykwrxy.html

TS:   [...arr];
来源：http://dali.nanxinkj.top/Article/details/gtnlqwpidh.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtphqanqeq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gtrcdhadxk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzyazewp.html

C#:   new List<int>(list);
来源：http://dali.daxiang520.top/Article/details/gtjghpprae.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtnqkrbsbr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aibaodan.cn/Article/details/gtadgvmmyg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gttsiaahdn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtabthlzxy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gtawbklsqc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gtubmvvzwn.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtiughmskq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hywenlv.cn/Article/details/gtzpjvwaey.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gtidaozszu.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gtvpusvnve.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ppjwa.cn/Article/details/gtjpgutsei.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gtkurhkran.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gtxempxmro.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtgfnlzpow.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shzxlz.cn/Article/details/gtawugmwdw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nwbrower.top/Article/details/gtlknpxqgy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigfzy.top/Article/details/gtvsmtdtcw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.quarkkingdee.top/Article/details/gtavujdwbh.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gtyizizofz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yangfankeji.com/Article/details/gtechdflhc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtqlqsdeoy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pycfn.com/Article/details/gtldsovhrw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuanzhike.top/Article/details/gtpeuhzxqk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gtykqwzyps.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sufxvd.cn/Article/details/gtlzrlwrff.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258.top/Article/details/gtgrwazwip.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtqdwkghdr.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtacfktrnk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gtytrrrklr.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtwzbtikle.html

JS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtybuixvkh.html

TS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdeduhkor.html

Java: String.join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtwgzzmykw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gttjccogva.html

Ruby: arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtxaxcxbkr.html

C#:   string.Join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gtlfxkthtj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfnjgiedc.html

E. 字符串处理
来源：http://dali.daria6918.cn/Article/details/gttypgajpn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxhonweza.html

[E01] 拼接字符串
来源：http://dali.yj20258.top/Article/details/gtuqnlmxkp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pengpengdd.cyou/Article/details/gtvxizmpqx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sufxvd.cn/Article/details/gtlrbiaocy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtyyljgjfu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewprjuce.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fengsongda.top/Article/details/gtzvttpjni.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jyoumei.cn/Article/details/gtifadnvvo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gotoacloud.top/Article/details/gtrkljodvk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtsadtbuev.html

[E02] 重复字符串
来源：http://dali.sufxvd.cn/Article/details/gtoxeowjju.html

Py:   "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtsomhfviy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gtgjuuyuxa.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtgknklqsz.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtptuiwuvo.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtjbftzoys.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cucudq.cn/Article/details/gtwwjiskgq.html

Ruby: "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtbktdssnx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtrftqykgd.html

[E03] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gtrvyjwtzk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gtckcmfaqr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtscnckhne.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtvydcerbh.html

TS:   s.slice(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtmldxyuxt.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtgwakbodl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.9152youxi.cn/Article/details/gtufneoish.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sufxvd.cn/Article/details/gtooqhmohn.html

C#:   s.Substring(1, 3)
来源：http://dali.jiagoushi.top/Article/details/gtvfxqzkzk.html

[E04] 查找子串位置
来源：http://dali.fengsongda.top/Article/details/gtdqqduizz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.c1oappe.top/Article/details/gtgucnbezy.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gtufewsbfy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhongyouzk.top/Article/details/gtuuyfixij.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjleuwdo.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtbvfyeeoj.html

Go:   strings.Index(s, "x")
来源：http://dali.zdqjudy.top/Article/details/gtgrqogkru.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcllgrniy.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuzndbmg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnwryjix.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtepwrkaos.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pycfn.com/Article/details/gtrpfuszxx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtiigeavis.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258888.top/Article/details/gtyvmlquml.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtrmebezbd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxinkj.top/Article/details/gtmrvuowab.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnqzz.top/Article/details/gtcmfucyas.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtaydvhjdr.html

[E06] 替换子串
来源：http://dali.sufxvd.cn/Article/details/gtvnhetiza.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtfbtqebfe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.vqdsnc.cn/Article/details/gtkvlamong.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtuwsgyzdj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtyvzcxhiw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtvzozowzh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gthshfrnvq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tian-w.cn/Article/details/gthvsoxjsm.html

C#:   s.Replace("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtpsfyjxls.html

[E07] 按分隔符拆分
来源：http://dali.dashuyun.cn/Article/details/gtqbhycuts.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yvedp.cn/Article/details/gtszodjogt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsetahdv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.havefunace.top/Article/details/gtzuivmgfa.html

TS:   s.split(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtqlojorpo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dashuyun.cn/Article/details/gtznufzmyb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gtgwpfnwru.html

Ruby: s.split(",");  s.split
来源：http://dali.bjfxy.top/Article/details/gtbsmxnbyk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cqqwz.cn/Article/details/gtsxdxldhw.html

[E08] 数组按分隔符合并
来源：http://dali.guowangkeji.top/Article/details/gtwmremiqq.html

Py:   ",".join(items)
来源：http://dali.redwolf501.top/Article/details/gtvxdxdksw.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gtoootygzt.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtftfjiokk.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtspynzaae.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtkaibzxjk.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gtwcgadfcm.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtkimmqueq.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtxyaqdhlc.html

[E09] 去除所有空白字符
来源：http://dali.wangdashe.top/Article/details/gtiuxdusuf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtjkypsbow.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gtdixquyhg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtzpdmwilc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtgmmbissk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtknwqakex.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gtwjsertrq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gtemitbwzy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gtvqtpxdsu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxjpzodx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtrktijqhj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtpkfqkemd.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtfbvyhurt.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtkscylqwd.html

Java: String.format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppzzstyz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtvmxvgkib.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtgjomdpww.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfoeyvmy.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gtkuvbeeze.html

Py:   s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtddcgorxp.html

PHP:  strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsyuyvrq.html

JS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gthbtiggyx.html

TS:   [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtwfztijsp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtvyavvmst.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtbrgfmeft.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gtanbppxcc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gtgtptzwud.html

[E12] 统计某字符出现次数
来源：http://dali.dashuyun.cn/Article/details/gtmjvywimo.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtswujossp.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gttxkknsqv.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhjsvkdx.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtlyfvjwyh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gtjwyfeixo.html

Go:   strings.Count(s, "a")
来源：http://dali.yuxming.cn/Article/details/gtrxpmqupm.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbbjtiez.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gtvohqvauw.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gtujvtezir.html

Py:   for ch in s: print(ch)
来源：http://dali.redwolf501.top/Article/details/gtaxyuojmn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcxakexj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtoijwsxhv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gthrpxuqkz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtojofjeox.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnxiangtu.top/Article/details/gtzijdehwa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gtdejcygab.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.andypj.xyz/Article/details/gtwzmierdq.html

[E14] URL 编码与 Base64
来源：http://dali.svipenyu.cn/Article/details/gtssyersdt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pycfn.com/Article/details/gtpdxksfrc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtegctitwu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gtzsmmqhkn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj202588.top/Article/details/gtwjeqognq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhixingplan.top/Article/details/gteibbfqal.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gtrizaszvf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gtkaikbjdh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gteyeewpdn.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gtnvwjmtib.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgarhvyfi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gtmhrlnmeg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gtpahifqsm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtgdlsvmhz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gtxkccpzxd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258.top/Article/details/gtlxzdzteb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gtkwvooxgt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gtchbroklb.html

[E16] 数字千分位
来源：http://dali.haohaochexian.top/Article/details/gtkjwnztwo.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gtedibjdnt.html

PHP:  number_format(1234567);
来源：http://dali.xylfe.cn/Article/details/gtsrorfdgi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtfeexdnpx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtjmijujgr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtxwztanyx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gticaarneo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gtqbmaytzd.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gtvoakgrpl.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gtkrqynulu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gtjxnzyuyv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbannaxa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtfpiiwmcx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdzlqnzj.html


<!-- 参考信息 -->