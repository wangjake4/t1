代发 wailian999

C#:   list.Reverse();
来源：http://dali.dianchejie.cn/Article/details/gtfjukvbqt.html

[D12] 查找元素下标
来源：http://dali.xuanzx.com/Article/details/gtuecildpw.html

Py:   arr.index(x);  x in arr
来源：http://dali.jiagoushi.top/Article/details/gtmttwyujh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtbzmngjaw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtyhqygbel.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtpaezdfoi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gtzmmvdfao.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gtnjnpyjji.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtxoamljjj.html

C#:   list.IndexOf(x);
来源：http://dali.feifeiyinyue.top/Article/details/gtirkkybzi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuanzx.com/Article/details/gttztxrwpi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gtskimugzm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cqqwz.cn/Article/details/gttdjhlpkd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtztbzgkyt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtnqmiwpoo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtcwnkfkfq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gtrplsocix.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gtomfyszjl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtoxysycjy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xinyue.icu/Article/details/gtsnyzdzxb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gtablmqugj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yonumen.top/Article/details/gtyldckjlj.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gttqyglgfx.html

TS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzfwjslv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtlhugqkaw.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gtgttchzrh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.meibo888.top/Article/details/gtgiigcmid.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjirgqxay.html

[D15] 去重
来源：http://dali.jinqigfzy.top/Article/details/gtzsiaqopx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gthchcjulj.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gtaeuhfbqc.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtkuinzras.html

TS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtkwezkqel.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gtcoeecvjw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tianlin.xyz/Article/details/gtiseyfjif.html

Ruby: arr.uniq
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzupovsi.html

C#:   list.Distinct().ToList()
来源：http://dali.haohaochexian.top/Article/details/gtewdemjfu.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnbdyxts.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gtcziqvndz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gthmvtdmip.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtjecodtmg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gtiefoqdhm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangshuangyany.cn/Article/details/gtpuehbomo.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gtmajcanbp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqzlidji.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gtrgzpsgis.html

[D17] 最大值与最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtyozeseib.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtutlcwolt.html

PHP:  max($arr);  min($arr);
来源：http://dali.sxryk.cn/Article/details/gtwtwxwjnb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gtbhnydgaz.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gtlzzbpgcn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj202588.top/Article/details/gtmfzddymq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ydzc1.top/Article/details/gtmhipjphl.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigfzy.top/Article/details/gtniistzbn.html

C#:   list.Max();  list.Min()
来源：http://dali.hywenlv.cn/Article/details/gtuwpjqvbc.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gtnunmjsom.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.mhx1999.top/Article/details/gtogczkmki.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gttbfrmynw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.feifeiyinyue.top/Article/details/gtnwqnjchk.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gtbktvhmoe.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gturnhfipg.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gttqgjxqpp.html

Ruby: nested.flatten
来源：http://dali.tanke756.top/Article/details/gtybtjumns.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cheryme.top/Article/details/gtrkyvgohe.html

[D19] 按字段分组
来源：http://dali.jlsjyb.cn/Article/details/gtnqzpoyzp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnxiangtu.top/Article/details/gtdjaeqtyy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenzaomai.com/Article/details/gtuikfajij.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cashguo.top/Article/details/gtonzceqcm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtsejvpedy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gtkprarier.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gtnouxjilk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gtilujvhkd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hammf.cn/Article/details/gtqiyzzjlf.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcytjidv.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gtseyhwyig.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtvqazxnvr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gteqguohkk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtmddrdarn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gtwfzpoqsp.html

Go:   // 手写 map[T]int
来源：http://dali.sxryk.cn/Article/details/gtgtgitdxv.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gtlvqgxzdx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gtdkmphixe.html

[D21] 判断是否包含某元素
来源：http://dali.cqqwz.cn/Article/details/gtoawsktyl.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gtnsvhiozb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hfpthk.cn/Article/details/gtbfwqewdn.html

JS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtbomakmct.html

TS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtvsuitgqe.html

Java: list.contains(x)
来源：http://dali.yuxming.cn/Article/details/gtjkgveqko.html

