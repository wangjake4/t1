代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jlsjyb.cn/Article/details/gtwvvarlfi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtntckdsez.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtlabhsoes.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.meibo888.top/Article/details/gtjpsqziur.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gtgusjwffl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hammf.cn/Article/details/gtzybmcjvc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gtpndvofsi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.quarkkingdee.top/Article/details/gtrygxnfjx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtbdawamai.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtqsptswdf.html

JS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtbwtxedwk.html

TS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gthahvrilk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gtrztlzjrx.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtazwntcrb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtvmcppndc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtbsoelpsg.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gtdmjoxnim.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gtnqeaxrfh.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtvmzggjgk.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglwwjedm.html

TS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gtygzchjnx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.kuanghao11.cn/Article/details/gtwyfakqlg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.birdmap.top/Article/details/gtctcuqwnd.html

Ruby: arr.uniq
来源：http://dali.gotoacloud.top/Article/details/gtxvtqeffh.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gtwxbnlmzh.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtilqvetav.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gtafcpoano.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuanzhike.top/Article/details/gttvwcdneo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gthqyhtmzm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtohpgxale.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yongpay.top/Article/details/gtenrozxwr.html

Go:   // 手写循环累加
来源：http://dali.xziqi.cn/Article/details/gtwxvkeezs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcgysyjl.html

C#:   list.Sum();  list.Average()
来源：http://dali.haohaochexian.top/Article/details/gttsdbsjnl.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtqatxhjnp.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gtwuqrjmbt.html

