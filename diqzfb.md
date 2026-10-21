代发 wailian999

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gttoilekap.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gtsuvflvln.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gtegfjcowy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sufxvd.cn/Article/details/gtiqrfzbwf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gtfbwccmff.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtfuzjbvqq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtksgrdpiy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aizwys.cn/Article/details/gtvsdvxqwn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jianghu66.top/Article/details/gtnlxnalap.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoeioloyk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jianghu66.top/Article/details/gttzpeyyrm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gtlmogehry.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gtuwosuvvw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hammf.cn/Article/details/gtrgncuifw.html

JS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtemwjzjdn.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtlqhynilq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gtdntzunxf.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtoyfujruq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtfwejaoby.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258888.top/Article/details/gtcinokfjk.html

[D15] 去重
来源：http://dali.yj20258888.top/Article/details/gtkejzblgv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtmgbufxjf.html

PHP:  array_unique($arr);
来源：http://dali.yuxming.cn/Article/details/gtkacocdjl.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtdsbqalbq.html

TS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtprwiubfg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgfzy.top/Article/details/gtdjqqngsj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gtxrcnhbhy.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsoolcit.html

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gtjnixabhm.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gtzvtcpamx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtjgfagemv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtwwxjitfw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtklrymrjq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtihxpddek.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.9152youxi.cn/Article/details/gtxulezilz.html

Go:   // 手写循环累加
来源：http://dali.bjfxy.top/Article/details/gtyvhzgief.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gtdhsxinsf.html

C#:   list.Sum();  list.Average()
来源：http://dali.dianchejie.cn/Article/details/gtfzacwkzs.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gtsufysmuk.html

Py:   max(arr);  min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtvptcvowh.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmavunjy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hfpthk.cn/Article/details/gtdorlzket.html

TS:   Math.max(...arr);
来源：http://dali.sxryk.cn/Article/details/gttzmhfkpc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dashuyun.cn/Article/details/gtpsknhhkq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gttxhkmzvo.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gtgmjaawst.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gtnxdmodlt.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gtcdotxhyz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.quarkkingdee.top/Article/details/gtohluzrwy.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gtqermpcoq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.0kj1m.cn/Article/details/gthhvqloqf.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gtvdmqxsqu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xziqi.cn/Article/details/gtuatflytt.html

Go:   // 手写双层循环
来源：http://dali.sxryk.cn/Article/details/gtmpsijtdh.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gttvmxpbqa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gtktezzzyc.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gtfqqrwfky.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hfpthk.cn/Article/details/gtbyjsvyba.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gtpblhuyrk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yanxiufei.cn/Article/details/gthfidbhjc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtedekoyfq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gthpeknksn.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gtmiysvkgz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gtglwurwdi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hysaishi.cn/Article/details/gtmifkgriq.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gtfshsrlnj.html

