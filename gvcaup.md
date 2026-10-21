代发 wailian999

[D11] 反转数组
来源：http://dali.nanxuanxn.top/Article/details/gtmgrdgsrk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guowangkeji.top/Article/details/gtplwjgcen.html

PHP:  array_reverse($arr);
来源：http://dali.ivvv.top/Article/details/gteuwvkzib.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xziqi.cn/Article/details/gtidjctfgq.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gtgcmwgmar.html

Java: Collections.reverse(list);
来源：http://dali.316326.xyz/Article/details/gtrxykpnpf.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gtkuxrursv.html

Ruby: arr.reverse
来源：http://dali.fengsongda.top/Article/details/gthtwfasrv.html

C#:   list.Reverse();
来源：http://dali.zycfv.cn/Article/details/gtscsbgjxl.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffhfeaqy.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbyldfwr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gzhubu.top/Article/details/gtetqusizd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gtrnuyjjjj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnwwmykc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhengqikj.top/Article/details/gtnzusbieo.html

Go:   slices.Index(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtctgnjrva.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gtvetehbby.html

C#:   list.IndexOf(x);
来源：http://dali.c1oappe.top/Article/details/gtyszjtwsx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuanzx.com/Article/details/gtexdjxtro.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258888.top/Article/details/gtcaixuvqt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgufenzy.top/Article/details/gtfqtwxshx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gterbenesz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtlybcwioo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cheryme.top/Article/details/gtdgrgzlkr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ydzc1.top/Article/details/gtjjzhyhmh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jianghu66.top/Article/details/gtwkpzdyyk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndkqtosf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xinyue.icu/Article/details/gtfipeetfp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gteapxxlld.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtvtyxbujq.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtgxshfxaj.html

TS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtsprzwudb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gtefzzxuza.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gtwdlausll.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtpxwzxgmo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtjrewiixi.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gtucxcfvyk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gttepglzhj.html

PHP:  array_unique($arr);
来源：http://dali.wangdashe.top/Article/details/gthegsljyd.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gthjouweef.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtptstgnfo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gtwqqmblrr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.316326.xyz/Article/details/gtpjizilqc.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gtrahxupbc.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gthctdxaau.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gthkcpnygz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gtqwvggpcg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtfemhtzxo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gtxzmkkjgh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtacplsish.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gtdigzkvxo.html

Go:   // 手写循环累加
来源：http://dali.xziqi.cn/Article/details/gtsdcenxud.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gtrpgnjssn.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gtvzgmtfuv.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gtgdzpgntq.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gtgygbnogp.html

PHP:  max($arr);  min($arr);
来源：http://dali.andypj.xyz/Article/details/gtfibbcnps.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosafdbic.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gtaodnsadq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gteunzbmwy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aizwys.cn/Article/details/gtpdvzrqxf.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gtvdmhewer.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gtrykggupi.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gtzmxooqhc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gtzudxnzeq.html

PHP:  array_merge(...$nested);
来源：http://dali.cashguo.top/Article/details/gtssibtmca.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gtvzfmpuyy.html

TS:   nested.flat();
来源：http://dali.jianghu66.top/Article/details/gtgimyvqhu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gtsbajjjhw.html

Go:   // 手写双层循环
来源：http://dali.yvedp.cn/Article/details/gtgkdpwyrf.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gtcalorsbv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvmosgcl.html

[D19] 按字段分组
来源：http://dali.9152youxi.cn/Article/details/gtfbppouek.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.meibo888.top/Article/details/gtytzfhoud.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yonumen.top/Article/details/gtxoxipeiz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gtznreajag.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtwrhwdkhs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gtkwcnwwyb.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gtklxjwmfw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gtqtjiwfso.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yvedp.cn/Article/details/gtnqbfmmbz.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gtguxvbkwo.html

Py:   Counter(arr)
来源：http://dali.hfpthk.cn/Article/details/gtphuylwln.html

PHP:  array_count_values($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtjvtwceow.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gteiyoxwoo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfslkqaz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhengqikj.top/Article/details/gtzxuiazgu.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gtucsdtgbc.html

Ruby: arr.tally
来源：http://dali.hnxiangtu.top/Article/details/gtzjvqjqgm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gtssraoeca.html

[D21] 判断是否包含某元素
来源：http://dali.aibaodan.cn/Article/details/gtjyqzfhxf.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gtyffczppc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgrbpnlr.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtqbawfkwg.html

TS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gtxbhbhqbx.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gtmfevozff.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gtsltunsgx.html

Ruby: arr.include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtydhayoug.html

C#:   list.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtbwbaydyk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sxryk.cn/Article/details/gtylwbxdqj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gtsqyjsbwr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gtznkrudwt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ybcxt.top/Article/details/gthokyfwzz.html

TS:   [...arr];
来源：http://dali.cucudq.cn/Article/details/gtsueebito.html

Java: new ArrayList<>(list);
来源：http://dali.redwolf501.top/Article/details/gtlljaifqy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgfzy.top/Article/details/gtwietwjaw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yangfankeji.com/Article/details/gtbbqezmct.html

C#:   new List<int>(list);
来源：http://dali.hysaishi.cn/Article/details/gtpvxlppvn.html

[D23] reduce 累积计算
来源：http://dali.jqgufenzy.top/Article/details/gtffxnvyqr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gtshoujrtg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gtefwrzctg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtlhkxbjzb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtrwdifkkt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjeysnixb.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gthmagumek.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gtynlzfzhc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gthgebtfbi.html

[D24] 字典 / Map 基本操作
来源：http://dali.svipenyu.cn/Article/details/gtxfzmswbh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gtmjuwyhfs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zdqjudy.top/Article/details/gthkyzchsp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbzqxyvz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtkmfybuyq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj202588.top/Article/details/gtitovbbls.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gtwlkottgu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gtiavjeyti.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.andypj.xyz/Article/details/gtetfdstei.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gtmdsfovmt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daria6918.cn/Article/details/gtitwvaecv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gaohongyu789.top/Article/details/gtncmmdmqp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xinyue.icu/Article/details/gtlxkyorcb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gtmwtyrhtg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sysykeji.top/Article/details/gtedcseaxi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gtwfkjbyif.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xziqi.cn/Article/details/gtiggapoez.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gtkncjkxdn.html

[D26] 数组转字符串
来源：http://dali.shzxlz.cn/Article/details/gtluocnksb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.316326.xyz/Article/details/gtzimeoooe.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gtodqbsetn.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiagpxerb.html

TS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gthtmdbttz.html

Java: String.join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gtyiepvqjh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtxegtbdgz.html

Ruby: arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtmiycuzfm.html

C#:   string.Join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gthkurbisb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtffyayqwx.html

E. 字符串处理
来源：http://dali.dianchejie.cn/Article/details/gtqhmdrecz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcxzosric.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gtnqfbfexg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dianchejie.cn/Article/details/gtxhbxjktl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtiwwodvfi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtjfypcprn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtcmlxhjjt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtvggkpsdj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuanzx.com/Article/details/gtbcyewpfe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxuanxn.top/Article/details/gtjthzcsix.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtgpcuemdu.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gtrlbnrizg.html

Py:   "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gtuaklfrhz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghipdodf.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtlalacptk.html

TS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtqbuhzimv.html

Java: "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtovytdstz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tanke756.top/Article/details/gtvftvscbj.html

Ruby: "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gtefdqsdkl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gtxxvbevot.html

[E03] 截取子串
来源：http://dali.cashguo.top/Article/details/gtgkwyaxhy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xziqi.cn/Article/details/gtcnnufshx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gthaffnjho.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtyepeerce.html

TS:   s.slice(1, 4)
来源：http://dali.yonumen.top/Article/details/gtyppcvroj.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtkrrplika.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yueranfly.top/Article/details/gtjlnelguk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gtcllbjnpm.html

C#:   s.Substring(1, 3)
来源：http://dali.ybcxt.top/Article/details/gtimqxqpth.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gtxcfpcrfd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtrvxaatmt.html

PHP:  strpos($s, "x");
来源：http://dali.daria6918.cn/Article/details/gtrarfhicr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cheryme.top/Article/details/gtxwibzlva.html

TS:   s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtpllfogmm.html

Java: s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtkspuynfd.html

Go:   strings.Index(s, "x")
来源：http://dali.yueranfly.top/Article/details/gtgxaflsww.html

Ruby: s.index("x")
来源：http://dali.hammf.cn/Article/details/gtizzrrgba.html

C#:   s.IndexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmthdvfb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gtkqmfntdr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gtsvitpeyg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jlsjyb.cn/Article/details/gttiwdqpzk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gtfxwvsxwj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjjciald.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtugoogzaf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.svipenyu.cn/Article/details/gtzwrwffmv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.iojbl.cn/Article/details/gtwfbfmrzv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtkhalgtps.html

[E06] 替换子串
来源：http://dali.zdqjudy.top/Article/details/gtxgrwldat.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gttagyvkkh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhvcmima.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gttbwlsdvg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtvkawruon.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtzlibipqt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtngdayhsc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtnhqkpkae.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtuuvdjzlc.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gtdutovkpx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gtwdqzpkej.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtilglqohk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cucudq.cn/Article/details/gtbbomqryk.html

TS:   s.split(",")
来源：http://dali.c1oappe.top/Article/details/gtisjpygck.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gtsvkqqpfu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gotoacloud.top/Article/details/gtwzjbxqzu.html

Ruby: s.split(",");  s.split
来源：http://dali.haohaochexian.top/Article/details/gtctzairby.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtuxkexayk.html

[E08] 数组按分隔符合并
来源：http://dali.yanxiufei.cn/Article/details/gtujhsujbj.html

Py:   ",".join(items)
来源：http://dali.jqgfzy.top/Article/details/gtlzyepkhn.html

PHP:  implode(",", $items);
来源：http://dali.hnxiangtu.top/Article/details/gthlvvbxkr.html

JS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtmjlzrjys.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtehcgpoqh.html

Java: String.join(",", items)
来源：http://dali.316326.xyz/Article/details/gtdqvuttwe.html

Go:   strings.Join(items, ",")
来源：http://dali.snrcjt.cn/Article/details/gtvaqrbnyq.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtonfzdwms.html

C#:   string.Join(",", items)
来源：http://dali.gzhubu.top/Article/details/gtjkzjllce.html

[E09] 去除所有空白字符
来源：http://dali.feifeiyinyue.top/Article/details/gtyoozzbtz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.9152youxi.cn/Article/details/gtxbdpvgjj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jianghu66.top/Article/details/gtmszxtcdi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtaoywffde.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtmdyyujbv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtynvejlso.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gtjtatjnkb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gtozzesddd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtkgqtlmct.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gtqxcakebi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtqjpmjtee.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xinyue.icu/Article/details/gtgdgjsocq.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijmyirol.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtryvfghtg.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtfqijtfhy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtjeqibquf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtbfvimmao.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daxiang520.top/Article/details/gtljagfeds.html

[E11] 反转字符串
来源：http://dali.jlsjyb.cn/Article/details/gthselxmyq.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gtgivfxprz.html

PHP:  strrev($s);
来源：http://dali.cheryme.top/Article/details/gtynmaeksj.html

JS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtdvoddqtu.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtvngrqnzw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gtgvwvbfpd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cdnleiting.top/Article/details/gtofsnbkkc.html

Ruby: s.reverse
来源：http://dali.iojbl.cn/Article/details/gtqykequam.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gtsqjtgzmd.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gtwhnagdcz.html

Py:   s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gttrooxspl.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gtdwbbduqz.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtvtqvzxgo.html

TS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtdnnpqyts.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258.top/Article/details/gtvyuecato.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gttcwexluo.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gtwttkkvyn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnxiangtu.top/Article/details/gtqxnbepbq.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gtkmspwftm.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gthbuuuldw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hammf.cn/Article/details/gtcyaegnkw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtrnweeouk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtxebzyfqc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtzavtqfgt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hfpthk.cn/Article/details/gttxvlfefh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gtxvltmfob.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtkewrmwyc.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gtrmmkhovi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gtkqphjymy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zdqjudy.top/Article/details/gtkuyuytre.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gtiqqzidfo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gtgeumwjbg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gttaebkaoo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gtgzwqyafm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fengsongda.top/Article/details/gtvfqhupuh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hammf.cn/Article/details/gtkntayqnw.html

[E15] HTML 转义 / 反转义
来源：http://dali.hfpthk.cn/Article/details/gtszdtxutv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gtgurhdyze.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gtiychukrx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cashguo.top/Article/details/gtzbkrgycq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gtexxqdawk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shuidangran.top/Article/details/gtofrpkejy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgfzy.top/Article/details/gtbbdgxxpj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtdfyiueqa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gtmpcykxot.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtnuxjawuk.html

Py:   f"{1234567:,}"
来源：http://dali.dianchejie.cn/Article/details/gtbjoajlpc.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gtotmbqpds.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gthjolksjw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtervyyowt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gtzhxrrwxg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxuanxn.top/Article/details/gtdbsyuauy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gtwibfsoso.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhvmcfgi.html

[E17] 首字母大写
来源：http://dali.cucudq.cn/Article/details/gtpxburpob.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtdesmgwsr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtvcuycahr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtmhjitbbm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtbyowaaro.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gtqyxbrhyo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.0kj1m.cn/Article/details/gtsqlgvhlz.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtyytklilg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gtzvosljid.html


<!-- 参考信息 -->