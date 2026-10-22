代发 wailian999

C#:   list.Reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkhrgocm.html

[D12] 查找元素下标
来源：http://dali.redwolf501.top/Article/details/gtoiisloxy.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gtpgqsvfao.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtjedclctc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gthoxwgprg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gtwhustlnb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dianchejie.cn/Article/details/gthshnqzsd.html

Go:   slices.Index(arr, x)
来源：http://dali.hnqzz.top/Article/details/gttwahmoyn.html

Ruby: arr.index(x)
来源：http://dali.c1oappe.top/Article/details/gttsgnanec.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gtngmnlfaz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyzutuvd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jyoumei.cn/Article/details/gtkpajciub.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xinyue.icu/Article/details/gtrettjzra.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtoxuwdtuz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gthfwgcdju.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gttnjagnmd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gtnmcpbciu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cqqwz.cn/Article/details/gtdqvastyj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shzxlz.cn/Article/details/gteyfsczmb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gtmbxtmjze.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.iojbl.cn/Article/details/gtkxpbjvzz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnarcqlr.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtuhhwrjfr.html

TS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gteoeazpve.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrytkfeh.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gtwrwznekc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hammf.cn/Article/details/gtovfgbahu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnqzz.top/Article/details/gtnpoaoodm.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gtxrkqwomp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gtjrvqwzad.html

PHP:  array_unique($arr);
来源：http://dali.zhengqikj.top/Article/details/gttmokrlgq.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtvpbnqcnh.html

TS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtrzydgjwh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gtyheidjro.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.havefunace.top/Article/details/gtasqgorfb.html

Ruby: arr.uniq
来源：http://dali.guowangkeji.top/Article/details/gtqmlbftxp.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtsnueenez.html

[D16] 求和与平均值
来源：http://dali.zycfv.cn/Article/details/gtxuzbbpxr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.c1oappe.top/Article/details/gttyqjwdtj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtuauwhnmr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gtsnnbcoke.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtthzlpggy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangshuangyany.cn/Article/details/gtksracqqf.html

Go:   // 手写循环累加
来源：http://dali.jinqigfzy.top/Article/details/gtwnzkyolq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cheryme.top/Article/details/gtwrqratrf.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gtiitywife.html

[D17] 最大值与最小值
来源：http://dali.xuanzx.com/Article/details/gtmuxuhgnq.html

Py:   max(arr);  min(arr)
来源：http://dali.sweek.top/Article/details/gtkiwqsaft.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxinkj.top/Article/details/gtnovtxvyi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gtwbqrnpqo.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gtrqgfjucr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xinyue.icu/Article/details/gtoturrbdl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuanzx.com/Article/details/gthrjmzoap.html

Ruby: arr.max;  arr.min
来源：http://dali.meibo888.top/Article/details/gtkcwfohja.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gtlfeghgjf.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gteujfxhvz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gtfniyfeli.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gtetwzhbfz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gtnyfdivgq.html

TS:   nested.flat();
来源：http://dali.pengpengdd.cyou/Article/details/gtmbzhdsls.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtyblrrlsa.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtxaijthzz.html

Ruby: nested.flatten
来源：http://dali.shuidangran.top/Article/details/gteluxejvt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtkdpronvq.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gtvlftyaqg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sysykeji.top/Article/details/gtevybbkwj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhengqikj.top/Article/details/gttjwdoxsc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gthzzwoyrf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtywmgfvcf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xinyue.icu/Article/details/gtkjajrbcs.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gtxdfmrgzt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gtmkmgnlqq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fzhhl.top/Article/details/gtkegliwnc.html

[D20] 统计每个元素出现次数
来源：http://dali.hammf.cn/Article/details/gtgzufvvjt.html

Py:   Counter(arr)
来源：http://dali.fengsongda.top/Article/details/gtsfvqqrnh.html