Py:   Counter(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtpfvphucr.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtakkefysr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtegzyyrjz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtfqwexyhi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigfzy.top/Article/details/gtmgydjfxm.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gttdhrwnvr.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gtghjvrfnu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gaohongyu789.top/Article/details/gtysdwyecf.html

[D21] 判断是否包含某元素
来源：http://dali.yuanzhike.top/Article/details/gtgizjzoto.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gtagcrykig.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gtuscmlpfb.html

JS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtvtdnbukx.html

TS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gtibvzsjtp.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtdmlbvcvg.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtfvmtoxjv.html

Ruby: arr.include?(x)
来源：http://dali.andypj.xyz/Article/details/gtvgbyjbij.html

C#:   list.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtetlawxje.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258888.top/Article/details/gtsrmrhglq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ppjwa.cn/Article/details/gtzqstxoip.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gtklizqqvz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dianchejie.cn/Article/details/gthommzgmd.html

TS:   [...arr];
来源：http://dali.havefunace.top/Article/details/gtnocibasr.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gtewvoeove.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gtieerbhcz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuanzx.com/Article/details/gtilvzafpm.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gttmbdqjzr.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gttqlsdrht.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gtwhnvcull.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nwbrower.top/Article/details/gtqeqjcuto.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtkjvgbzjr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gthvpcevas.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gttsintkum.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gtcnfcuflv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cdnleiting.top/Article/details/gtoshizijf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtebfonycl.html

[D24] 字典 / Map 基本操作
来源：http://dali.andypj.xyz/Article/details/gtavihlkwc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gtlbgadkhm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sufxvd.cn/Article/details/gtkcusmaes.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gtgvypfvvj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gthqasgqfc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yongpay.top/Article/details/gtvkltdgdx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sxryk.cn/Article/details/gtdxgdlstk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ydzc1.top/Article/details/gtfpiwuiqs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xylfe.cn/Article/details/gtjfpkpits.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigufen.top/Article/details/gtzpiojyof.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgfzy.top/Article/details/gtlrhaferc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegfymbkt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gtewxfjccq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cdnleiting.top/Article/details/gtpgjcrvqa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtnmbzllxv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cashguo.top/Article/details/gtxxktkxju.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gtvjrkcjzo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yvedp.cn/Article/details/gtzuhgulju.html

[D26] 数组转字符串
来源：http://dali.redwolf501.top/Article/details/gtwslnhfuw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.316326.xyz/Article/details/gtbrndcxmv.html

PHP:  implode(", ", $arr);
来源：http://dali.tanke756.top/Article/details/gtwtdacnqd.html

JS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtqdwekcdi.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtmcmyilgn.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtvqebshue.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gtgivzwsjd.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtmwlzastk.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtywepzulv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxxayaqlg.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gtflgftotf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafhdubao.html

[E01] 拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtapeusazn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ydzc1.top/Article/details/gtdhkrcuik.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xinyue.icu/Article/details/gtioewoeky.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gtovnmovcd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gtkvzqeovj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtsdjblopv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cdnleiting.top/Article/details/gtkjpepmov.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gtvnkjmfxf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtzxuxtscy.html

[E02] 重复字符串
来源：http://dali.shzxlz.cn/Article/details/gtmfyngguy.html

Py:   "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplrjhibb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.haohaochexian.top/Article/details/gtuxkuprir.html

JS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtoofjxecg.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gttputhamm.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyxamqut.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gteabjxegk.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgfojmeq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gteuyymcrb.html

[E03] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtjuaizktg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.feifeiyinyue.top/Article/details/gthzwlafdr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyavoxjn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gthojmczug.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtlaedjnpd.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtsavcbwol.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtpppqvjwp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.snrcjt.cn/Article/details/gtyfaxjtyw.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gtbbxxaxmh.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gtmhuxcdgp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tian-w.cn/Article/details/gtxwvrzmmg.html

PHP:  strpos($s, "x");
来源：http://dali.chenlongwang.top/Article/details/gtqhlsttus.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gtwojlzrrt.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtzomlwjuo.html

Java: s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtykzcpjzh.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gtuywruddk.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtkiyeqvjv.html

C#:   s.IndexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtijqufpxr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenzaomai.com/Article/details/gtrnsglxec.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.meibo888.top/Article/details/gtdfqamvlm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenzaomai.com/Article/details/gtndsyjgcg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gtbthknmfl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xinyue.icu/Article/details/gtsunspodq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtjslyljnh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.andypj.xyz/Article/details/gtxrdysviu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gotoacloud.top/Article/details/gtlpfgoubb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtwonfnprr.html

[E06] 替换子串
来源：http://dali.hnxiangtu.top/Article/details/gticpjybhs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtzcbwisqt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ybcxt.top/Article/details/gtjmdkzksj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtnkyvvuao.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcpffsef.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtzkodddni.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtjagqtbgh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtuiquzlkm.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtzpoxfkfj.html

[E07] 按分隔符拆分
来源：http://dali.xylfe.cn/Article/details/gttvyqbefl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gtrkprfiye.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtanxheenl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fzhhl.top/Article/details/gtakjbpres.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gtorbkgegv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgufenzy.top/Article/details/gtfdpbvkpu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daxiang520.top/Article/details/gtjcfeplyh.html

Ruby: s.split(",");  s.split
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwxmepxq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ppjwa.cn/Article/details/gtoizgfzlb.html

[E08] 数组按分隔符合并
来源：http://dali.sufxvd.cn/Article/details/gtsujqypyy.html

Py:   ",".join(items)
来源：http://dali.tianlin.xyz/Article/details/gtiiermpaj.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwphxmvmf.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtewvzrepf.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtcgzgenth.html

Java: String.join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtyzpdhcfl.html

Go:   strings.Join(items, ",")
来源：http://dali.iojbl.cn/Article/details/gtiofqoyga.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtwrftuzxc.html

C#:   string.Join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvfrdvxr.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gtgtotdmyh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gtquxdgozv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258888.top/Article/details/gtvkebsoia.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gtyhenskns.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gtirocmsbh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtjmqjurrp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hysaishi.cn/Article/details/gtgikjclsw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.kuanghao11.cn/Article/details/gtocbjdgdq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gtoakfkekw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gotoacloud.top/Article/details/gtpzxnqjzc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcofwxak.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtplomtyis.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtyeyncmoc.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtpcoiraod.html

Java: String.format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gthqxofugw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtplvogvdq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtyiajcnjs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.bjfxy.top/Article/details/gtionputmh.html

[E11] 反转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtotldfcld.html

Py:   s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtlsmdrbul.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtkkshxqru.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtpgqfjbxk.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyodahpur.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gtkugvhagt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtuwjlnmxr.html

Ruby: s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtritvtwes.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtirbrhjid.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gthdjtrmrs.html

Py:   s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtexnbuzub.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gtzahmcpad.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gtnefskrgg.html

TS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gtsskzucjy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jlsjyb.cn/Article/details/gtkqfintsy.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gtcrmsqgnq.html

Ruby: s.count("a")
来源：http://dali.havefunace.top/Article/details/gtnecyvmvz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gtrdkakpzx.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gtkgasbmjw.html

Py:   for ch in s: print(ch)
来源：http://dali.xuetiantiany.cn/Article/details/gtiqobiscf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gtbbfvzmct.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gtkzlzepda.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtuxwnopvx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtkqxrzqja.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gtlakgehhq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aizwys.cn/Article/details/gtsqclrepq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gtdzchpaks.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gtluvulnld.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yanxiufei.cn/Article/details/gtgvdjgmhx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gtjmaflqvn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shzxlz.cn/Article/details/gtkwnmffbz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtikmntmxc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalqdwqmw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gtqfzrkvdr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgfzy.top/Article/details/gtmnvlxlpt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.meibo888.top/Article/details/gtsvmfvwoi.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gtohenjkpq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gtwvrytqxt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gthzueyeyu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gtyqalnvwq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yanxiufei.cn/Article/details/gtwvoxeszv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sysykeji.top/Article/details/gtxzbeyapt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gttdtvtsad.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daxiang520.top/Article/details/gtwihxqiyd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.smart0.xyz/Article/details/gttqbdepau.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gtkdfxjhhy.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigfzy.top/Article/details/gtzxcoqwdg.html

PHP:  number_format(1234567);
来源：http://dali.aibaodan.cn/Article/details/gtvgccslzg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtoxdgrcte.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtyakwyezo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtkoydghwr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ybcxt.top/Article/details/gtpgxfzrwj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtosadjakd.html

C#:   1234567.ToString("N0")
来源：http://dali.316326.xyz/Article/details/gtqeyccmmx.html

[E17] 首字母大写
来源：http://dali.andypj.xyz/Article/details/gtzkllmlfy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtxbnymtvc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gthdexsuuq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtdikfxvho.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gttutvcoib.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gtdwpscpkk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenzaomai.com/Article/details/gtdwejtike.html

Ruby: s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gtkygitumw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtesjugxub.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gtqkxciflz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuxming.cn/Article/details/gtqmmsbqhw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyufwtasq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtpssmmrgp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtkccobliq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtymbqjizu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtusbvdwea.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gtpnkthygg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gtdpoxiwtf.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gtyisebuqu.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gtvkwysdwn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtsonaokfu.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtbuoiklvm.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtggwaiava.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gthtnomdnj.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gtekwktlpv.html


<!-- 参考信息 -->