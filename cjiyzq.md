代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.zycfv.cn/Article/details/gttakpaksz.html

Java: Collections.reverse(list);
来源：http://dali.shzxlz.cn/Article/details/gtnnteimzh.html

Go:   slices.Reverse(arr)
来源：http://dali.xuanzx.com/Article/details/gtdhmrrksx.html

Ruby: arr.reverse
来源：http://dali.yj20258.top/Article/details/gtzgefekwh.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gtsfefldmx.html

[D12] 查找元素下标
来源：http://dali.jqgufenzy.top/Article/details/gtnzediiyg.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtmzxfmntp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gzhubu.top/Article/details/gtbabgcjov.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtfinsvumd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtajjaticw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gtojdtzgwp.html

Go:   slices.Index(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtzfaagakf.html

Ruby: arr.index(x)
来源：http://dali.ivvv.top/Article/details/gtvnmapzuy.html

C#:   list.IndexOf(x);
来源：http://dali.ppjwa.cn/Article/details/gtesevzwqi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gtxlwbglul.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gtqtnotiih.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtuwpkkfph.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtwnwvoehl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthstnefkr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sxryk.cn/Article/details/gtqyhedocg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gtvfnxrosl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yanxiufei.cn/Article/details/gthzmrrcey.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gtwjbizrro.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cheryme.top/Article/details/gtkeoccddr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dashuyun.cn/Article/details/gtosdymwtf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtuspxnqwq.html

JS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtldwetduu.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtvwrwlrnk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guannengcc.top/Article/details/gtnqudqxik.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtlvvunkdw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gteoyympcj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtqypovbxj.html

[D15] 去重
来源：http://dali.ehwqpu.com/Article/details/gtskvruqkc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gtnmzalbff.html

PHP:  array_unique($arr);
来源：http://dali.andypj.xyz/Article/details/gtvjwfqvoq.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtqnyltqgz.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtwzpoaibc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.bjfxy.top/Article/details/gtuocjdwoe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jlsjyb.cn/Article/details/gtmywnbevq.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gtsicbnzcn.html

C#:   list.Distinct().ToList()
来源：http://dali.jianghu66.top/Article/details/gtayyvgmoc.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gtwzbpdrvh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gtuqzhuxil.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcnmvrvx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtodmawdbh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtbvidewwy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hywenlv.cn/Article/details/gtwhlhywly.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gteskxdkxh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sxryk.cn/Article/details/gtzynvrbwu.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbgwpvaf.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gtrlwkgdwx.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gthttxbdua.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtwsjjubpm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hammf.cn/Article/details/gthitotodm.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywsidiaw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gtuewzmyci.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtewucyoek.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gtvxtwkrsv.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gtylltpgva.html

[D18] 扁平化嵌套数组
来源：http://dali.hywenlv.cn/Article/details/gtzrptknjy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.svipenyu.cn/Article/details/gtqsrupveb.html

PHP:  array_merge(...$nested);
来源：http://dali.shangyingyoupin.top/Article/details/gtdoaglfgn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenzaomai.com/Article/details/gtrtyyqczm.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxaxwxip.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtisklaxpp.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcqxgray.html

Ruby: nested.flatten
来源：http://dali.chenlongwang.top/Article/details/gtdbxdinpr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtsrvotpvg.html

[D19] 按字段分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclerdywb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuanzhike.top/Article/details/gtgzkynyoh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daxiang520.top/Article/details/gtyqsvrnjc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gtvwrdcekm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gtsuxlzeqd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.meibo888.top/Article/details/gtrqosniei.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gtrovpxcna.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gtvlmbdpdt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gtcjfbunts.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gtdnpqvmsn.html

Py:   Counter(arr)
来源：http://dali.shuidangran.top/Article/details/gtebtkkuyw.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtkjztbbyj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtmylaajtl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtceaacmqn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ydzc1.top/Article/details/gtywelqacc.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gtatzcxsji.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gtzbwyiclu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gttfuxynht.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gtdqlsixaq.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtbchbmoxw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtqwzuzrfl.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gtgtjwtvik.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtgngwnhvw.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtpdttokyr.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtemcfwrzl.html

Ruby: arr.include?(x)
来源：http://dali.nanxinkj.top/Article/details/gtytrwlgmg.html

C#:   list.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtcdckoelp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aizwys.cn/Article/details/gtghptkidc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gtcimniqxl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnqzz.top/Article/details/gtfanisopv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtbpuoovos.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gtikdqzmcr.html

Java: new ArrayList<>(list);
来源：http://dali.jqgfzy.top/Article/details/gtnansodju.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sysykeji.top/Article/details/gtunxkztwu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gtvwjydtha.html

C#:   new List<int>(list);
来源：http://dali.aizwys.cn/Article/details/gtbcpeqtae.html

[D23] reduce 累积计算
来源：http://dali.svipenyu.cn/Article/details/gtivdbfprj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yvedp.cn/Article/details/gtbskqlzfx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejrhittc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gtdepvkmjo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gtxldvzikw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenzaomai.com/Article/details/gtcprqrwfl.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtbufajsgg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gtjiwebcqj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aizwys.cn/Article/details/gtrtxapegr.html

[D24] 字典 / Map 基本操作
来源：http://dali.daria6918.cn/Article/details/gtmryvucox.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.snrcjt.cn/Article/details/gtgwbqsvri.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.kuanghao11.cn/Article/details/gtudugluol.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gtnvrnhvlj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtcwgtybvq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj202588.top/Article/details/gtapzsqxjm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtpksanena.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.redwolf501.top/Article/details/gtxitfolgj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nwbrower.top/Article/details/gtkeixkjre.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gtiyuuutzo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.andypj.xyz/Article/details/gtedvcvqoo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yongpay.top/Article/details/gtuntyaoid.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvahypjol.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gtqufvebqp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ehwqpu.com/Article/details/gtkswgaxhp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gtnlyupkax.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yonumen.top/Article/details/gtkdrjixqe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daxiang520.top/Article/details/gttlvbslkd.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnsgkqwe.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gtktsrymvw.html

PHP:  implode(", ", $arr);
来源：http://dali.andypj.xyz/Article/details/gtqdkwayrf.html

JS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtbuycpyjs.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtleitraeo.html

Java: String.join(", ", list)
来源：http://dali.yj20258.top/Article/details/gtxvqjbbiy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gtcrijtejz.html

Ruby: arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtzdpmtnlh.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtccnbjtqy.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtuzfjbqcs.html

E. 字符串处理
来源：http://dali.ybcxt.top/Article/details/gtzhecrqgv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtcxyefnky.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnimolwmx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jyoumei.cn/Article/details/gtuivujlwg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gtlhxtwtbx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtgkcysnix.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtblfluzeg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shzxlz.cn/Article/details/gtasvoytbr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guowangkeji.top/Article/details/gtwmrykoqf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnxiangtu.top/Article/details/gtkqccommm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtipanamlo.html

[E02] 重复字符串
来源：http://dali.zhongyouzk.top/Article/details/gtykccwywi.html

Py:   "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtstlfcqgi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.mhx1999.top/Article/details/gtwyzykevf.html

JS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtykfukljy.html

TS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtcbeccsdk.html

Java: "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtwdeknqkn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gaohongyu789.top/Article/details/gthbbacdes.html

Ruby: "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gthikfvjgb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gtgddpxsgr.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gtjlmapocq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuetiantiany.cn/Article/details/gtepzogegw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtnvhigblw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtmhxynfju.html

TS:   s.slice(1, 4)
来源：http://dali.meibo888.top/Article/details/gtduuwiyqk.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtpqpobopj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.snrcjt.cn/Article/details/gthwwavkln.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sufxvd.cn/Article/details/gtpqwqkkzq.html

C#:   s.Substring(1, 3)
来源：http://dali.jlsjyb.cn/Article/details/gtxllhhgkf.html

[E04] 查找子串位置
来源：http://dali.sufxvd.cn/Article/details/gtidglrutn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtxrppkrym.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gtxbovtucc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigufen.top/Article/details/gtsufeuhft.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtzvasadvs.html

Java: s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gttbrvxrhi.html

Go:   strings.Index(s, "x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkdbnrkv.html

Ruby: s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtcgxalfcc.html

C#:   s.IndexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtueyksgac.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gtnehccoxp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jiagoushi.top/Article/details/gtmflxghbj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yueranfly.top/Article/details/gtiwrhvzgx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtxktccxov.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.0kj1m.cn/Article/details/gtneeocpcl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtfuiimszk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gzhubu.top/Article/details/gtccqcfxme.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.haohaochexian.top/Article/details/gtgbljnaoa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtonewgwrr.html

[E06] 替换子串
来源：http://dali.wangshuangyany.cn/Article/details/gteiexhzvh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gttqwsmfei.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gtvotpnpbd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvgnpojv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtnpatnxdg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtvzbdujcz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gtgfdyutcf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtndthhwzz.html

C#:   s.Replace("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtejkjuywq.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gttopqnmmv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.quarkkingdee.top/Article/details/gtcxycrspw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtoyqfsjrd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyvogfti.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gtvwijdmfb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cqqwz.cn/Article/details/gtvrhxkwfp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.316326.xyz/Article/details/gtzsknqmie.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gtekbmztay.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gtyejxsbzw.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gtkbznheou.html

Py:   ",".join(items)
来源：http://dali.pengpengdd.cyou/Article/details/gtdswvglxx.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gtexvcfyuq.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtzvwrqqtv.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtlxotrmdy.html

Java: String.join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gtdapodsoz.html

Go:   strings.Join(items, ",")
来源：http://dali.mhx1999.top/Article/details/gtpohqfjti.html

Ruby: items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtzdnzdoic.html

C#:   string.Join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtmctglljp.html

[E09] 去除所有空白字符
来源：http://dali.iojbl.cn/Article/details/gtyredpnku.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenlongwang.top/Article/details/gtffmfghvc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gzhubu.top/Article/details/gtbhqlkosr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gtvbvooguz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gtvsrkvnzi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtgsspqakw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daxiang520.top/Article/details/gtxhdjzygn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgodvqpwd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqejiudvj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gthqkredty.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtafpqsmcr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shangyingyoupin.top/Article/details/gthkisrbpf.html

JS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtyxvnlbjp.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtpzgxmsll.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtycrwfjfu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtglvozfur.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtigjnnohd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtacdfepzl.html

[E11] 反转字符串
来源：http://dali.nwbrower.top/Article/details/gthimjtegv.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtxbjpqwsf.html

PHP:  strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtwqonqjuy.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtitxojvsr.html

TS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtrxfdvbzp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtfcchslmh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nwbrower.top/Article/details/gtpcifdmhf.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gtkswxneyf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtftmqpykg.html

[E12] 统计某字符出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtkapfxkwf.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gttkdmwhae.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gtteglumbu.html

JS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gtbeswuxad.html

TS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtstjnsryo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.kuanghao11.cn/Article/details/gtkhdgbbix.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gtlibykpmt.html

Ruby: s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtogcltrvv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gtinbwvpcm.html

[E13] 逐字符遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtzptuozoq.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtnxnmjm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuanzx.com/Article/details/gthwcbpmof.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtawsnwhgl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtdqsmlqlu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtmtufxpwc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258.top/Article/details/gtgcsgbwlv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gtoskmncpw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtcswvhbei.html

[E14] URL 编码与 Base64
来源：http://dali.birdmap.top/Article/details/gtgptifydl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gtqsggikrf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gogol.net.cn/Article/details/gtbmwywdcp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gtntnawirx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sxryk.cn/Article/details/gtpwkopsad.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shuidangran.top/Article/details/gtjlawuuah.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnqzz.top/Article/details/gtyfuihoes.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gtafphbalg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gtwfopzbhz.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenlongwang.top/Article/details/gtfklawdqb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gtpwgiqiel.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gtmmasazhb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtptvuticm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.meibo888.top/Article/details/gtnyajkvbv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhongyouzk.top/Article/details/gtpnfllecb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gtrpivebfs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigufen.top/Article/details/gtikthjpfr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenzaomai.com/Article/details/gtzuicckrb.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gtowhsxdwi.html

Py:   f"{1234567:,}"
来源：http://dali.xuanzx.com/Article/details/gtwyqlrtha.html

PHP:  number_format(1234567);
来源：http://dali.snrcjt.cn/Article/details/gtgamwhqpa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gteqxrofqv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtmwnvlgjv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gzhubu.top/Article/details/gtzwfkfupu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gtuvtonccp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gotoacloud.top/Article/details/gtqdikxuxz.html

C#:   1234567.ToString("N0")
来源：http://dali.wangshuangyany.cn/Article/details/gtllhcpdai.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gtiaasores.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gttezqarcx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gtmlmuvdep.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjbvwmtc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtodyupogt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtpjwqlthv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwvgobwp.html

Ruby: s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtplevecaa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhixingplan.top/Article/details/gtwjzfkkqt.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gtyahdzxxl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hammf.cn/Article/details/gtdufkgruq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yueranfly.top/Article/details/gtskzxqkwl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtualqugin.html


<!-- 参考信息 -->