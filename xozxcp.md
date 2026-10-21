代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gtxnhkocfi.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gtghxeybft.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gtutdiplof.html

Ruby: arr.reverse
来源：http://dali.chenzaomai.com/Article/details/gtsuyejmtt.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gtxjwmfdpz.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gtnjjlgpbw.html

Py:   arr.index(x);  x in arr
来源：http://dali.ivvv.top/Article/details/gtmuegjiww.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtwrymohqu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynlqflxx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gtnhbduazu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gtlxjyegvr.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtrkjplili.html

Ruby: arr.index(x)
来源：http://dali.hywenlv.cn/Article/details/gtmibgfvpz.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gtvuoedyuj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtwwpjbfbv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gtjcmoqenf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtraqcaafo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtatklsevc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtvjiealme.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzomsswig.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zdqjudy.top/Article/details/gtwwhfqhrp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gtcedtmcrn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gttevesfyu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gtzcvwpvgh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtphhczyic.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtvcvcmuow.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtbjqnxbfa.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gtfbllmnkm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gtjyngccbt.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gttyvhdrat.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtypjmuhqy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gtsfklwiyn.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtkkgovubo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gtqemxzayd.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gtopjypwja.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtlvcsmgco.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtptpueomt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuanzhike.top/Article/details/gtuobkrozk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fzhhl.top/Article/details/gtwlhihwnw.html

Ruby: arr.uniq
来源：http://dali.tian-w.cn/Article/details/gtpfrvkamy.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtffkgsnqy.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgzbmywk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yonumen.top/Article/details/gtivbaevae.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tianlin.xyz/Article/details/gtxcrwdndg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtuemtooyr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtyxfilmxc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gtizygxwty.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gtmyuffwsw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtnnmhoipi.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gtowqavipx.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gtguycybzq.html

Py:   max(arr);  min(arr)
来源：http://dali.smart0.xyz/Article/details/gtgiwzlyxy.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtammjodpx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gtanxooghw.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gtvwhyproc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtfbnanopl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gthuhkerje.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gtkzboxevw.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gtiuorwwom.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gtlbforhun.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gtvdggpljr.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gtdursampi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenzaomai.com/Article/details/gtkjzmoqzm.html

TS:   nested.flat();
来源：http://dali.yanxiufei.cn/Article/details/gtoxvscfou.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtgolziimb.html

Go:   // 手写双层循环
来源：http://dali.yongpay.top/Article/details/gtijdyygdn.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gtotljnmgy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.redwolf501.top/Article/details/gtsjpzeivy.html

[D19] 按字段分组
来源：http://dali.ehwqpu.com/Article/details/gtvgclnzpc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gtawrokktb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajigxqsg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.kuanghao11.cn/Article/details/gtzzguovzm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gthvymtlfj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbssxrzi.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gtyqcxgsbt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fengsongda.top/Article/details/gtowzorjvt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gtpcrojtvp.html

[D20] 统计每个元素出现次数
来源：http://dali.chenzaomai.com/Article/details/gtrujjmrli.html

Py:   Counter(arr)
来源：http://dali.cqqwz.cn/Article/details/gtxtmawhwn.html

PHP:  array_count_values($arr);
来源：http://dali.chenlongwang.top/Article/details/gtrgliuket.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gteotuwgav.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gtftdspiwn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.andypj.xyz/Article/details/gtxcoylzea.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gtohfvrayy.html

Ruby: arr.tally
来源：http://dali.wangdashe.top/Article/details/gtchajhswk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gtlwwxzqka.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtgjgfdhqt.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gtofpodqkk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.vqdsnc.cn/Article/details/gtfjyekmpz.html

JS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtdmscxqxs.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtbrzhdjwi.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbbpdgxk.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtplupgzqr.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtrsetxksr.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gtvhzpdljx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gtoxpqkjuw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtfrudnfsh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.kuanghao11.cn/Article/details/gtigmywwkx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gtgevwngof.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtwfufkrhj.html

Java: new ArrayList<>(list);
来源：http://dali.wangdashe.top/Article/details/gtslezlwdj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gtvkmfvelu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gtqcapzsru.html

