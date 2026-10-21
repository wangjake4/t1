代发 wailian999

[D11] 反转数组
来源：http://dali.kuanghao11.cn/Article/details/gtyirrxlgk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gogol.net.cn/Article/details/gtweilocfl.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gturtyxbin.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shzxlz.cn/Article/details/gtacewhuqw.html

TS:   [...arr].reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyfyvvwg.html

Java: Collections.reverse(list);
来源：http://dali.zhixingplan.top/Article/details/gtcwqivugr.html

Go:   slices.Reverse(arr)
来源：http://dali.wangdashe.top/Article/details/gtkjqnzmsd.html

Ruby: arr.reverse
来源：http://dali.ivvv.top/Article/details/gtkmlulhgu.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gtcqnxnsug.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gtjgenwcdd.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuanzhike.top/Article/details/gtuwqmhoyi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtmkbdtzmu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gtdyrnzjix.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtgwedpqoc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.redwolf501.top/Article/details/gtrsxavpog.html

Go:   slices.Index(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtrzulnjhd.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gtqnenegmh.html

C#:   list.IndexOf(x);
来源：http://dali.xylfe.cn/Article/details/gtraqsjjfw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtadoxlnjp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gtvzmknxdk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gtuaecjtqd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtfxhlmove.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtwevqjzho.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gtqvphbdkd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tanke756.top/Article/details/gtmndshkur.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guowangkeji.top/Article/details/gtqbxqfjgz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.smart0.xyz/Article/details/gtldvqhrsl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuxming.cn/Article/details/gtathbbdge.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hysaishi.cn/Article/details/gtfaczhntl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gtwutuhdne.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtpzbtrixn.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtirrzkjod.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.0kj1m.cn/Article/details/gtinzhhfuk.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gteybhsgrs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtsubatlza.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtynhyacjx.html

[D15] 去重
来源：http://dali.yonumen.top/Article/details/gtowpshoxr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gtkcxqsisx.html

PHP:  array_unique($arr);
来源：http://dali.wangdashe.top/Article/details/gtzgqcrffp.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtubdeckdp.html

TS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtskmsddwa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gthurmmjpr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gtgkqhprcb.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdnrdbcb.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gtihrklngb.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gtfzjmbbkh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.0kj1m.cn/Article/details/gthjtubbvq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gtkvvyjjkj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtrxbowbzv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtbwzvgfqr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gtvdsreecp.html

Go:   // 手写循环累加
来源：http://dali.cashguo.top/Article/details/gtararmtog.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tanke756.top/Article/details/gtytuhyuai.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gtbonqftgf.html

[D17] 最大值与最小值
来源：http://dali.jiagoushi.top/Article/details/gtwfpodwlv.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtwlnvhnny.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gtqoutkcbo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gtnvgrvdis.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnagwfidd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gtmibvdibx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtjnoyrqin.html

Ruby: arr.max;  arr.min
来源：http://dali.aizwys.cn/Article/details/gthqucpzrt.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gtjndotqax.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gtnkqfdpaa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fzhhl.top/Article/details/gtmuakecxj.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtojalmyyi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gtzivngzpu.html

TS:   nested.flat();
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqqnbgnt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gtmiwpwdse.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztffewdt.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gtqhutcyyc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtgdlqfpqb.html

[D19] 按字段分组
来源：http://dali.ybcxt.top/Article/details/gtajtwzqww.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gtyhjcfypx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gtuazqacva.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhiwuduotai.top/Article/details/gtzkwqaeog.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gthfqsaztq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xziqi.cn/Article/details/gtvwikylaj.html

Go:   // 手写 map[string][]T
来源：http://dali.jyoumei.cn/Article/details/gtyhfwsrxm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.snrcjt.cn/Article/details/gthrurvffa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nwbrower.top/Article/details/gtxmnccacw.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gtleueenes.html

Py:   Counter(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gthznrhvon.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gtexgqebki.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gtkuyetljs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtkwyxdxiu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gthpnbkrnf.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gtzidvjoig.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gtyfqqkkgk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gtgqjvliob.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gtuuhfftfn.html

Py:   x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbngtevhb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtktayacnd.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtapyonwti.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmktfpvy.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtdpjlibih.html

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtqulzxzsv.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gttsgvfpyk.html

C#:   list.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtuxfqtieu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gtyivcieqf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gticrggjzz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj202588.top/Article/details/gtfyiftojv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj202588.top/Article/details/gtgqpjaqos.html

TS:   [...arr];
来源：http://dali.haohaochexian.top/Article/details/gtholtszxm.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gtxikqlynz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gtyiyvznqp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgfzy.top/Article/details/gtkrpdreyf.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gtgxboeklb.html

[D23] reduce 累积计算
来源：http://dali.daria6918.cn/Article/details/gtdizzshjt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.iojbl.cn/Article/details/gteflexygi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gtujqvsnul.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gthxdorbqh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtgwxbqgoq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cucudq.cn/Article/details/gtgkyuejrr.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtcsdttusl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gtnqderopw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gtlmrmzgbb.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gtinvjtygm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenzaomai.com/Article/details/gtsuvddosl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj202588.top/Article/details/gttphlzjko.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sysykeji.top/Article/details/gtuktqudhp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtfluugmhk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gtabpnlxpz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zdqjudy.top/Article/details/gthwaiaegj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gtiummouxe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gtwqjhmpbr.html

[D25] Set 集合去重与交并差
来源：http://dali.vqdsnc.cn/Article/details/gtpjeiwiwx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gttmlxqzla.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gtwpfkpvnc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgufenzy.top/Article/details/gtkpioouef.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ivvv.top/Article/details/gtkedhquku.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtvuhncgvo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gtufpkyrez.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfqwowsa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtsogtkdwg.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gtjotvyhwh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daria6918.cn/Article/details/gtivpqbchy.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtgfizrckd.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtwmhlctpe.html

TS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtiepxoclt.html

Java: String.join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gtisbynxik.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldbbxilq.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtfmhlbujo.html

C#:   string.Join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtmcppzrep.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcunsbvc.html

E. 字符串处理
来源：http://dali.hfpthk.cn/Article/details/gtnpylhvnq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtaqvnvlqs.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtwdgypaab.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtfrfwrpcj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gtfluoewmj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtaffoynwj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtduwwuidm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gtrmcjwmju.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gtutrixyqz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hammf.cn/Article/details/gtwrpabxle.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj202588.top/Article/details/gtihtdupyb.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gtmxwbbfje.html

Py:   "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtmvuxfaxa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cdnleiting.top/Article/details/gtihcscowu.html

JS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtbzmfrhdy.html

TS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtuggbegyy.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtxymeeiky.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sxryk.cn/Article/details/gthhyprbji.html

Ruby: "ab" * 3
来源：http://dali.hammf.cn/Article/details/gtwklcgpwt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtqimsrmpg.html

[E03] 截取子串
来源：http://dali.hnqzz.top/Article/details/gttgzyqnrt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsqwyfzd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtsrwszeau.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtosayvcrz.html

TS:   s.slice(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtyknikqyz.html

Java: s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtikyzxlql.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtjrurwwdb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhixingplan.top/Article/details/gttjzklrmx.html

C#:   s.Substring(1, 3)
来源：http://dali.pengpengdd.cyou/Article/details/gttlgzfzuw.html

[E04] 查找子串位置
来源：http://dali.yuxming.cn/Article/details/gtcgrbivgu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtixeiuguj.html

PHP:  strpos($s, "x");
来源：http://dali.yuxming.cn/Article/details/gtyszpdqxo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.feifeiyinyue.top/Article/details/gtayightmy.html

TS:   s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gtubjdwwmc.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtvrrztzhz.html

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gttwvpnidq.html

Ruby: s.index("x")
来源：http://dali.pycfn.com/Article/details/gtxqcjrnbd.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtyhjxfhhw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbekpyzd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ydzc1.top/Article/details/gtqxiscqir.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gtmkrdqqqx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtwsxibogk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zdqjudy.top/Article/details/gtmtdygrmy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gtkokyorxm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gtupsrxumx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtbvfilhna.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtryuzxrbt.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gtiyujaugm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtnwjnkvuh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cheryme.top/Article/details/gtehsuhkgo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtmokblbia.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtyrgjyxez.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtyplepmlv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtmpiajblh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.meibo888.top/Article/details/gtytjxqrss.html

C#:   s.Replace("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtyccluzrl.html

[E07] 按分隔符拆分
来源：http://dali.iojbl.cn/Article/details/gtswgrtmph.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.vqdsnc.cn/Article/details/gtuvevvrzw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258.top/Article/details/gtxmroqlle.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuetiantiany.cn/Article/details/gthbyyezjv.html

TS:   s.split(",")
来源：http://dali.xylfe.cn/Article/details/gtpxcpkoto.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gtkdfezvmv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yanxiufei.cn/Article/details/gtmbscnejj.html

Ruby: s.split(",");  s.split
来源：http://dali.shzxlz.cn/Article/details/gtjgrsrjlg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gtcfgqveot.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolsxbfso.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gtemvrzqqq.html

PHP:  implode(",", $items);
来源：http://dali.andypj.xyz/Article/details/gtgdkhiref.html

JS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtjnycxxtw.html

TS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtrhmvprpu.html

Java: String.join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gtseoxddoy.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gthmwrqmjq.html

Ruby: items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gteivtpztk.html

C#:   string.Join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtycrbkccq.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gtqdkretuo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xinyue.icu/Article/details/gtiurwwmou.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gtrpmtieud.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtxetgwaja.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtmizfxirt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gtudktlcwr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gzhubu.top/Article/details/gtbjddjwgl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gtksssqkdq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jianghu66.top/Article/details/gthzhluhre.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gtdrnghhas.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yonumen.top/Article/details/gthnlytesd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gtnkksdzyt.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwaapatt.html

TS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtdpnsncfs.html

Java: String.format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtdheafsik.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtyyaavpaf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtjwrnryhd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.svipenyu.cn/Article/details/gtzrrtjprp.html

[E11] 反转字符串
来源：http://dali.hywenlv.cn/Article/details/gtwzwsgdvs.html

Py:   s[::-1]
来源：http://dali.ydzc1.top/Article/details/gtssvvevfu.html

PHP:  strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtzmosuhgu.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtbwnxuohx.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtppckhbop.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gtwjldcupf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtmigraqsm.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gtvbrrfmdm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gthenlzeqj.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gtquevwcrb.html

Py:   s.count("a")
来源：http://dali.zycfv.cn/Article/details/gtwbicipgz.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyooqkaz.html

JS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gtyigehsgv.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtaedjblcg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gtluzthzfa.html

Go:   strings.Count(s, "a")
来源：http://dali.cheryme.top/Article/details/gtewztcliu.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtrpelkvwx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shuidangran.top/Article/details/gtjoenugps.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtgvgerjbd.html

Py:   for ch in s: print(ch)
来源：http://dali.daria6918.cn/Article/details/gtsychgvtw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daria6918.cn/Article/details/gtcqbdsgiy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtlpdixryp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtbmdqlvnq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjiizsgfa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gthukflmvq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gtdudqycmm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gtykhtvlte.html

[E14] URL 编码与 Base64
来源：http://dali.feifeiyinyue.top/Article/details/gtqawfpzus.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shzxlz.cn/Article/details/gtcrcaqhle.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gtaskqtpkt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dashuyun.cn/Article/details/gtzllmewxv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmzyvrsa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtuocqbded.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shuidangran.top/Article/details/gtsmynelwh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gtuuylhbdx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtaeivrulf.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gtnbvepvws.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gtajwpskpl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtswbwitbd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yanxiufei.cn/Article/details/gtuswnqryz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gtdgznhjzf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.9152youxi.cn/Article/details/gtbecmshhl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtyzlsahef.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gtpunauedm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gtdytzpert.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtrefgpofh.html

Py:   f"{1234567:,}"
来源：http://dali.gzhubu.top/Article/details/gtbajdxlgx.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gtsjkosvmr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtrwesjkdq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gtohucivfg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuanzx.com/Article/details/gtvasqpnqp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gtbctguznx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.bjfxy.top/Article/details/gtmfzewvxv.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovqaqiqk.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gtxutjativ.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gttmimoctk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujepnmfm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtuxdjvgas.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtlcwbwbbs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgjwyiun.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.0kj1m.cn/Article/details/gtgctxodbz.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gtmztsaobw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aibaodan.cn/Article/details/gtdyfehuii.html


<!-- 参考信息 -->