Go:   slices.Contains(arr, x)
来源：http://dali.cheryme.top/Article/details/gtmcxrdpso.html

Ruby: arr.include?(x)
来源：http://dali.hfpthk.cn/Article/details/gthglumecs.html

C#:   list.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gtfipuruqn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gtxzdrismo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtmdaygfea.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gttzvwolqe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyqvhxmt.html

TS:   [...arr];
来源：http://dali.andypj.xyz/Article/details/gtweyhvzst.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gturfhgsij.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgfzy.top/Article/details/gthyztbecj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gtqwwkpoug.html

C#:   new List<int>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtifgzdtdm.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gtdmcmjmce.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtpsqcefoy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shuidangran.top/Article/details/gteeavmkmi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtzuprtxev.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmijpiwj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gtcpfjzfvf.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtivwfuoxt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gtkcqrcdgn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jiagoushi.top/Article/details/gtebifhpgx.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gterynclib.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gtpislejee.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gthluntaxt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.c1oappe.top/Article/details/gtchxpnmlo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtkcchvdyu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gtqovelunt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gtpjjqahaf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnqzz.top/Article/details/gtnsxwqbpm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tanke756.top/Article/details/gtgrjenazt.html

[D25] Set 集合去重与交并差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhinsdbx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfmimvxm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gogol.net.cn/Article/details/gtanbdumit.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gtlxyjemxq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gtelnftgeg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gtcxulpvuv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuanzx.com/Article/details/gtihyrvdqv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnztsybqr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.0kj1m.cn/Article/details/gtxpijuiku.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gtdmetxkbx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sweek.top/Article/details/gtfrkcqfvk.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtszjnanir.html

JS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtfqtjgghv.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtviuhgojr.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtmmtfbpch.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tianlin.xyz/Article/details/gttzwvwugy.html

Ruby: arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtsigaqexe.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrhqpmpr.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtazpczhzi.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gtecihktia.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtltpkjcla.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtdivljbhj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gtstimhujv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gtbqdugyqu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtoyjldzeq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gtgqcaedcc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.havefunace.top/Article/details/gtilzxnbiq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtnswoicyb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhixingplan.top/Article/details/gtiouxjmdo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tanke756.top/Article/details/gtjtirsiqv.html

[E02] 重复字符串
来源：http://dali.nanxinkj.top/Article/details/gttuwgkibz.html

Py:   "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gtmaxkelfi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hywenlv.cn/Article/details/gtblekjzum.html

JS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtaqxcvifj.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtewoiffxc.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtenndntem.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gtpastcozw.html

Ruby: "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtjvtctexz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hywenlv.cn/Article/details/gtajppzvmv.html

[E03] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtwuqjbcwf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.316326.xyz/Article/details/gtnxtflyex.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtnbxjvcln.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtvvjvysii.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtxrnqtklx.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtpqygbloi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtnzxlauvu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guannengcc.top/Article/details/gtrkcbyieu.html

C#:   s.Substring(1, 3)
来源：http://dali.svipenyu.cn/Article/details/gtdrjsbcdx.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gtkzintghn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gtzfzuzztr.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gtsoogfaca.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangshuangyany.cn/Article/details/gtxhababgv.html

TS:   s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtsgosrlhw.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtexjnnqrk.html

Go:   strings.Index(s, "x")
来源：http://dali.yuxming.cn/Article/details/gtdqlkwabm.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtopedqxae.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtycczjsle.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pycfn.com/Article/details/gtnsikwerv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhengqikj.top/Article/details/gtnqzobbxw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gtqpbpugiq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtxbntcwiy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhoulong.xyz/Article/details/gtkqcexzgw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtejmjhyvg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hfpthk.cn/Article/details/gtykzikvhe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gtqvnhkyzj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gthigskhav.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gtzlugyaha.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtueariynp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgufenzy.top/Article/details/gtrajkwrmi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtgjpdstkp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtnkcbteml.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtjhqyfwcu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtfdhbvnbk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtutluksfx.html

C#:   s.Replace("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtzcvjafnv.html