C#:   new List<int>(list);
来源：http://dali.jqgfzy.top/Article/details/gtebctyuoz.html

[D23] reduce 累积计算
来源：http://dali.pengpengdd.cyou/Article/details/gtqkqpaqfx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.meibo888.top/Article/details/gtldtzrudp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gtslcfqgvf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtkvcvvenq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtjuacshom.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gtcxuupqkk.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gtvupywwvq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.svipenyu.cn/Article/details/gtojytiazt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yangfankeji.com/Article/details/gtmqnspiqi.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetyhclrs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcybvxrs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.birdmap.top/Article/details/gtdoweobxf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtmeqvnlxs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunrjpqps.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gtvlplgrko.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gtgwlpiqff.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gtgzcunxlp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gthbocqskb.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gtrpzvbkbd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zycfv.cn/Article/details/gtnhwrpuos.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenzaomai.com/Article/details/gtzrnpislu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtindmwvlw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gtrdpcaulu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xinyue.icu/Article/details/gtovpxwpic.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gtxzdlbrdo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dianchejie.cn/Article/details/gtehqhwgyc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtxtbfpzfj.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gtkxtjwcid.html

Py:   ", ".join(map(str, arr))
来源：http://dali.0kj1m.cn/Article/details/gtmsgdmqcv.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtshpioujq.html

JS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtdszyhhdx.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtapvtravv.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtsequqedx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gtecvpxknu.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtpwtqsfbw.html

C#:   string.Join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gttnzcpsrb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtlhiempvn.html

E. 字符串处理
来源：http://dali.yueranfly.top/Article/details/gtupoubvkp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvkgwnvxj.html

[E01] 拼接字符串
来源：http://dali.aizwys.cn/Article/details/gtapokfcrj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuanzhike.top/Article/details/gtbsydqphc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.havefunace.top/Article/details/gtbyvcfeml.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtgqikgcbt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtszbhwmtu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gtohfmrrnx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspogcnmm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gtmdqtzzbz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gthrwvfhhl.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gtpokrclgv.html

Py:   "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtjnlvetst.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gtqhkpujav.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gttcoczwbi.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gteqymeday.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtofkuwmlw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gtkldrvmsd.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtefjnhrhw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sweek.top/Article/details/gtdctnncue.html

[E03] 截取子串
来源：http://dali.pycfn.com/Article/details/gtloayzqex.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aizwys.cn/Article/details/gtjbwuepqs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtiehrqsvr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtrrgiyvda.html

