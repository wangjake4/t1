代发 wailian999

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtnvmmftel.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gtfhwrybdk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcilxgymd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gtvuueezav.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtkbvaaswb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gtotenotws.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gtpdvnbkng.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtwqymeljq.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpmkjycj.html

C#:   list.IndexOf(x);
来源：http://dali.yangfankeji.com/Article/details/gtepegffuf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ywan-chungtsiang.top/Article/details/gttndidenc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xylfe.cn/Article/details/gtycqrvecw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hysaishi.cn/Article/details/gtlytfgpqa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknqyyzhg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtvjnamncu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gtcdqjuffr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhoulong.xyz/Article/details/gtxixsxvtz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shangyingyoupin.top/Article/details/gtacvtxami.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtwxafvmfm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhongyouzk.top/Article/details/gtvaphjnht.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xinyue.icu/Article/details/gtieegnfar.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gtwimddnus.html

JS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtmfmfgqbb.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtuvlehhav.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gotoacloud.top/Article/details/gtcbzpkedk.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gtgrmriewj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtichiqqkk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xylfe.cn/Article/details/gtevytyygt.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gtwotpnuac.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gtvvjfiqkj.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gtrmmrtfzr.html

JS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtllhrojom.html

TS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtlvzzuscs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gtgwcfjkwi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gtovmvdqnc.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gttjrwxxmc.html

C#:   list.Distinct().ToList()
来源：http://dali.chenzaomai.com/Article/details/gtaijlsjbm.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gthgeubuvk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtqtecgtev.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gtahostyfk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtndgxytph.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtspdgvdgu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.snrcjt.cn/Article/details/gttwealyyc.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsegsubt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.c1oappe.top/Article/details/gtdctnpehi.html

C#:   list.Sum();  list.Average()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhlyfoeh.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtuqaoxaiz.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gtwcnlbpal.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtinanxsbt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gtvjnhozdt.html

TS:   Math.max(...arr);
来源：http://dali.yongpay.top/Article/details/gtrmyfkvvd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xziqi.cn/Article/details/gtaidicbax.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gthigzotkt.html

Ruby: arr.max;  arr.min
来源：http://dali.haohaochexian.top/Article/details/gtufjghief.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gtcylewasi.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxinkj.top/Article/details/gtwrzyjzvk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gtssmvukoo.html

PHP:  array_merge(...$nested);
来源：http://dali.yangfankeji.com/Article/details/gtmmzcsgyf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gtueidchds.html

TS:   nested.flat();
来源：http://dali.hnxiangtu.top/Article/details/gttczsxfsc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuanzhike.top/Article/details/gtdvraetvq.html

Go:   // 手写双层循环
来源：http://dali.gotoacloud.top/Article/details/gtumlsizpb.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gtjdldjqsi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.meibo888.top/Article/details/gtiicomwng.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gthhkjlqcr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gtpmgbnfuc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gtjhzzewsj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gtandsxviv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtzjekwhts.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gtblnmpjdf.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfdqgqzh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gtviltcejm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hammf.cn/Article/details/gttbzmascq.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczfyzqor.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gtxianfdfo.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gtakmocsbs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtjyunribb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gtncvimoqe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cheryme.top/Article/details/gteffxwraj.html

Go:   // 手写 map[T]int
来源：http://dali.hfpthk.cn/Article/details/gtiahnvhnc.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gtdnlawlxf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhengqikj.top/Article/details/gtzawuqvrp.html

[D21] 判断是否包含某元素
来源：http://dali.dashuyun.cn/Article/details/gtypibjuuy.html

Py:   x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gtxbbmagfz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gteircytrd.html

JS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtybvnwcoz.html

TS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtnhbsyavz.html

Java: list.contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmnskkmn.html

