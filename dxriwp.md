代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.cqqwz.cn/Article/details/gt2utlhzkuf.html

Java: Collections.reverse(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2fejpqfyw.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gt2qsvhjpar.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gt2scjnhnrn.html

C#:   list.Reverse();
来源：http://dali.jqgufenzy.top/Article/details/gt2jkjnhbdj.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gt2latevqrn.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gt2phqmimbw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zvfquhuv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xizztduv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2xdohirwn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epqtodyv.html

Go:   slices.Index(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezapkcxz.html

Ruby: arr.index(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2toqnnedd.html

C#:   list.IndexOf(x);
来源：http://dali.zycfv.cn/Article/details/gt2adtaaefj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gt2jzubrsir.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2okfqpimj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gt2yrtxiiqa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gt2zhrncxxa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywbtcpey.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2aiqnsytl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gt2aebfjotu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gt2lnfxsfkz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2ronpeptd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aizwys.cn/Article/details/gt2xflwstoy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dashuyun.cn/Article/details/gt2tvrcnjfh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gt2xszpuxtu.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gt2zxsdawto.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2qbvnxpmu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2iwwxgiev.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gt2iblfgtee.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kekavoyf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2lpnnphuv.html

[D15] 去重
来源：http://dali.xinyue.icu/Article/details/gt2xwydioam.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlnuftfy.html

PHP:  array_unique($arr);
来源：http://dali.yuxming.cn/Article/details/gt2qbigxxjp.html

JS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gt2zcbpzbpg.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gt2hutoelhd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yonumen.top/Article/details/gt2agsqlgax.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gt2eyxeiepl.html

Ruby: arr.uniq
来源：http://dali.meibo888.top/Article/details/gt2pculzsgg.html

C#:   list.Distinct().ToList()
来源：http://dali.wangdashe.top/Article/details/gt2bwlkemij.html

[D16] 求和与平均值
来源：http://dali.ehwqpu.com/Article/details/gt2kdirvcyt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuxming.cn/Article/details/gt2puitxqrn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.c1oappe.top/Article/details/gt2njvlccqt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gt2yuawmozi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gt2ualmzrkv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gt2bdgovngq.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skucbfdh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gt2zdllgrzw.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gt2pvsmmaag.html

[D17] 最大值与最小值
来源：http://dali.cheryme.top/Article/details/gt2rnumbvbd.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2mdydpdqg.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2uocsusmg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xinyue.icu/Article/details/gt2hmgwcizf.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gt2dosmmrcb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gt2lcluxumh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.c1oappe.top/Article/details/gt2wzwlcskn.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gt2hrolsqyr.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gt2wlniworq.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gt2hvalqizg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gaohongyu789.top/Article/details/gt2ehylbuya.html

PHP:  array_merge(...$nested);
来源：http://dali.chenlongwang.top/Article/details/gt2ffkcgvap.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfwapohj.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gt2stouiohp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2mrnfidcq.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gt2naczpvzv.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gt2mtsiiblk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2chnpnsie.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gt2pkkfluda.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gt2oxuymsfg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gt2vukfanmi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gt2wsserutj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gt2wiidxcjg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xylfe.cn/Article/details/gt2xeaplqse.html

Go:   // 手写 map[string][]T
来源：http://dali.sxryk.cn/Article/details/gt2djkvkwqj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gt2oxdqlwrc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ivvv.top/Article/details/gt2fsivezbw.html

[D20] 统计每个元素出现次数
来源：http://dali.zycfv.cn/Article/details/gt2ubpathog.html

Py:   Counter(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2bpudarsj.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2yrlxjnzh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gt2giybynhw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gt2lzyomezk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gt2qzaksxrr.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gt2rruigzmt.html

Ruby: arr.tally
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftcfqozu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gt2ubliqvwb.html

[D21] 判断是否包含某元素
来源：http://dali.jiagoushi.top/Article/details/gt2izhttjij.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gt2lhhwavmu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2wfgkjhrh.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2kzcikfkj.html

TS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gt2qzfwktoc.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2cevejmxn.html

Go:   slices.Contains(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2znlwwljx.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2amruujmn.html

C#:   list.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2gxkmwbni.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugljvyha.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2taquyzfb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdafutkq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2iyhygobf.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpyxnmrx.html

Java: new ArrayList<>(list);
来源：http://dali.yuanzhike.top/Article/details/gt2sqseezhp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gt2esurtfjl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gt2afxnrejy.html

C#:   new List<int>(list);
来源：http://dali.fzhhl.top/Article/details/gt2odmjxrot.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gt2xwexsoit.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gt2qkmanqdq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gt2zoptdesc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2oycdktha.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2srztybvj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.bjfxy.top/Article/details/gt2kbxajxwn.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gt2uhvihgsl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gt2flluuwoy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gt2lqhaqovx.html

[D24] 字典 / Map 基本操作
来源：http://dali.shzxlz.cn/Article/details/gt2zmbpzxje.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fzhhl.top/Article/details/gt2dwosjmgy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gt2mrtckmxf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guowangkeji.top/Article/details/gt2peiliemn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2qdkzaivi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gt2fpallpfg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gt2yxzpiyje.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gt2cwqsrahe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daxiang520.top/Article/details/gt2jwztwpxb.html

[D25] Set 集合去重与交并差
来源：http://dali.gaohongyu789.top/Article/details/gt2uekbgwod.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gt2shagunwo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hysaishi.cn/Article/details/gt2rehzxjro.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gt2tedcbhaq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gt2jvkmixpv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gt2yzewvoaq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.andypj.xyz/Article/details/gt2tmqnklep.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gotoacloud.top/Article/details/gt2ruvuwyhk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgfzy.top/Article/details/gt2jifxqxgd.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gt2ckwsskso.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2lbklwxpn.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2abgwxsek.html

JS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gt2dxlwagbi.html

TS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gt2wefvvscd.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gt2seoysqmt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.c1oappe.top/Article/details/gt2cmzpconj.html

Ruby: arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gt2kbwfzwaq.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdmtlrry.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2vnquhinu.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gt2yxdgmwra.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2tlbvqdch.html

[E01] 拼接字符串
来源：http://dali.aizwys.cn/Article/details/gt2aolvhaya.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gt2fogynbbi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cheryme.top/Article/details/gt2zalkfbki.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gt2ypdexzdk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gt2opnuacaq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gt2hsmxvzsa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gt2xqvgovfj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gt2zxvqlrbp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2rtolpocz.html

[E02] 重复字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzjoqtkx.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2juqxhxfe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2gxjlfjke.html

JS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gt2ullnjarx.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2whudusqb.html

Java: "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gt2ikgvgqkt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gogol.net.cn/Article/details/gt2emwopfvm.html

Ruby: "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gt2sskhlgoy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tian-w.cn/Article/details/gt2umhudvsq.html

[E03] 截取子串
来源：http://dali.316326.xyz/Article/details/gt2gqoojuhq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgfzy.top/Article/details/gt2fgdwxwsj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2tibqwwho.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gt2xgxworel.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2ktzbmuhw.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gt2sihjvrxe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aibaodan.cn/Article/details/gt2vkwaueez.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxuanxn.top/Article/details/gt2ncwadzhq.html

C#:   s.Substring(1, 3)
来源：http://dali.wangdashe.top/Article/details/gt2byeegwmx.html

[E04] 查找子串位置
来源：http://dali.gogol.net.cn/Article/details/gt2frpdjftz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gt2yhrecvex.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gt2rxkdzpmg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgpzwizd.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2ditdjhbx.html

Java: s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gt2utwtfzjw.html

Go:   strings.Index(s, "x")
来源：http://dali.hysaishi.cn/Article/details/gt2jsfgwwvj.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2nzclhaog.html

C#:   s.IndexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2pcsdbdch.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnqzz.top/Article/details/gt2ailgecqn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj202588.top/Article/details/gt2hugwjhxk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.bjfxy.top/Article/details/gt2yceovixs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2txsjmkbc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hywenlv.cn/Article/details/gt2fcmnlexc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2thjwklbt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gt2nsrevpfe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cdnleiting.top/Article/details/gt2gfazstaz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daria6918.cn/Article/details/gt2stbfzbbo.html

[E06] 替换子串
来源：http://dali.ydzc1.top/Article/details/gt2vydhitsj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnxiqzzz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rphzqama.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2vnwshwcw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2xhabmfxw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2ilmobipv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2fnxehmhn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2dhwjxgdn.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2jakgtmsb.html

[E07] 按分隔符拆分
来源：http://dali.0kj1m.cn/Article/details/gt2vqmtkclj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fengsongda.top/Article/details/gt2quauxnse.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2wmokuqvh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzetgfgw.html

TS:   s.split(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcfncgll.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gt2uzwknvqh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2hcockzlf.html

Ruby: s.split(",");  s.split
来源：http://dali.wangdashe.top/Article/details/gt2fltkmysu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cheryme.top/Article/details/gt2spzswubq.html

[E08] 数组按分隔符合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzbtbbqh.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gt2njoiabvm.html

PHP:  implode(",", $items);
来源：http://dali.sysykeji.top/Article/details/gt2qmencdeg.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ertoysgd.html

TS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gt2gofkxavm.html

Java: String.join(",", items)
来源：http://dali.redwolf501.top/Article/details/gt2exosvnwk.html

Go:   strings.Join(items, ",")
来源：http://dali.hnxiangtu.top/Article/details/gt2seqabray.html

Ruby: items.join(",")
来源：http://dali.xziqi.cn/Article/details/gt2gpqukpvm.html

C#:   string.Join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gt2osqhbfjt.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gt2lonzcfof.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.mhx1999.top/Article/details/gt2viqlkpek.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2chekmyht.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjxaxkqe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2snruxnqh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kacwwolj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gt2uivynmjw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gt2fcyfmhzy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gt2algkhhns.html

[E10] 左侧补零 / 定长填充
来源：http://dali.snrcjt.cn/Article/details/gt2vihafseq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2zpvxbtqz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gt2inmdeesh.html

JS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2cpsbezoc.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gt2oucbfuyk.html

Java: String.format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gt2zxhdczrm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gt2ybfhboim.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2fkkelyvt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangdashe.top/Article/details/gt2pglxaszt.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gt2xapilhkj.html

Py:   s[::-1]
来源：http://dali.hnqzz.top/Article/details/gt2taaukjwb.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gt2oppuzdow.html

JS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2mxaaufzc.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcbfffxt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwnlipbf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gt2cvueiuhz.html

Ruby: s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2teblgwvl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gt2sqysbtzp.html

[E12] 统计某字符出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzttmunf.html

Py:   s.count("a")
来源：http://dali.gzhubu.top/Article/details/gt2zjyearvw.html

PHP:  substr_count($s, "a");
来源：http://dali.fengsongda.top/Article/details/gt2kedjkrvn.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gt2vzptkocu.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gt2goqkknec.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mudteyaj.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gt2tbhozlbf.html

Ruby: s.count("a")
来源：http://dali.316326.xyz/Article/details/gt2pilfkiqm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gt2vnswgysa.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2mgdmyfdd.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owgsmwef.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rorvkksw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2awhtqfyn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gt2qeupaxsw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2kbjvodxr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2dlopgdpm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gt2voidbcpj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.meibo888.top/Article/details/gt2hxdwedmn.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxykcclk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gt2wuchwycj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gt2rojjynwi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivnvugmr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dashuyun.cn/Article/details/gt2hdgdpfpj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenlongwang.top/Article/details/gt2bhkbrlgr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gt2kcdvtftx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvqntgtv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gt2mpzussik.html

[E15] HTML 转义 / 反转义
来源：http://dali.tanke756.top/Article/details/gt2ugpznjmv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gt2ddvhnufy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gt2gjupitgk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2jgercdzv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gt2rfvwotzn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmqjxwae.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fltibplj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2oalvpfgc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2biuzlogo.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwebeph.html

Py:   f"{1234567:,}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2wixefgtn.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gt2jtowumyi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gt2pszlzkre.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gt2spzzelvs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gt2oibnpyac.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yvedp.cn/Article/details/gt2rbvxtatx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2ksnhctmi.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gt2wpelcyop.html

[E17] 首字母大写
来源：http://dali.cdnleiting.top/Article/details/gt2mfdztdoy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gt2oeqnjrwl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.iojbl.cn/Article/details/gt2zjtizhcj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gt2touftvsc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gt2hesybqbv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gt2rbiauwcd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2wyngvpme.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gt2nfpyiikk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gt2zvfesxqc.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtrsitze.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gt2kmbtklck.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgfzy.top/Article/details/gt2djcycdbj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2kamozuqs.html


<!-- 参考信息 -->