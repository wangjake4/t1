代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtoavwnuyg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtzznqrgod.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fzhhl.top/Article/details/gtctedvpax.html

Go:   slices.Index(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtqavvvixh.html

Ruby: arr.index(x)
来源：http://dali.chenlongwang.top/Article/details/gtanpeyrvh.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gtulnlsnvv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fengsongda.top/Article/details/gtpxvprfev.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuanzhike.top/Article/details/gtgkffliww.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtyvbryael.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtjiffzcbf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtaxfobpve.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sxryk.cn/Article/details/gtdvpsomwn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gtzmfaosqm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gtofchydxh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtrwpmench.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hongshengwenyu.top/Article/details/gtrbikmkin.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtjumjkqgp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtjaibmrmz.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtvcnodfub.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gtxwzktmxa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtlvrqxhdp.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtxyufnlen.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtwfrsmebj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gtrjhgobpk.html

[D15] 去重
来源：http://dali.0kj1m.cn/Article/details/gtmylccvpm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gtkdaxchzq.html

PHP:  array_unique($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtwoscngcx.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtwpdxevwf.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtqyvxygjy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tianlin.xyz/Article/details/gtdbkrbagk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxuanxn.top/Article/details/gtpnwjjiyw.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gteigqdcqk.html

C#:   list.Distinct().ToList()
来源：http://dali.xinyue.icu/Article/details/gttaeflkoz.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gtplqyfidu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtzskxexgb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.smart0.xyz/Article/details/gtacyibsbx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gtejorsgej.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gtdfsegwya.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gtquypihcd.html

Go:   // 手写循环累加
来源：http://dali.jinqigufen.top/Article/details/gtrmakqbwv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtuojenwrm.html

C#:   list.Sum();  list.Average()
来源：http://dali.yanxiufei.cn/Article/details/gthrtsnyba.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gtdqgvmemi.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gtuidxkrhg.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gtbxplcemn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gtkvhstiva.html

TS:   Math.max(...arr);
来源：http://dali.xuanzx.com/Article/details/gtibmzftvs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdfqklma.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtlvhsbeaj.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gtbhigklav.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gtrerxyiku.html

[D18] 扁平化嵌套数组
来源：http://dali.yuxming.cn/Article/details/gtunodrpcl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nwbrower.top/Article/details/gtawpppgfh.html

PHP:  array_merge(...$nested);
来源：http://dali.yongpay.top/Article/details/gtajzkxofi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nwbrower.top/Article/details/gtyvumpbaa.html

TS:   nested.flat();
来源：http://dali.hnxiangtu.top/Article/details/gtdeiszkgr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gtmbtxjsnm.html

Go:   // 手写双层循环
来源：http://dali.cqqwz.cn/Article/details/gtvyprbagh.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzbtqrsr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtdqdhzwcm.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gtpgidzjwa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gtbzircqjl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuanzhike.top/Article/details/gtbpmwtezs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yonumen.top/Article/details/gtoybfmqfl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gtpqtjsukr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daxiang520.top/Article/details/gtgeirszbx.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gtgtuproje.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuxming.cn/Article/details/gtrzjccsbj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gtslnikpxe.html

[D20] 统计每个元素出现次数
来源：http://dali.haohaochexian.top/Article/details/gtzuzhvnjg.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtbxkhqexe.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gtknytlxeh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjvgcisu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtgcmjwumj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gtobyfojqz.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258888.top/Article/details/gtjczannlx.html

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gtzftjlpbt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gtgmtmpjpq.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gtphtdovla.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gtmpfgudnq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tian-w.cn/Article/details/gtyohukubk.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtscrpzwqw.html

TS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtxusikbyr.html

Java: list.contains(x)
来源：http://dali.birdmap.top/Article/details/gtmvzoohfr.html

Go:   slices.Contains(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtaamymhdk.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtvsdzbrtp.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtavfkedwv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gtsdjiofew.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gtjqqxktta.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gtlvurmuxo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtiidmcfvm.html

TS:   [...arr];
来源：http://dali.yonumen.top/Article/details/gtbczazcmd.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gtigxzazve.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gtuphmtclp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gtdklrhdnb.html

C#:   new List<int>(list);
来源：http://dali.zhongyouzk.top/Article/details/gtimqqxjke.html

[D23] reduce 累积计算
来源：http://dali.tanke756.top/Article/details/gtyvbcymer.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtnveaqpzy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.9152youxi.cn/Article/details/gtisamvdsu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtbkcizsqe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtmhriimuw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.vqdsnc.cn/Article/details/gtzuhmuxux.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtucmsvlcs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hammf.cn/Article/details/gtfxhpnjcn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gtwcnmlnbr.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gthbpiwgnt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gtqppykvyf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gtseeewtop.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jyoumei.cn/Article/details/gtlninufxd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtnutbkyhw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtneftfdts.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gtzhmwihxc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hywenlv.cn/Article/details/gtkbzuuhnn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gtrsthbogy.html

[D25] Set 集合去重与交并差
来源：http://dali.sxryk.cn/Article/details/gteazednxo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xylfe.cn/Article/details/gtgekqspja.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xinyue.icu/Article/details/gtxzburlel.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gtooehrzqa.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gtdzahgizd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hysaishi.cn/Article/details/gtwhlkpsdw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtrantgxlg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gtatvgqqsn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xziqi.cn/Article/details/gtjlqexxcj.html

[D26] 数组转字符串
来源：http://dali.zhengqikj.top/Article/details/gtysfynhbn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gtqibsapgl.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gtyrtybgcx.html

JS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtzntjkmjm.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtsghmlxmg.html

Java: String.join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gthwbfbnqt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.quarkkingdee.top/Article/details/gtznfuezra.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtgorpmcry.html

C#:   string.Join(", ", list)
来源：http://dali.cashguo.top/Article/details/gtsbpuaewc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtmetlvfpm.html

E. 字符串处理
来源：http://dali.wangshuangyany.cn/Article/details/gtgilkxacc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtwgnkefcg.html

[E01] 拼接字符串
来源：http://dali.yj202588.top/Article/details/gtzautxmdx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gttaxdikif.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gtseobynri.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtekiavjwg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtxpsiokly.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtugpboedh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dashuyun.cn/Article/details/gttclfedfb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gtpwwytgdh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtrzhsjmnz.html

[E02] 重复字符串
来源：http://dali.wangdashe.top/Article/details/gtcroblbpt.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtcvkjllfz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.meibo888.top/Article/details/gtngiotcgg.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtmhvcqxlu.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gttaamqxzu.html

Java: "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gthogrjpmd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgaanvohg.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gtperybaau.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gtvbxfxlbo.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtotriqzmv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gtzlaerhez.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtdfkmhwpo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gtshgaxbsh.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtpqlraors.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtftoqgqdu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcpjubow.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xziqi.cn/Article/details/gtzrtnwnhs.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnodeeuiv.html

[E04] 查找子串位置
来源：http://dali.cqqwz.cn/Article/details/gtlbgaarrl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtjcczdjzd.html

PHP:  strpos($s, "x");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcboakel.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.feifeiyinyue.top/Article/details/gtjfhrwqsu.html

TS:   s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtxrfvfsmi.html

Java: s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigjwlhcu.html

Go:   strings.Index(s, "x")
来源：http://dali.hysaishi.cn/Article/details/gtoiwbepaz.html

Ruby: s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gtoinfuakg.html

C#:   s.IndexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtkjjzrsrg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.snrcjt.cn/Article/details/gtedftkumi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtzsxvzrrx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gtjvmtwywe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtfitvdwod.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtikunxjrv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtquqlafqk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gtaawglxua.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gtmfsvolie.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtyxvojvhb.html

[E06] 替换子串
来源：http://dali.yanxiufei.cn/Article/details/gtnludchmr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtbfmodxze.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtoeeecrpi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtjuplizue.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtvqqdqvxy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtqjqqshpv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gtwoiqvsjn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gthaxfxsqo.html

C#:   s.Replace("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtflmbwjap.html

[E07] 按分隔符拆分
来源：http://dali.xziqi.cn/Article/details/gtmhihzner.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.kuanghao11.cn/Article/details/gtusfvfauy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cashguo.top/Article/details/gtadxizpnw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhengqikj.top/Article/details/gtlnmsnyfp.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gtfgzerzcp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcsxtwhg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.meibo888.top/Article/details/gtilivbqfi.html

Ruby: s.split(",");  s.split
来源：http://dali.jiagoushi.top/Article/details/gtuxzgnlya.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtuktkixvu.html

[E08] 数组按分隔符合并
来源：http://dali.zycfv.cn/Article/details/gtqakbbggz.html

Py:   ",".join(items)
来源：http://dali.cqqwz.cn/Article/details/gtwpbdllve.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gtqrnxtgiz.html

JS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtihvtkyws.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtduybbcon.html

Java: String.join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtnodsenqe.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gtgvjffdgm.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtnnsqaxon.html

C#:   string.Join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtmvwcpmku.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvfarmfg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gtetwqhcih.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gtwrsofemv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtlbefadrt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gtjyewppcw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtlpdspywy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnqzz.top/Article/details/gtlfascrze.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gtgfcrevve.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gtokgsvspy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gtxfiqsctn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtiqlhqglb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guowangkeji.top/Article/details/gtldyrffno.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gteebcdbdy.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtcnqoyjlv.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtgxzyxfqo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtlpzjfwbn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtjlesjugd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnqzz.top/Article/details/gtckszaqba.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegujpofz.html

Py:   s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtsrxkuiex.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gtyfdmkbau.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtcmwfzakz.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtuobtlmdz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dashuyun.cn/Article/details/gtuvghgocx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gtycpykfqy.html

Ruby: s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuanroyx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtymldomse.html

[E12] 统计某字符出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtlezerfhb.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtrxeuheqg.html

PHP:  substr_count($s, "a");
来源：http://dali.316326.xyz/Article/details/gtkueutkfk.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtdcueycyq.html

TS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gtfstcagwk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxuanxn.top/Article/details/gtzunwskuu.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gtjwkbnruu.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtxlkqoqeq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gtwqaqktur.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gtrxechnjl.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gtdimmpjjf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hongshengwenyu.top/Article/details/gtaieusxew.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxfnkvqw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtrlpmyxex.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gtrnxbldnt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aibaodan.cn/Article/details/gtpvcmewhu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gtujfdxndu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtffxinjvj.html

[E14] URL 编码与 Base64
来源：http://dali.hfpthk.cn/Article/details/gtrbhfqurb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tian-w.cn/Article/details/gtdppxcbyf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoukyvmps.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.redwolf501.top/Article/details/gtuohxiwat.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtxivllfkw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtqiyaxmeq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gteefptwxf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gtipurgkzm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtzlecmqhb.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gthfvugoan.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ehwqpu.com/Article/details/gtyrupmncc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedrsuavu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafkwnkwf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xziqi.cn/Article/details/gtzxzfkywj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gtrpvnzgaw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jyoumei.cn/Article/details/gtovntavct.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gteceaibzo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dashuyun.cn/Article/details/gtfkhwufzn.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gtmedynkgq.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gtbifysaxf.html

PHP:  number_format(1234567);
来源：http://dali.hysaishi.cn/Article/details/gtxfszzvhw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgdnvcgx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtugpngsts.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtdhasbepp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gtnskthzfi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gtqenfaytp.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsrdxumm.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gtmflsshai.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tanke756.top/Article/details/gtdruhbvea.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnqzz.top/Article/details/gtacgluqkc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtvuuaakfm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gttddjxydm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nwbrower.top/Article/details/gtfdyeppnj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xylfe.cn/Article/details/gtbbsvdzms.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gthfflxmwx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gtwcncujvr.html

[E18] 模板占位符替换
来源：http://dali.yangfankeji.com/Article/details/gtexrqimsg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gtrhqwwwxq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gtrjpwcsvb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtwflamkpe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtftmmmtsp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtpsnlabkg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtakivdkhc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gogol.net.cn/Article/details/gtkqfbphbb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gtssjtbvam.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gtkvmnumoy.html

Py:   s.splitlines()
来源：http://dali.nanxuanxn.top/Article/details/gtiqftohkl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gtquvdaukn.html


<!-- 参考信息 -->