[E07] 按分隔符拆分
来源：http://dali.c1oappe.top/Article/details/gtfifeqkww.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gthvouumwq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtfoagbmtu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pycfn.com/Article/details/gtducfpncg.html

TS:   s.split(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnbsuxjq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gtklivjrkf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gtsmrgboob.html

Ruby: s.split(",");  s.split
来源：http://dali.yonumen.top/Article/details/gtkvwngglu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dashuyun.cn/Article/details/gtoemzbrpx.html

[E08] 数组按分隔符合并
来源：http://dali.zhixingplan.top/Article/details/gtubjaegfo.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gteokyokhe.html

PHP:  implode(",", $items);
来源：http://dali.jiagoushi.top/Article/details/gtakvllqfp.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtjzkeyotq.html

TS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtanptowbs.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtrlzkeshj.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gtkrgxtluz.html

Ruby: items.join(",")
来源：http://dali.sweek.top/Article/details/gtnqvlbhoo.html

C#:   string.Join(",", items)
来源：http://dali.nwbrower.top/Article/details/gtxdspwevr.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gthgnykimz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtuqmgzepd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gtenhhpewr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtarusfqcr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gttuvuszxq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtuttfyphh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hysaishi.cn/Article/details/gtvsbmxjyi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.0kj1m.cn/Article/details/gttrnbboqx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtlmovrbjb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xziqi.cn/Article/details/gtfxubpnnq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gtzfatvqlu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gtojdatsax.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtpxehrzyz.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtexfvfess.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtmqsjlerx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtzybujplj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtjkjeqcbk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwojndao.html

[E11] 反转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtojiqyppn.html

Py:   s[::-1]
来源：http://dali.yj20258.top/Article/details/gtzgowleof.html

PHP:  strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtguycgyqi.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcssegplz.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtzujmpdmi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cdnleiting.top/Article/details/gtmphqdrja.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtjpymhxhz.html

Ruby: s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfwxrbba.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtknrsqhhs.html

[E12] 统计某字符出现次数
来源：http://dali.yuxming.cn/Article/details/gtnxdgwvfn.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtqakwqfzb.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtrzbnvoev.html

JS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gtconiwdjy.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtqkltoeve.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gtgdmevkih.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gtniotptgk.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtzjsgixlg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gtbambakfw.html

[E13] 逐字符遍历
来源：http://dali.hnqzz.top/Article/details/gtzlqozozm.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gtouorcxds.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tanke756.top/Article/details/gtnpyddtlb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtpmopzkax.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtmxfxegpt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gtlbjqgssz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gtkycdczcc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gtikzkjkua.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gtllodmahi.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gtrvnjxxam.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gtpqlwzybg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaneiozj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwlovqqy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gtgboziibr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tanke756.top/Article/details/gtwppslnix.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gtuviwhhqt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gtnmdjiowu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gthliswsva.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gtpdfrajsv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gtdcaycvao.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fengsongda.top/Article/details/gtbrzlspqr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ybcxt.top/Article/details/gtefbmwwbg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuxming.cn/Article/details/gtyskeinqx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xziqi.cn/Article/details/gtxjsiough.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrxydddz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gttidiutrw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sxryk.cn/Article/details/gteozlpqss.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtrtlwyoec.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkyxkdura.html

PHP:  number_format(1234567);
来源：http://dali.yonumen.top/Article/details/gtarmuruai.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtcbfxzarv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gtemaockgg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gtzlzppptq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.bjfxy.top/Article/details/gtfwejnmtc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeynknxc.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrslekftv.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gtdrjomyck.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gtdrdbtlmm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj202588.top/Article/details/gtxritiwkr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtxoemdijz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtczwtjatv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gtmbvxjeyc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.mhx1999.top/Article/details/gtlvzrifzy.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gteaskgjio.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gtitoyxghw.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gtcxiwxrsq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gttwelttem.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gtuymvwsik.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtqawmsugb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtseugqdca.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtimdohlxk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtycissplk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gogol.net.cn/Article/details/gtrydozeea.html


<!-- 参考信息 -->