Go:   slices.Contains(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtfomtixvk.html

Ruby: arr.include?(x)
来源：http://dali.gzhubu.top/Article/details/gtnkainppl.html

C#:   list.Contains(x)
来源：http://dali.cashguo.top/Article/details/gtjbajblox.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gtivmxmrzs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gtstgroruc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxuanxn.top/Article/details/gtzaofqxkf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtfbetojgq.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gtzeteubbh.html

Java: new ArrayList<>(list);
来源：http://dali.sysykeji.top/Article/details/gtjbmhtymr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtrudbhgke.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuxming.cn/Article/details/gtqkarwjwr.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gtycvlszlc.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckwzblmi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.havefunace.top/Article/details/gtrztdrmnj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gtezxhtbcy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtyvokncqr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtlmwvywqf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxqigpol.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtfckwziaq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigfzy.top/Article/details/gtgvtrsroq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtzznisacd.html

[D24] 字典 / Map 基本操作
来源：http://dali.andypj.xyz/Article/details/gtxjfcpyrj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.andypj.xyz/Article/details/gtyawmlcwe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtuatbnyki.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjzijbbd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtiwwfejbz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gtpziyfgoe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.vqdsnc.cn/Article/details/gtqhkhgiic.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gtumvvarjs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gtetdptfba.html

[D25] Set 集合去重与交并差
来源：http://dali.yongpay.top/Article/details/gtsocignqj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hfpthk.cn/Article/details/gtqzuzjpjv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtdejwadra.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnqzz.top/Article/details/gtpkvcoprz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtpowajibl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258.top/Article/details/gthfwkpbkm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jyoumei.cn/Article/details/gtqekgejsg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gtnoisnxxr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtdedxotmd.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtiwylyjsd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gtkhezfska.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthddvtdub.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtwgzdcadp.html

TS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gttwrymdwl.html

Java: String.join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtkkotyxzp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gtfanjzgxp.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtddzvsfps.html

C#:   string.Join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gtskqjwxjg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtlyjznxwf.html

E. 字符串处理
来源：http://dali.yueranfly.top/Article/details/gtaavxvhdt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzdjiywzt.html

[E01] 拼接字符串
来源：http://dali.cashguo.top/Article/details/gtqgcnqbqj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gtfnzlvdfs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ppjwa.cn/Article/details/gtlyppskly.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtyxwsdypa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtnkeacztf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aibaodan.cn/Article/details/gtuhfhhxio.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gtnxdrfgym.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gtvzhgfpxg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtbxkfysoe.html

[E02] 重复字符串
来源：http://dali.zhengqikj.top/Article/details/gtedtwqxyk.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhmodwyu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yanxiufei.cn/Article/details/gththiiedg.html

JS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtwdhyaqby.html

TS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtdvtzvivj.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyykjakw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fzhhl.top/Article/details/gtmkfqxgfd.html

Ruby: "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtqoncyqii.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gtzixtwtxj.html

[E03] 截取子串
来源：http://dali.tanke756.top/Article/details/gtvhktrkpz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchrxepbe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtrwwffxlg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtrbiwaczo.html

TS:   s.slice(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtyibckfmv.html

Java: s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtgbryfkgw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzbzqijz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gtfblbvuec.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gtnpzsnxvj.html

[E04] 查找子串位置
来源：http://dali.sxryk.cn/Article/details/gtpfclqzpo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gthjjqqvbj.html

PHP:  strpos($s, "x");
来源：http://dali.iojbl.cn/Article/details/gtgiaqjoav.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gtxgdrhhab.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtghfsuork.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gthpwwaabv.html

Go:   strings.Index(s, "x")
来源：http://dali.cashguo.top/Article/details/gtxqicliux.html

Ruby: s.index("x")
来源：http://dali.ivvv.top/Article/details/gtpdsizlga.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmohfjhdz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gtfvtkulsf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hywenlv.cn/Article/details/gtlrpsxcwp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gtaumdbzsc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gtoxbyytma.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gtmikxxldz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtnzhmknuy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dianchejie.cn/Article/details/gtrjldqqse.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tianlin.xyz/Article/details/gtzyguxmqw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtlfkkdnug.html

[E06] 替换子串
来源：http://dali.mhx1999.top/Article/details/gtyyihcoow.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtdklqaiyo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gtggvhnibp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtfbhykwlr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtlyxxfrlb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtupurtsip.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtixazehts.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gtaawkdzpw.html

C#:   s.Replace("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtdmyomrmc.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gtbaqxvdyt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ybcxt.top/Article/details/gtmgcggkgh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtlzwaecqr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gtpqxjhdfj.html

TS:   s.split(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtagxdnmnq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258888.top/Article/details/gtnmbfgzxx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gtnnsrfohh.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gtvclcoqjq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yonumen.top/Article/details/gtxzetzmzq.html

[E08] 数组按分隔符合并
来源：http://dali.xylfe.cn/Article/details/gttzbwkiub.html

Py:   ",".join(items)
来源：http://dali.meibo888.top/Article/details/gtfjpaysyx.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gtpluimdho.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtrocrlotw.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtrsnjsufz.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtapabkvdp.html

Go:   strings.Join(items, ",")
来源：http://dali.xuanzx.com/Article/details/gtgxevyigo.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtxyobghoh.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gtbylxrymf.html

[E09] 去除所有空白字符
来源：http://dali.jinqigfzy.top/Article/details/gtqjoffggi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gtesikhqgt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gtsgmvayfu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtzxmxscxj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtkicdbqae.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gtfmhkxonz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gtpfhbhmgh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dianchejie.cn/Article/details/gtezoguzhl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtuochjdba.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gtpmailkiq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtvnemqcol.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gtqocwcvaa.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtfuyrialj.html

TS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtoazqbgnc.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtjegxjpbx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtizylozqt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtobeffklz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gtdkscshpl.html

[E11] 反转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtshrojtxk.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtlyuwqego.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gtubuvnxfa.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtchoxkalp.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtctvzcyvf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomfqooin.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gtvewzdcbh.html

Ruby: s.reverse
来源：http://dali.yueranfly.top/Article/details/gtblvvqvlg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtlgucnnhb.html

[E12] 统计某字符出现次数
来源：http://dali.cucudq.cn/Article/details/gtupaqsyqi.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gtwwctlhoe.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gtlrmntmek.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtghcnzcxt.html

TS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtgeadampu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gtgfbovyim.html

Go:   strings.Count(s, "a")
来源：http://dali.yuanzhike.top/Article/details/gtadsynybz.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtguohyqri.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gttzhjbfcc.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gtzykgigxf.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtlutexkle.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gtizhvpphe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtdncwlhcf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gtuovvycvj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jianghu66.top/Article/details/gtlmezxtrh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtbmthxkbp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gtfdcazvur.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqeamxwye.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gtyytddvzk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daria6918.cn/Article/details/gtgqgmzdkx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtqtsgtquk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gtfyxlrsci.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gtbdiucotp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtnfemcbxk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gtujjqddxg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gthsfubsor.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtcnsxqyug.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtuhuyjaae.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dianchejie.cn/Article/details/gtjpfntltr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cdnleiting.top/Article/details/gtehdrsmjl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gtzunxlzod.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hfpthk.cn/Article/details/gtngralcnn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhongyouzk.top/Article/details/gtjdhqckex.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cqqwz.cn/Article/details/gtjgajacpr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zycfv.cn/Article/details/gtvelovcdm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gtcucyzxce.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gtwgevxnbl.html

Py:   f"{1234567:,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtjjcvnndh.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gtjmrvkcmx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtcaktpjjg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtzirrmvou.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnvfovji.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dashuyun.cn/Article/details/gtjqfgknxx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nwbrower.top/Article/details/gtmzoiiuab.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gteigvxdoe.html

[E17] 首字母大写
来源：http://dali.andypj.xyz/Article/details/gtdjiihtxw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gtoxcpycil.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gtqiiqdynv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gthnhqipdz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtysvnvzxu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gtzsqpnhty.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gtzygpfjzu.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gtahuhfgek.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258.top/Article/details/gtqzmjwgok.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gthjnbzfon.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtxgednysl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gtptddysvc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtpedxisub.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtxucxsuyn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtopsyhcsp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtovucgulw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gtjkmxgrzi.html


<!-- 参考信息 -->