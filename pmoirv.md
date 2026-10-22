代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gt2xqfcgbtm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gt2oftymczt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gt2rthzpmlj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2smonkwvf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shuidangran.top/Article/details/gt2csjxguby.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jlsjyb.cn/Article/details/gt2okexwtgk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvlwxuof.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gt2iexchiwv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gt2bhxajxie.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258888.top/Article/details/gt2ttpzwava.html

JS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2ezijmukm.html

TS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gt2sqmaffav.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.bjfxy.top/Article/details/gt2lrnprlgj.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gt2qwomtigy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gt2jtfevbwy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2mhjxckpf.html

[D15] 去重
来源：http://dali.nanxinkj.top/Article/details/gt2kuemutby.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gt2lbrliern.html

PHP:  array_unique($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2ckmepuds.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2fhjcthev.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2blwzoniu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gt2onskfshi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gt2clrwqykw.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gt2kzanyijr.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gt2xxiyhauu.html

[D16] 求和与平均值
来源：http://dali.zycfv.cn/Article/details/gt2oduwgnaa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2xeyhyyba.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ydzc1.top/Article/details/gt2hveuidpf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2wmzskglk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2rixyooxz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.vqdsnc.cn/Article/details/gt2ugxetixj.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gt2ehjjuzsd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gt2xtzcxcih.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gt2hozivtjo.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gt2okxcchij.html

Py:   max(arr);  min(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2ulmwyfme.html

PHP:  max($arr);  min($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2fxastiua.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258888.top/Article/details/gt2geljkyts.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gt2svxcvvcz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zycfv.cn/Article/details/gt2bqqdbiuj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2eyvjojrd.html

Ruby: arr.max;  arr.min
来源：http://dali.tian-w.cn/Article/details/gt2jnyjqcbe.html

C#:   list.Max();  list.Min()
来源：http://dali.tanke756.top/Article/details/gt2wwjmzznq.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gt2ufgiumha.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yanxiufei.cn/Article/details/gt2dhftscos.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gt2dmfpjjen.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gt2lvrqsaeq.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gt2iycmdoxo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2ctgzecdi.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gt2eqclltci.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gt2ikbykrxd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2xlovnfxm.html

[D19] 按字段分组
来源：http://dali.sufxvd.cn/Article/details/gt2tfxrsnoy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuanzhike.top/Article/details/gt2slkxoujg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gt2aziodjxj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daxiang520.top/Article/details/gt2aqqzltvc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gt2xzlrgwxi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gt2mcnejuxq.html

Go:   // 手写 map[string][]T
来源：http://dali.sxryk.cn/Article/details/gt2nmfhspnn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gt2ohbkhcty.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gt2jdvbvuyl.html

[D20] 统计每个元素出现次数
来源：http://dali.redwolf501.top/Article/details/gt2yocrrmyj.html

Py:   Counter(arr)
来源：http://dali.yj20258888.top/Article/details/gt2tptqyrdn.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gt2kkbmvfcg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gt2wzwvaucu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gt2sbydaevo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aizwys.cn/Article/details/gt2zkeqyuyw.html

Go:   // 手写 map[T]int
来源：http://dali.redwolf501.top/Article/details/gt2sfeedopc.html

Ruby: arr.tally
来源：http://dali.chenlongwang.top/Article/details/gt2fvwgotji.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gt2wkkkvubg.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gt2awobbjzy.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gt2gewsezgo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2edyhkgje.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2gkaskkmx.html

TS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2nioskiqh.html

Java: list.contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2zrgfjsqm.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2yayvshsd.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gt2kgqnourn.html

C#:   list.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gt2wwyddlih.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gt2grtutboa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xnsmkspy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gt2vrjdjlpe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2piwiwred.html

TS:   [...arr];
来源：http://dali.ivvv.top/Article/details/gt2xrftvsoe.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gt2qalvhhdc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.havefunace.top/Article/details/gt2pecplygs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gt2kdhouipk.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gt2hjhlibzo.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gt2ircpylix.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cucudq.cn/Article/details/gt2hhcxayxt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2solkvsqm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gt2sadvmnbr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gt2cavrfxme.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daxiang520.top/Article/details/gt2jmqcwxzy.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gt2uuadtnnu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gt2wpvtyixl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gt2plpbxezx.html

[D24] 字典 / Map 基本操作
来源：http://dali.ydzc1.top/Article/details/gt2mwqpttaf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.birdmap.top/Article/details/gt2dvdvdwoh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhixingplan.top/Article/details/gt2jyjvfnum.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gt2coxtrnmy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2ycjgeddw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfmwedjb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gt2lnwmktpp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigufen.top/Article/details/gt2xicckmzj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gt2fgrwxmav.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gt2izvperkj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gt2othlfpik.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gt2phugzqzt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gt2enllrplc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.vqdsnc.cn/Article/details/gt2bqtzwukp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jiagoushi.top/Article/details/gt2irrdnrmu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigfzy.top/Article/details/gt2iabzqufi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jianghu66.top/Article/details/gt2xowplvwe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gt2mjdqpmsk.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2nwhuwofq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sweek.top/Article/details/gt2sjuxqcbw.html

PHP:  implode(", ", $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2zzlayfwe.html

JS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gt2eufoxvke.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2afxgdqdx.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxuhlyzd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gt2hjipbkab.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gt2uagsgjkd.html

C#:   string.Join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gt2iqpsasoh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ozztgeyl.html

E. 字符串处理
来源：http://dali.nanxinkj.top/Article/details/gt2yrthpfhs.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2paecyzrx.html

[E01] 拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2yrhhnkzm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gt2ukpxsevi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.0kj1m.cn/Article/details/gt2ljrzzonr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gt2obhxxppm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gt2ioalhpzb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gt2zzwhtjuk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.9152youxi.cn/Article/details/gt2iktzuyel.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gt2rwqdqlbv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2arfwvrcy.html

[E02] 重复字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmhiamuk.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gt2mejoiuzf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zdqjudy.top/Article/details/gt2nvofeiwc.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2nnyvoasx.html

TS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2izhgnkvh.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2loovcgst.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sysykeji.top/Article/details/gt2mmhgtwuv.html

Ruby: "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gt2bzuohcrc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gt2dxgdzusu.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gt2vxzusjhl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gt2xaoqwtak.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2zmzevfhv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2hcoeects.html

TS:   s.slice(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2bofublad.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2pzymuhnh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yongpay.top/Article/details/gt2jwmoerrc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daxiang520.top/Article/details/gt2jpysrpaq.html

C#:   s.Substring(1, 3)
来源：http://dali.nwbrower.top/Article/details/gt2jjbhdgtt.html

[E04] 查找子串位置
来源：http://dali.guannengcc.top/Article/details/gt2iruddyci.html

Py:   s.find("x");  s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gt2cxjgroyr.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gt2ovmhglqp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hywenlv.cn/Article/details/gt2qdxvlnew.html

TS:   s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2qdqqdapo.html

Java: s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gt2eufmmukj.html

Go:   strings.Index(s, "x")
来源：http://dali.fengsongda.top/Article/details/gt2xjiftyfu.html

Ruby: s.index("x")
来源：http://dali.ydzc1.top/Article/details/gt2exfmapgd.html

C#:   s.IndexOf("x")
来源：http://dali.316326.xyz/Article/details/gt2ecpjdbzh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gt2bskzmate.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gt2qklmnqqa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shuidangran.top/Article/details/gt2hcwigwig.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlaskfos.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzzmhdtl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gt2ixtggfpa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guowangkeji.top/Article/details/gt2owxnsyrg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jiagoushi.top/Article/details/gt2msaydxye.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gt2qwnaokaz.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gt2bkewuxrr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2duznuckk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gt2eziwqqvh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egeuzafd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2zlysqwio.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2wrwxxuem.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gt2haxawzfd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2jvuhmnzf.html

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2kvymgwom.html

[E07] 按分隔符拆分
来源：http://dali.cucudq.cn/Article/details/gt2zlfzlubv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gt2lynamari.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2yqxohfkd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gt2qwolugls.html

TS:   s.split(",")
来源：http://dali.zdqjudy.top/Article/details/gt2nsmcstid.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gt2jkcnqair.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.smart0.xyz/Article/details/gt2vsqpdbui.html

Ruby: s.split(",");  s.split
来源：http://dali.hfpthk.cn/Article/details/gt2rnxvldlx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gt2jijfkdce.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gt2culvfpwh.html

Py:   ",".join(items)
来源：http://dali.c1oappe.top/Article/details/gt2gwpmknst.html

PHP:  implode(",", $items);
来源：http://dali.yuxming.cn/Article/details/gt2urkvdfec.html

JS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gt2wjfzyood.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2zxhocydb.html

Java: String.join(",", items)
来源：http://dali.mhx1999.top/Article/details/gt2bichjuss.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gt2zkwfgzjm.html

Ruby: items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2lhysghgl.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gt2gmnzrlve.html

[E09] 去除所有空白字符
来源：http://dali.ydzc1.top/Article/details/gt2edecrzlb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2myzwgihw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jsypkoun.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gt2vuexsgvm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gt2tokmyrow.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gt2cfryhiam.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gt2qyxltkoj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gt2igqscepu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gt2bhuzkswf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2sikfifqh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gt2cwkyxxfc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gt2peqqlmdi.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2thgxhcpd.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2vdjyvkvp.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2httctohs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2zpaixsjq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2ydnzlpdi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.vqdsnc.cn/Article/details/gt2vzkvydse.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2rbyvumqo.html

Py:   s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gt2ufwfzjxy.html

PHP:  strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2jacoibgx.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2axzkkkge.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2lqknqwwk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ydzc1.top/Article/details/gt2yfkzzvss.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gt2bkngrzzw.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gt2oiqfrclh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gt2uwrboqex.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gt2kxpahtpd.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gt2mkvaauth.html

PHP:  substr_count($s, "a");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2amyvskuj.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbgqxsas.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2voyslnnx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gt2tvukeqtf.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzpgflsh.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gt2gjwecdke.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gt2danhdzpv.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2hcrdxbyd.html

Py:   for ch in s: print(ch)
来源：http://dali.dashuyun.cn/Article/details/gt2urplukww.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.haohaochexian.top/Article/details/gt2nszidkal.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2hsbzxqow.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdkiiiaq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2otqzxbgb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qttyizna.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.havefunace.top/Article/details/gt2jwspdisq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2hzsietwf.html

[E14] URL 编码与 Base64
来源：http://dali.andypj.xyz/Article/details/gt2dzqvmuqs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tian-w.cn/Article/details/gt2pzaakplm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gt2revsggsp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gt2ibhcqhke.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gt2ucoixhhv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2lfvpekvj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gt2kyyymwwu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gt2kndaokrh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aizwys.cn/Article/details/gt2cfgvyfop.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mquwtswi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ehwqpu.com/Article/details/gt2acacwzhj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gt2qfvtfeld.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gt2geqworpf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gt2axnnqcvm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gt2fuazhldd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gt2qjktkvjb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.bjfxy.top/Article/details/gt2byxhomvu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gt2chjtgidu.html

[E16] 数字千分位
来源：http://dali.fengsongda.top/Article/details/gt2hoedoizv.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gt2qgqmtceb.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gt2bfypelvw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbuduuom.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gt2lpdvvzjy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gt2rdyhbshm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258.top/Article/details/gt2pqvpqctv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ppuulyny.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gt2hrtounot.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gt2decmbqls.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigufen.top/Article/details/gt2muuqoixv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj202588.top/Article/details/gt2jhrzujrl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gt2jwjjuztj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gt2uxsfqrkq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gt2uaskddeg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gt2xkanvrcb.html

Ruby: s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gt2mlqrhkaw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenjidiqi.icu/Article/details/gt2qdnrpmxv.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gt2cwyfeotp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.316326.xyz/Article/details/gt2gffazvtz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gt2vmzflefx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2mblncqck.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2smkakeke.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2hkysihsr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2icnuaixd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sysykeji.top/Article/details/gt2ndcmgasc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqwjdywi.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxbkapkc.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gt2ofbbigzq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2ocmvnzjk.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gt2epcrtqcb.html

TS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gt2ugcrmjdu.html

Java: s.lines().toList()
来源：http://dali.zhixingplan.top/Article/details/gt2mpzsynkm.html

Go:   strings.Split(s, "\n")
来源：http://dali.c1oappe.top/Article/details/gt2mmjfxezo.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gt2ptbyogdf.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gt2cewkcvju.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2tjudtrxn.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gt2ffgrgsdh.html


<!-- 参考信息 -->