PHP:  array_count_values($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtsevlbrob.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtwfcefdbn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtdvdhuluz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnqzz.top/Article/details/gtpnofermq.html

Go:   // 手写 map[T]int
来源：http://dali.pycfn.com/Article/details/gtbabihelz.html

Ruby: arr.tally
来源：http://dali.jlsjyb.cn/Article/details/gtdoqaveem.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gtzgzxupyo.html

[D21] 判断是否包含某元素
来源：http://dali.ivvv.top/Article/details/gtosiznfae.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gtrhrwcxes.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtywnogunc.html

JS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtmsrfqhnf.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gthfdeqwba.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxuvihwa.html

Go:   slices.Contains(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtihjvztjw.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gtzvcwbbil.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtpdwduwsk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gtahgjjjhg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gtkqylujzl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.c1oappe.top/Article/details/gtisklxmka.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtuwgxtjpn.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtqrqrxuvy.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtwrdudkbc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yvedp.cn/Article/details/gtkbkhzgyp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gtwjbuogmr.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gttxfnvgsh.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gtqxlysqep.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtlvsndyuu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gtswkphlkn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtglavobtv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gtoziigtek.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvuotigh.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtqfftmjkt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daria6918.cn/Article/details/gtzgejlvzt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gtujacqrqa.html

[D24] 字典 / Map 基本操作
来源：http://dali.feifeiyinyue.top/Article/details/gtpwyewqby.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zycfv.cn/Article/details/gtaurdknvs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gtbtdqiwzd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jyoumei.cn/Article/details/gtfagcwvyz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtwnwssvet.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gttlmyttvp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gtueymgpmr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aibaodan.cn/Article/details/gtwlguldir.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sweek.top/Article/details/gtehxtmzbv.html

[D25] Set 集合去重与交并差
来源：http://dali.guowangkeji.top/Article/details/gtfycdonhu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gttjrhowel.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gtmieqowwf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gtumroytmy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gtodidpsci.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.c1oappe.top/Article/details/gtkprkprxv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.bjfxy.top/Article/details/gtmdxcmcyk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gtoygdcxof.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.316326.xyz/Article/details/gtrjpyeutk.html

[D26] 数组转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtujjmmywp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gtadgwogwi.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gtwuimhztj.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtfrxjblxu.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdooudbtw.html

Java: String.join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gteskefyun.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gtblmncdro.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtjmfwmwml.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtlabdqees.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjmqwussg.html

E. 字符串处理
来源：http://dali.nanxinkj.top/Article/details/gtqurpnpuu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadwxtjgy.html

[E01] 拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtcpzntgus.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ybcxt.top/Article/details/gtuphbkcyd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gtgllaxjfo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtkgjkfuvr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtewjovhia.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenlongwang.top/Article/details/gtphbjcyvm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daria6918.cn/Article/details/gtzcrgkzzc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shangyingyoupin.top/Article/details/gtmxaxuhwi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtwjhexohc.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gtvbcocfwc.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gtfgmgbfoz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenzaomai.com/Article/details/gtskobcflg.html

JS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtzavemiwr.html

TS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtefhtxtvo.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjkroqme.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxinkj.top/Article/details/gtdjoocqru.html

Ruby: "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtcqpevadf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.meibo888.top/Article/details/gttxbyolad.html

[E03] 截取子串
来源：http://dali.nwbrower.top/Article/details/gtszzhqxkj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gtsnkhjnsm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtgbdyjyhp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtbegzcjzr.html

TS:   s.slice(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtdtlfydmk.html

Java: s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtingkrawe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmssaoxn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gtuxagnnke.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtangrelhw.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gtwywigxkx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtsukgkdcd.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gttqgfjtwt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.redwolf501.top/Article/details/gtjkzraqqi.html

TS:   s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdpaauhp.html

Java: s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtljhlsjdk.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gtqbjudwqg.html

Ruby: s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqpbuusw.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtzcoiolbc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yvedp.cn/Article/details/gtowdvtacx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cqqwz.cn/Article/details/gtcuzcknkb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sxryk.cn/Article/details/gtsplapqpf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gttznjdkhs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gtzwdfkcdt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtlctcvupc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gttrarukfn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.meibo888.top/Article/details/gtlsyrpntr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtlbbjklva.html

[E06] 替换子串
来源：http://dali.yvedp.cn/Article/details/gtorfhnrvm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtjywbyncg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxabirdz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtkghtxepl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtgovekwxj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtfxwkyenz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtpyutequl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtfajauhco.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258.top/Article/details/gtgublklie.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gttolvtovu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aizwys.cn/Article/details/gtjnuesyyn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtkprzhprl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangshuangyany.cn/Article/details/gthbxabnxd.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gtzyivxvjj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuetiantiany.cn/Article/details/gtgybpecws.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtowfqdtdp.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gtghzpiyhy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dashuyun.cn/Article/details/gtannrvotl.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gtriupprcr.html

Py:   ",".join(items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcupfzynn.html

PHP:  implode(",", $items);
来源：http://dali.zhengqikj.top/Article/details/gtigfehkrb.html

JS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtevvhwbbs.html

TS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gthcypomhb.html

Java: String.join(",", items)
来源：http://dali.nwbrower.top/Article/details/gtshzxcuuw.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gtmmnfazoi.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtcgkfptvl.html

C#:   string.Join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gtuxmwczta.html

[E09] 去除所有空白字符
来源：http://dali.havefunace.top/Article/details/gtipmgscgm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jlsjyb.cn/Article/details/gtaobhxpmo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtwyeaqcji.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtalmkmiog.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gthbhuxerh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yueranfly.top/Article/details/gtpeoucsut.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shangyingyoupin.top/Article/details/gtegupmycw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zycfv.cn/Article/details/gtebqsbeal.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zycfv.cn/Article/details/gttoscszul.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xziqi.cn/Article/details/gtjfuxgxqo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtjivmsfey.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuxming.cn/Article/details/gtleutxyfg.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtuzdjwlwy.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtimunhavs.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtmwvsllfg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtrnypozbk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtdyrghbiy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhixingplan.top/Article/details/gtidjqkxoy.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gtrpzynryl.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtbugucasb.html

PHP:  strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtxszyadsj.html

JS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtylhehhyf.html

TS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxudkdgm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hfpthk.cn/Article/details/gtrilavxkm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gtvlvhvbhz.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtefxgtdub.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtcnwvafpk.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtplhrfjpq.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gtudkgwdij.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gthuqkhbss.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtuxnxmwok.html

TS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gtmawarrhk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yueranfly.top/Article/details/gtzfvysqys.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gtdddrxpgl.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtasvkhwqv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ybcxt.top/Article/details/gtcsgauwwp.html

[E13] 逐字符遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtxwjqziiy.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gtgkihzgwf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yongpay.top/Article/details/gtqufsbqzw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtovxqriul.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gttueadenz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daria6918.cn/Article/details/gtujpzdtrf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.redwolf501.top/Article/details/gtgvpkxtbc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtuzsgptun.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdyuxnqx.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gtxkiodvfe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gtnofpslxm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gtenbelgta.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuanzx.com/Article/details/gtcsusamuh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gtzkwpsdzk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xylfe.cn/Article/details/gtpotkqnlm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aibaodan.cn/Article/details/gtuxwbekuw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gtqqxzbjig.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gthyvhektp.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gthubvuhww.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gtuerbyxzu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ehwqpu.com/Article/details/gthlbxkeap.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gtqpptrtrs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtqxwzsgib.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gtfpwgomqf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtuqrvizap.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.bjfxy.top/Article/details/gtrsgzkypl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gtbwuicgnc.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gtytmrjjsx.html

Py:   f"{1234567:,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtwikcyftp.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoxmyrbk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtevgvyhnq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtlvktcbzq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtyjhanfcc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgfzy.top/Article/details/gtntiwwkiw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yanxiufei.cn/Article/details/gtoaycuqpj.html

C#:   1234567.ToString("N0")
来源：http://dali.hnxiangtu.top/Article/details/gtbztiqvmn.html

[E17] 首字母大写
来源：http://dali.cucudq.cn/Article/details/gtqvrverbt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gtcyurfmqi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gtxqfrincs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gthmfmufep.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtnnuiztry.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gtsbgrhodu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gtxxbfqomn.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gtqnsulrpg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenlongwang.top/Article/details/gtnybptuni.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gtbahjodcq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gtgmaidsjf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtsqivnapj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtgisnbhdj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtvvqgzick.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtrltstcex.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtadirozrz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gtvnqgfcln.html


<!-- 参考信息 -->