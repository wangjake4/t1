代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gtmlspakxj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtxecsoinn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gteiaakewo.html

Go:   slices.Index(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtppwdgxxk.html

Ruby: arr.index(x)
来源：http://dali.jyoumei.cn/Article/details/gtdyvpccma.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gtyojvoqec.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sysykeji.top/Article/details/gtlrtpkmaz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gtwphvkjpb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xylfe.cn/Article/details/gtoukcnvvg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtflsgzggd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gtwkpiypoo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hysaishi.cn/Article/details/gtmexrmept.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ivvv.top/Article/details/gtxzamtuvg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gtkjdfjzkv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gtbfdybkau.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zdqjudy.top/Article/details/gtugrghlht.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gtrrvpfbvf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtngmjlgbh.html

JS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtoxnninml.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtoraidjhf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yongpay.top/Article/details/gtifueptxn.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtmadnazre.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtwqgdwfqb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtqlzjxgjm.html

[D15] 去重
来源：http://dali.zhixingplan.top/Article/details/gtwfnbqmll.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gtslybcxpk.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypmknbdr.html

JS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtcvvzzfrb.html

TS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtonybiocv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigufen.top/Article/details/gtzmzdeiud.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yvedp.cn/Article/details/gtlhjibedo.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gtsgwuthgz.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gtoxfelzwo.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gthbcqnmex.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtukbinvnk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjiwzffqj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gtgdiihrzs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtqlrakrjc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuanzx.com/Article/details/gtcyvmgymz.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gtpzczqwch.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gtrwtapdes.html

C#:   list.Sum();  list.Average()
来源：http://dali.guannengcc.top/Article/details/gtgwsqiqqz.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gtsdhtagnf.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhrlaoan.html

PHP:  max($arr);  min($arr);
来源：http://dali.sxryk.cn/Article/details/gtdtutkkfs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gtrhldomdi.html

TS:   Math.max(...arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtiazrltiy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtnuovgsqr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtwfylzqsb.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gteqrpldlz.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgfzy.top/Article/details/gtjusbbnrq.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxinkj.top/Article/details/gtwiksimhj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gtqqdnrhrm.html

PHP:  array_merge(...$nested);
来源：http://dali.chenlongwang.top/Article/details/gtfqxusnoc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gtlcyyjlmj.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gtrxkvwvcx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.havefunace.top/Article/details/gtznatopmq.html

Go:   // 手写双层循环
来源：http://dali.shzxlz.cn/Article/details/gtskbmrsvq.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gtdhbqlbqd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtsuehmbfe.html

[D19] 按字段分组
来源：http://dali.haohaochexian.top/Article/details/gtprzywvng.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gtdbyzowxf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sufxvd.cn/Article/details/gtasltfliw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gtjxajvkqn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtreyurugi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtuczqmbpz.html

Go:   // 手写 map[string][]T
来源：http://dali.yangfankeji.com/Article/details/gtclaxhaxe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gtwxiavhcq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuanzx.com/Article/details/gtipoxdmej.html

[D20] 统计每个元素出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtyjwtyerm.html

Py:   Counter(arr)
来源：http://dali.9152youxi.cn/Article/details/gthxkimyog.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gtxqfirdgv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtnqixyhhv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gtzgnaxtfx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jiagoushi.top/Article/details/gtvumzdtrj.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gtssxvmbnq.html

Ruby: arr.tally
来源：http://dali.aizwys.cn/Article/details/gtqqegaptt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gtkgdxqhtn.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gtnplbanke.html

Py:   x in arr
来源：http://dali.xziqi.cn/Article/details/gtynuirctp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.vqdsnc.cn/Article/details/gtfvdztook.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtkmfrabov.html

TS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtpeculptn.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gttmglapex.html

Go:   slices.Contains(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtgtyolqvh.html

Ruby: arr.include?(x)
来源：http://dali.yueranfly.top/Article/details/gtzemlurki.html

C#:   list.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtpegypalk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gthhpcigoj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gtmmfgtsci.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ydzc1.top/Article/details/gtrnijaogj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtpkckuytd.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gtqsuynzan.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtfxhbkyjl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xinyue.icu/Article/details/gtqmwuuhgl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.kuanghao11.cn/Article/details/gtehmqiuya.html

C#:   new List<int>(list);
来源：http://dali.aizwys.cn/Article/details/gtxiirksqm.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpesfnhg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvowfmep.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gtonqxndsx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtxluqktzb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gtqysfxcqh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fzhhl.top/Article/details/gtujrwmzjy.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtwumyjxrg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gtbdnzrdax.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.quarkkingdee.top/Article/details/gtfoqrkked.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gtaaitcewf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlufprrtg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gtgixdmfnu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jiagoushi.top/Article/details/gtvsbrefic.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtslmoplhk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gtncnzqdom.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sxryk.cn/Article/details/gtufttgpal.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimwvukrg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuxming.cn/Article/details/gtrwgbzqyk.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqcqsnwa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenzaomai.com/Article/details/gtyvihwrak.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtuvzwldgc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gtwuagovsj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gtamhrfysn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gtrcwvckuh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jianghu66.top/Article/details/gtepnhjaxq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.smart0.xyz/Article/details/gtocccahyn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtzpiimkqf.html

[D26] 数组转字符串
来源：http://dali.316326.xyz/Article/details/gtztutbnqi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtiruowggy.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtrhhdohcj.html

JS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtjyokmdsb.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtrmhnslip.html

Java: String.join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtskkaqnys.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtzfzhuwmm.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtdgytkito.html

C#:   string.Join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gtzciouoev.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtijdcykti.html

E. 字符串处理
来源：http://dali.shzxlz.cn/Article/details/gtqynsphor.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvqwrlgze.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtzbfauakp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.316326.xyz/Article/details/gtrixkbytl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gtffljsyru.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtquapujrq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtvzfpqnvs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gthaqrnqkl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.birdmap.top/Article/details/gtvbfgcnec.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ehwqpu.com/Article/details/gthwwulzog.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtwzeeskcx.html

[E02] 重复字符串
来源：http://dali.c1oappe.top/Article/details/gtahprbars.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtrirwgrkm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xylfe.cn/Article/details/gtbgthvtsh.html

JS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtnqqplhys.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtmppqmvsr.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtjqcutcqy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gthmnqeyml.html

Ruby: "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gtxkcurdbg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnqzz.top/Article/details/gtbudgddbp.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtbwfzzubh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yanxiufei.cn/Article/details/gtrdfduizu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtihadjrok.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtslmosdxd.html

TS:   s.slice(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtcydbewiw.html

Java: s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtkzciiqln.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtvscweawv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.svipenyu.cn/Article/details/gtrzndpyev.html

C#:   s.Substring(1, 3)
来源：http://dali.xinyue.icu/Article/details/gtspprgcgb.html

[E04] 查找子串位置
来源：http://dali.jinqigfzy.top/Article/details/gtddxkdpiw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tian-w.cn/Article/details/gteuyblmov.html

PHP:  strpos($s, "x");
来源：http://dali.tian-w.cn/Article/details/gtpnicixhs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gtaggdqkpc.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtjdlorstt.html

Java: s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtfvlcudqm.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gtbfkyuzbk.html

Ruby: s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtepluwbbu.html

C#:   s.IndexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtthqneijl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenzaomai.com/Article/details/gtsdncqcnb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gtmfxxgbyy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.c1oappe.top/Article/details/gtgaetpweq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtllyjqlzw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258888.top/Article/details/gtuhivsghq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtolywsajz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gtissytdrj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cqqwz.cn/Article/details/gtrvovsbzq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtrgmxokhb.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gtklehrqbt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gthedljrql.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnahqgzbb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtfyjrdvpl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtflorliup.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtnsmvhhzf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtmzowhhff.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gteyoazrdh.html

C#:   s.Replace("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtdeofmhhs.html

[E07] 按分隔符拆分
来源：http://dali.jqgfzy.top/Article/details/gtgfxpmedd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gogol.net.cn/Article/details/gtxqpxdnew.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yongpay.top/Article/details/gtejvptkbb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.svipenyu.cn/Article/details/gtbvrnzznh.html

TS:   s.split(",")
来源：http://dali.mhx1999.top/Article/details/gtoibtlmkh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gtxkqzbpxb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yueranfly.top/Article/details/gtcvtxewlo.html

Ruby: s.split(",");  s.split
来源：http://dali.kuanghao11.cn/Article/details/gtnuqjdzet.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shangyingyoupin.top/Article/details/gtkoyjlvac.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gtemziafdt.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gtdbzfcjjm.html

PHP:  implode(",", $items);
来源：http://dali.aibaodan.cn/Article/details/gtwuwodijt.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtcoyjkmcl.html

TS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtlrxyuddg.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtiezbygod.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gtbpjgcyzw.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gtzyjzwmub.html

C#:   string.Join(",", items)
来源：http://dali.316326.xyz/Article/details/gtlohnsfie.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gtjkzjrbsl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gtqgigrjiu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gotoacloud.top/Article/details/gtvsbybhdt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtbmhnjbhm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtkqfzpvud.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yongpay.top/Article/details/gtavthiand.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gtugnkplhg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gtdaoafewk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nwbrower.top/Article/details/gtueelkhnp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.bjfxy.top/Article/details/gtpfjplbym.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtihyutevg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gtjiaxgpce.html

JS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtnuldbade.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtbhjqpedt.html

Java: String.format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtrnitaayk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbyaqemw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtrhtlulqz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zdqjudy.top/Article/details/gtjmoekqoc.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gtofrfcztt.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstwkidtl.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtapowedmt.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtinrzodww.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtfmvhxdsh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhixingplan.top/Article/details/gtprjqwnil.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtlqveosme.html

Ruby: s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtbtebravf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtkkfshmlh.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtrtjkoheh.html

Py:   s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtkzlpyawi.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gtprmxunxf.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtzkgyofwx.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtsvnywwat.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gtgtpofgwb.html

Go:   strings.Count(s, "a")
来源：http://dali.ivvv.top/Article/details/gtatkfzocc.html

Ruby: s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtgkvqgfog.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxinkj.top/Article/details/gtdetpckqr.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gtkdkumymm.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gtlcxvzgac.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.mhx1999.top/Article/details/gtojzsensm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtzztnxvha.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtyjbfvflp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuxming.cn/Article/details/gthabmssnz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pycfn.com/Article/details/gtfgvlwnba.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tian-w.cn/Article/details/gttfdlliot.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnztzpxlq.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gtutlcylok.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gteufqonaz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cheryme.top/Article/details/gticongchl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuanzhike.top/Article/details/gtxemyxnln.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuanzx.com/Article/details/gtahzwxjda.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxnqmljc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gtspmrrafw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gthscppxnz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gttkyunpep.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gthnpeisij.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tianlin.xyz/Article/details/gthryavvax.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenlongwang.top/Article/details/gthocbqdaq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tanke756.top/Article/details/gtwvfmlfzl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gtxwqtudih.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdsfeppm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.svipenyu.cn/Article/details/gtsxpgcevi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuanzx.com/Article/details/gtesaxcaug.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sxryk.cn/Article/details/gtlmsfxmok.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gtquhcakvi.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gtoykbrfid.html

PHP:  number_format(1234567);
来源：http://dali.chenzaomai.com/Article/details/gttyqftwdh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtncnrafpd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gthykjdjvj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gtmdoroszh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpucgoumr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jyoumei.cn/Article/details/gtgllysfwd.html

C#:   1234567.ToString("N0")
来源：http://dali.sweek.top/Article/details/gtexhszmor.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gtexgqjrys.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gtlffysonq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtmgudywcl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtbajlutga.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtjhbxpwgm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gtkzrbdrge.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tian-w.cn/Article/details/gtaftuvmlf.html

Ruby: s.capitalize
来源：http://dali.birdmap.top/Article/details/gtlpongarm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxinkj.top/Article/details/gtvwojxvhq.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gtrkqtkvrh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gtbvezmrof.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gtigttwgdw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtdzikqtwv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtenirwblh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtgcsjlior.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gttdsffdhq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gtamkoiiuy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gtswvjzpfk.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gtqkuzjits.html

Py:   s.splitlines()
来源：http://dali.yongpay.top/Article/details/gtvvpaoqdz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtcrxqecve.html


<!-- 参考信息 -->