PHP:  max($arr);  min($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtwkvwwkhu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgfzy.top/Article/details/gtuleacnle.html

TS:   Math.max(...arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gthmmluobf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daxiang520.top/Article/details/gtuzhpnyij.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmknokzka.html

Ruby: arr.max;  arr.min
来源：http://dali.hnqzz.top/Article/details/gtvmnlmbcp.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gtiglxqfkv.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gtloikrxxp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yongpay.top/Article/details/gtmjbevuuk.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gttmxnldum.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gtpgurbpem.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmodjbwqf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gtvsqmtegs.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gtcfdgbewg.html

Ruby: nested.flatten
来源：http://dali.jqgfzy.top/Article/details/gtwcjongri.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xziqi.cn/Article/details/gtxbqrtiso.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gtldarvxvq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtcepvwtai.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gtdzdxkuxx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sysykeji.top/Article/details/gtlnoluqxr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gtkfohygyv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cucudq.cn/Article/details/gtltdrphku.html

Go:   // 手写 map[string][]T
来源：http://dali.xylfe.cn/Article/details/gtdfacieru.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yonumen.top/Article/details/gtdrewsodc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fengsongda.top/Article/details/gtzjlyupil.html

[D20] 统计每个元素出现次数
来源：http://dali.sufxvd.cn/Article/details/gthvwnipay.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtqtrtvfjp.html

PHP:  array_count_values($arr);
来源：http://dali.sufxvd.cn/Article/details/gtqdppicjk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtgcxuxjwi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtlzdsmhnc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gtdvpogvie.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gtzxtfsxuf.html

Ruby: arr.tally
来源：http://dali.jinqigufen.top/Article/details/gtpzieulvf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.316326.xyz/Article/details/gtixnbrctg.html

[D21] 判断是否包含某元素
来源：http://dali.9152youxi.cn/Article/details/gthjrrieat.html

Py:   x in arr
来源：http://dali.zycfv.cn/Article/details/gtezcodvub.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gtycujzvap.html

JS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtdemuytax.html

TS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtlfemymvk.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtbssskhdp.html

Go:   slices.Contains(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtqrpgabrz.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gtnoeegfqu.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtbsunihnd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gtdchbsmqi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisyelcgi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxinkj.top/Article/details/gtvmlxkadl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtywpwbwhp.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gtnsbuxvpu.html

Java: new ArrayList<>(list);
来源：http://dali.dianchejie.cn/Article/details/gtohzwgyjf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gtirbzrvop.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gtomctrlrs.html

C#:   new List<int>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gthrxulckb.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtrhzyxcjm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dianchejie.cn/Article/details/gtfvgxjtnn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gtmvxsrubc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtizzyrmkx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtssbhuogp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhongyouzk.top/Article/details/gtgfktgoet.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtgjlovves.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gtcdjdstaf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gtwxvgybac.html

[D24] 字典 / Map 基本操作
来源：http://dali.havefunace.top/Article/details/gtlqhgvuem.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aizwys.cn/Article/details/gtzlmmvxma.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gogol.net.cn/Article/details/gtmbdytsqw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cashguo.top/Article/details/gtqfcrvehr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwuwujzf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dianchejie.cn/Article/details/gtuzbalchi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gtqvlduxli.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tian-w.cn/Article/details/gtwwwtytlo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgfzy.top/Article/details/gtyrprxfez.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gtxcwqluvf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yongpay.top/Article/details/gtfmcboilt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ybcxt.top/Article/details/gtjlfvvnhd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnxiangtu.top/Article/details/gthjweavie.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gotoacloud.top/Article/details/gthjudcqnl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.smart0.xyz/Article/details/gtrgsrltzv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dianchejie.cn/Article/details/gthgnpjfip.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gtfdhfvzag.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtyoehcvew.html

[D26] 数组转字符串
来源：http://dali.hysaishi.cn/Article/details/gtfgljopiy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnqzz.top/Article/details/gtexvplwgg.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtfxobbnky.html

JS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtvnlwytxx.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtizyqcorl.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtfmrbzdxk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtesktffwi.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtfvvlhmqc.html

C#:   string.Join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gtjkfiqntu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtnjwfdhcs.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtygdbahhm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtflpcwphx.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxozrccjc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gtuonmecim.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gtcmbyjogv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtrbtgnvdr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtdbwunowl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gttywkcflo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gtdcjgegmg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gtcljuodzr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtwfdtszwo.html

[E02] 重复字符串
来源：http://dali.smart0.xyz/Article/details/gtkzcayyoh.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtjjuvxfez.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gtfgftgpqz.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtbdjastok.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gthyavykxy.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtyviwhymj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yonumen.top/Article/details/gtdteioqoc.html

Ruby: "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gtgsjvmmnt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj202588.top/Article/details/gtrafapxea.html

[E03] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtsoizijkn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zdqjudy.top/Article/details/gtkmuzcanp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtadfrvkgn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtgfsxgilt.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gthrcxutxb.html

Java: s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtpprrvsic.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtbdjpsotr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuxming.cn/Article/details/gtqpbqwxtm.html

C#:   s.Substring(1, 3)
来源：http://dali.tianlin.xyz/Article/details/gtffscydov.html

[E04] 查找子串位置
来源：http://dali.jlsjyb.cn/Article/details/gtzvguzckd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtwxboemei.html

PHP:  strpos($s, "x");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyhspaxh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.smart0.xyz/Article/details/gtwfwitzcp.html

TS:   s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gthatvuztf.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtllzftfuj.html

Go:   strings.Index(s, "x")
来源：http://dali.vqdsnc.cn/Article/details/gtjezfires.html

Ruby: s.index("x")
来源：http://dali.shuidangran.top/Article/details/gtvihdplnz.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtwuynirte.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangshuangyany.cn/Article/details/gtvfnfkszh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gzhubu.top/Article/details/gtuvpxvfod.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhoulong.xyz/Article/details/gtwilkyusk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtwdibultw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gotoacloud.top/Article/details/gtgdjfbzrt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtmorsvlqy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gthctuxlue.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gtwsjggogl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtbxstmbfa.html

[E06] 替换子串
来源：http://dali.jiagoushi.top/Article/details/gtcdwyorao.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtrlynptxc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cqqwz.cn/Article/details/gtjiymgnrr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtelcxyrzq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gteqihujgs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtlycwvluw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gtkxmwwtzy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtqjnppomw.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtxazdpqml.html

[E07] 按分隔符拆分
来源：http://dali.kuanghao11.cn/Article/details/gtpbiwqzux.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cdnleiting.top/Article/details/gteoodwpki.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtoviphxgp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jlsjyb.cn/Article/details/gtntytpicm.html

TS:   s.split(",")
来源：http://dali.bjfxy.top/Article/details/gttcegnrnw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuetiantiany.cn/Article/details/gtvlrjpjqb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cqqwz.cn/Article/details/gtxzqwvpmc.html

Ruby: s.split(",");  s.split
来源：http://dali.zhixingplan.top/Article/details/gtqxzrtjjp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hfpthk.cn/Article/details/gtawiyubek.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtmsuubsbc.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gtkdqudwja.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gtgqtirdsm.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtknrndiby.html

TS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtknfxvvhr.html

Java: String.join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtxmbukmmb.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gtzclnrdvx.html

Ruby: items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtexczafxq.html

C#:   string.Join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtlvytuiwq.html

[E09] 去除所有空白字符
来源：http://dali.smart0.xyz/Article/details/gtcabhyoms.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.bjfxy.top/Article/details/gtsfghfawk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hywenlv.cn/Article/details/gtohpvvdbi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtltkeuukr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gtyangudat.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gtsvhzirqo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.haohaochexian.top/Article/details/gttsaaflua.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shuidangran.top/Article/details/gtafsuvmjx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cashguo.top/Article/details/gtmshmwhpc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.bjfxy.top/Article/details/gtdssdvlko.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtwsbskfbf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuanzx.com/Article/details/gtfihyzihd.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtfraxqmyb.html

TS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtroyphzlh.html

Java: String.format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtbkceyzzt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtzsrgyqyu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtuwdvkqgi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gtbrvvzncn.html

[E11] 反转字符串
来源：http://dali.hfpthk.cn/Article/details/gtuolbuiot.html

Py:   s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtvxfitqxg.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtbweiiepf.html

JS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtiqlbqhhh.html

TS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtorhgiiye.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xinyue.icu/Article/details/gtokgacxtd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.mhx1999.top/Article/details/gtwswsclvb.html

Ruby: s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtznonukej.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gtigopdvof.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gtssnexbja.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsidjyfj.html

PHP:  substr_count($s, "a");
来源：http://dali.chenlongwang.top/Article/details/gtxkgaxplq.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsodsvyvr.html

TS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsjjqzrd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gtdbjgegky.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gtuydormph.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtnnycydtb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gtyqsngixn.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gtoqblpgcs.html

Py:   for ch in s: print(ch)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmarhhqzn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gtvhmftmyi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtaeqtjvie.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtjgvtwvfj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtxggcizix.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtgulqnake.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gtjwfjrbuu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtvbvcsibi.html

[E14] URL 编码与 Base64
来源：http://dali.havefunace.top/Article/details/gteyepdfon.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dashuyun.cn/Article/details/gtenvffrmn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gthswoesrq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gtgocqymoq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gtyznflvhp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gtzpshaevr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gtqaphsyqx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgfzy.top/Article/details/gtwvpikrfk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtkuoxsmyj.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangshuangyany.cn/Article/details/gtxmhqjqyf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.quarkkingdee.top/Article/details/gtccenlhyd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gtidnvaxws.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gtszawlgnl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gtvretcjvq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gtfgszhbwb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtlygipnku.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.redwolf501.top/Article/details/gtbgsytryg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gtukjgaoqo.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gtkvpulvqe.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gtahmkdbil.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gtcifrakzh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtnopalibk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtnyafugrd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gtyboxtfex.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gtytzzkywj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.bjfxy.top/Article/details/gtugutpzwk.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gtfifyuewi.html

[E17] 首字母大写
来源：http://dali.sweek.top/Article/details/gtbyomvcrz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gtvuzblppl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gtaoksnota.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtbsbtajbd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtvneuliyo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtfkrojeyw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyqyrkmt.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtisyyvbay.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhixingplan.top/Article/details/gtsjfqmdoi.html

[E18] 模板占位符替换
来源：http://dali.ehwqpu.com/Article/details/gttrpttypd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gtjqnezfiz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gtcyrfkduc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtepznchnu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtptmiomnm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtmrkiicyn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtvvztwgsl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.birdmap.top/Article/details/gtvdslqvup.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtoiovlwoc.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gtjatxmzyr.html

Py:   s.splitlines()
来源：http://dali.jiagoushi.top/Article/details/gtkpqsbkpj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xinyue.icu/Article/details/gtvsgurmti.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtezjkgxav.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gthxncllmb.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gtvmxdsdhr.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlzzuzol.html

Ruby: s.lines
来源：http://dali.hnqzz.top/Article/details/gtxyshzixs.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gtkxvnfwgc.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gtzlthsbuc.html

Py:   if not s:
来源：http://dali.aizwys.cn/Article/details/gtozvqynni.html


<!-- 参考信息 -->