TS:   s.slice(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtrnlemilz.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtnxxaohfd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggbftzrm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.vqdsnc.cn/Article/details/gtubnvozea.html

C#:   s.Substring(1, 3)
来源：http://dali.yj202588.top/Article/details/gtvnyyvehy.html

[E04] 查找子串位置
来源：http://dali.bjfxy.top/Article/details/gtyqnqkkih.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtmzoevqka.html

PHP:  strpos($s, "x");
来源：http://dali.yueranfly.top/Article/details/gtpsxhuxni.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj202588.top/Article/details/gteudqutgx.html

TS:   s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtzyhdrfxl.html

Java: s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gtqdjfwkdp.html

Go:   strings.Index(s, "x")
来源：http://dali.jyoumei.cn/Article/details/gtupenicye.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtnxjscxpt.html

C#:   s.IndexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtjagjyuex.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pycfn.com/Article/details/gtbdhlisbg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuanzhike.top/Article/details/gtqmauymmi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.316326.xyz/Article/details/gttjdszpsv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gthryltjnd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.smart0.xyz/Article/details/gtejjdythe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtigqvithc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hfpthk.cn/Article/details/gtmnvoetuy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hammf.cn/Article/details/gtdwzrduwu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.meibo888.top/Article/details/gtxucqmrcg.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqwijugo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtfpwgfibe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gtsepaxkpw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtjehvfuyi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtextectzs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrhfgxks.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtxsxcbdtz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtptbjwzng.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtayzsxkfm.html

[E07] 按分隔符拆分
来源：http://dali.guowangkeji.top/Article/details/gtebpfzdnz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jlsjyb.cn/Article/details/gtinpmwvxs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gthvixgewx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gtjpclhvnd.html

TS:   s.split(",")
来源：http://dali.snrcjt.cn/Article/details/gtuvryibyr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gtwxhucnht.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hammf.cn/Article/details/gtjknbtjfm.html

Ruby: s.split(",");  s.split
来源：http://dali.guannengcc.top/Article/details/gtoypgyioj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gtdwgltxcz.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gtivbkbucw.html

Py:   ",".join(items)
来源：http://dali.cqqwz.cn/Article/details/gtxydukcrt.html

PHP:  implode(",", $items);
来源：http://dali.yuxming.cn/Article/details/gtbdmdfldi.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtdfxhjmts.html

TS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtftmriqgj.html

Java: String.join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gtbcavlibk.html

Go:   strings.Join(items, ",")
来源：http://dali.dianchejie.cn/Article/details/gtczxkvied.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtogaqyimn.html

C#:   string.Join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtuppyufru.html

[E09] 去除所有空白字符
来源：http://dali.yj20258.top/Article/details/gtrmqzyxim.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gtqngscawe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapwjsiyk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtnhionhmz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gttgdyddsh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtgpcrjkxh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhongyouzk.top/Article/details/gthwqcmzwr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gtockyhats.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yonumen.top/Article/details/gtyjbcmqzy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gtzyihcgpq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtmsuzjfls.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gteofnjmui.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtdxorfnrr.html

TS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtbynwanrb.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gthtlfpqmk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gttqstpbdo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtggabajhn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtzvjjjpbn.html

[E11] 反转字符串
来源：http://dali.cqqwz.cn/Article/details/gtsanhrxzv.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtxuhxxpjz.html

PHP:  strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gtlxepijhx.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfypyujsl.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtcumklmqx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyckgysif.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtmkckocsz.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gthyyeyiru.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtydccnucw.html

[E12] 统计某字符出现次数
来源：http://dali.yonumen.top/Article/details/gtpsyutqzr.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtpqxopzxa.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gtycwiysrb.html

JS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtyysxajkm.html

TS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtcaqhjlbf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gtbjzxgfgj.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gtcdnsxyyv.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtxbmloqzc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gtsihbcfks.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gtvzounyes.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gtirubpzpn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gtkxeuxksv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtlyeydglb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtxprfmjap.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtbczaewdm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsxqokng.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gthsaytlpv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gtmxyinynv.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gtlltmqhhf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtlfjatwap.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gtgkuoxanp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gtbnzhvxyz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gtzyzbpwog.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtmbfqgdmj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.316326.xyz/Article/details/gtguhmifvf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gtwvcozivt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtigqbouzo.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gtykvbvtqf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.iojbl.cn/Article/details/gtvcorhpgp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gtixhuhqor.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jlsjyb.cn/Article/details/gtgnvfnmgd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuxming.cn/Article/details/gtgkmpoeeq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ydzc1.top/Article/details/gtknqzaduy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.316326.xyz/Article/details/gtzaiszhjm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gtzcewqivm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtudevcukk.html

[E16] 数字千分位
来源：http://dali.hysaishi.cn/Article/details/gttwdmtonk.html

Py:   f"{1234567:,}"
来源：http://dali.bjfxy.top/Article/details/gtvtgvvrvc.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gtzjvbxryt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtxsxlhaoq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtxdkswxzi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sweek.top/Article/details/gtxefpuvwi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gtvatwqmqh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xinyue.icu/Article/details/gtuvvciavw.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gtczpbavsd.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gthvriduvd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuanzhike.top/Article/details/gtlwwkrder.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gtmwxzpxye.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gtcrzpdvwx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtaqhbruyt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nwbrower.top/Article/details/gtvetyiwyb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdpghomj.html

Ruby: s.capitalize
来源：http://dali.jyoumei.cn/Article/details/gtmorivznc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gtfwxefphg.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gtiencsyoj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gtmoxjibcb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gtluvgmxso.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtdfiqhjkv.html


<!-- 参考信息 -->