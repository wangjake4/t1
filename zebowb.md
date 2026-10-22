代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gogol.net.cn/Article/details/gtcbkqzlbe.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gtqsytgznu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fengsongda.top/Article/details/gtoywldftf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gtnngrloox.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sufxvd.cn/Article/details/gtsnchwott.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtdljkliuo.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtskglhask.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtmaxghhvi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gtijamtjvv.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtcelfncne.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.316326.xyz/Article/details/gtwcxksrbw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gtdmqqtnmc.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtrlxrlcgh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtvybbkijn.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gtxxcwfvyu.html

JS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtqlrfmeix.html

TS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtylwreaga.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ybcxt.top/Article/details/gtvwcrdxfd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.bjfxy.top/Article/details/gtdwylquyf.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gtwxwvfomd.html

C#:   list.Distinct().ToList()
来源：http://dali.gaohongyu789.top/Article/details/gttpjjvxev.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gthxphfqwa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cucudq.cn/Article/details/gtfjddypdl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guowangkeji.top/Article/details/gtqjbnnysa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtlumkxood.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtzwwudtzd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gtywcnbloi.html

Go:   // 手写循环累加
来源：http://dali.jqgufenzy.top/Article/details/gtttavhzau.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gtglkrnlwa.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gtcwgkvvub.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gtblomzghn.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gtrmfykawt.html

PHP:  max($arr);  min($arr);
来源：http://dali.cheryme.top/Article/details/gtcbfandwo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daria6918.cn/Article/details/gtodmjhcjh.html

TS:   Math.max(...arr);
来源：http://dali.dianchejie.cn/Article/details/gtdaujcqgn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxinkj.top/Article/details/gtlrcurupn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gtqnlibpiu.html

Ruby: arr.max;  arr.min
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdnupytf.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigfzy.top/Article/details/gtsksorvmz.html

[D18] 扁平化嵌套数组
来源：http://dali.fzhhl.top/Article/details/gtfngfacxr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gttkvaajqr.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gtkvfufviq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gtlnqydxju.html

TS:   nested.flat();
来源：http://dali.chenlongwang.top/Article/details/gtaremqbzr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtxrodsxal.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqgscnbt.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gtojwjpkaj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtziqyqlfd.html

[D19] 按字段分组
来源：http://dali.jqgufenzy.top/Article/details/gtnudskyvk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gtqnywqgqf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gtfmmcjsms.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xziqi.cn/Article/details/gtoyvrdeju.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gtrcdtqugd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zycfv.cn/Article/details/gtklntkydv.html

Go:   // 手写 map[string][]T
来源：http://dali.andypj.xyz/Article/details/gtbsgxpunw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gtmyzspsdk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhengqikj.top/Article/details/gttljzlqhz.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzwepikf.html

Py:   Counter(arr)
来源：http://dali.xinyue.icu/Article/details/gtwemfujoc.html

PHP:  array_count_values($arr);
来源：http://dali.jqgfzy.top/Article/details/gtalnkyfcp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtmagykjmz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtjuscqhxa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gtqirsuqan.html

Go:   // 手写 map[T]int
来源：http://dali.jyoumei.cn/Article/details/gtbozrueqg.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gtslfvxzpq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gthiuksxho.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gtsgttdukd.html

Py:   x in arr
来源：http://dali.nwbrower.top/Article/details/gtjcnebmvq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtquiifgrc.html

JS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtsuwjswrr.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasunbowq.html

Java: list.contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtelimfjji.html

Go:   slices.Contains(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtkifrxmol.html

Ruby: arr.include?(x)
来源：http://dali.andypj.xyz/Article/details/gtloqkpkcg.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtnxzrmbvf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gtvtxhqyhk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhixingplan.top/Article/details/gtjmfsindx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigufen.top/Article/details/gthxjzpcdf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigufen.top/Article/details/gtlqfxkarq.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gttqomqgql.html

Java: new ArrayList<>(list);
来源：http://dali.aizwys.cn/Article/details/gtfxtgxvxz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gtpdvolhps.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gtupqdgepz.html

C#:   new List<int>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtwjmzkypc.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gtmdoliuuj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gtmofuggij.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gtmnorlxga.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtjewmcpzz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtjjlmbknb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhoulong.xyz/Article/details/gtkkvlwypt.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtmfjmbmvt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gtbtjyniqz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pycfn.com/Article/details/gtbtkqljvs.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gtklhuvjcv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fzhhl.top/Article/details/gtkdpcsmlk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gtwxbzfdga.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gttsyjdzpw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtlmnfstdu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daxiang520.top/Article/details/gthbedghok.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenzaomai.com/Article/details/gtirtcitbv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtogeopxvt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gtegbijhjq.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gtqlettwaz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gtpqanoatr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gtdktgoumr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dianchejie.cn/Article/details/gtzmhxfqro.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjuxcgnm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258888.top/Article/details/gtyukahdiz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gtrifdjmsb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.havefunace.top/Article/details/gtlnpazpka.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gtmbroucah.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcywekle.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tian-w.cn/Article/details/gtlimeidlm.html

PHP:  implode(", ", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtyijqrbgi.html

JS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtwmutdpex.html

TS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtocbbxptv.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtkvkybdet.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gaohongyu789.top/Article/details/gtknmzrhyq.html

Ruby: arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtuqauiefv.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258.top/Article/details/gtgmzhbpto.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktpsljen.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gtchfjcxmb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtminpyllu.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtmcnrrdmt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ppjwa.cn/Article/details/gtndwfpasj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtnagdyflz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtcbnwotgi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtkyldtolj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gtyskcoyrk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtmbsuadzv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinghuilouyu.cn/Article/details/gtqignvuzq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtbvxdjgja.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gthiaxzmuo.html

Py:   "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gtioclpnlr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gtzpmxqnai.html

JS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtldbwmypm.html

TS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijcmcnhf.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtdiuamlwx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtupllhwbx.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtqpivcjrt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfaviemnc.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtugffhztv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gotoacloud.top/Article/details/gtjvvvwqkq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbeyeutur.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gttltfnwma.html

TS:   s.slice(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtaqtibytr.html

Java: s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtwosieaav.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cashguo.top/Article/details/gtkuometmh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yangfankeji.com/Article/details/gtujxnkwlw.html

C#:   s.Substring(1, 3)
来源：http://dali.zhixingplan.top/Article/details/gttuvcnewz.html

[E04] 查找子串位置
来源：http://dali.zycfv.cn/Article/details/gttpfpczgk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gtipomzydh.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gtwabmshoj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gtjyespedt.html

TS:   s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtfjcnviru.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtiachozyp.html

Go:   strings.Index(s, "x")
来源：http://dali.shzxlz.cn/Article/details/gtlsqhfkcw.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtokpqvrub.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gtbasuwjrc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.andypj.xyz/Article/details/gtxtwzrbey.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gtkaafqxrh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdzaurpc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtkwmoxnre.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gtvsmhbnii.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtpiiiiutm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuanzhike.top/Article/details/gtxonjewwg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zdqjudy.top/Article/details/gtgyjacain.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hammf.cn/Article/details/gtusfymoti.html

[E06] 替换子串
来源：http://dali.birdmap.top/Article/details/gtolmpgwpo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gtsygrwawn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtuczfbbhq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtigtgfuar.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtkklqsnoy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtzezjkxvi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtuvittiba.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gtbqeiphfq.html

C#:   s.Replace("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtheeuovpo.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gtrgttsuzk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ivvv.top/Article/details/gtwagrlopk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guannengcc.top/Article/details/gtxiqzhawa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jianghu66.top/Article/details/gtujgtjxyt.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gtzxemofdo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gthkeyoxrl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.svipenyu.cn/Article/details/gtygfgsgbw.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gtioxsyvuj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgfzy.top/Article/details/gtkhpsheys.html

[E08] 数组按分隔符合并
来源：http://dali.cucudq.cn/Article/details/gtthavmouo.html

Py:   ",".join(items)
来源：http://dali.gotoacloud.top/Article/details/gtyhglrblj.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gtpbynxcxm.html

JS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtzjidsmuf.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtftgieimq.html

Java: String.join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gtfnjdlhrl.html

Go:   strings.Join(items, ",")
来源：http://dali.kuanghao11.cn/Article/details/gtcgvytrne.html

Ruby: items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtjqrhvxxa.html

C#:   string.Join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtrftytxcw.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gthhsztfqs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuxming.cn/Article/details/gtklyfivlx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.havefunace.top/Article/details/gtzffaowhp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gthxahmaqd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtpbqbkoet.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gthajrrwcx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gtzcppqozj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtadhtmhkt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cheryme.top/Article/details/gtxpioitre.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jianghu66.top/Article/details/gtonjtshuw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hammf.cn/Article/details/gtstqfvpfh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gtbhhbagdq.html

JS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtfzbigiiw.html

TS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtinylkuwu.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtevxsquqx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcheilfxz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtyrgscltk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigfzy.top/Article/details/gtdgehiyqf.html

[E11] 反转字符串
来源：http://dali.sweek.top/Article/details/gtgnouujox.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtwgshdaxa.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtdgrbfxzj.html

JS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtxfxwvhxc.html

TS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtembtuncl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtpbdvjpaj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gtakpenaxw.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtkxffwatm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtpcvoildd.html

[E12] 统计某字符出现次数
来源：http://dali.xziqi.cn/Article/details/gtinhbmlaf.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtsdukxygv.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gtkepevvkc.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtynsiaoiu.html

TS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtfsgyeazi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.andypj.xyz/Article/details/gtivejewhw.html

Go:   strings.Count(s, "a")
来源：http://dali.xziqi.cn/Article/details/gtmriceqdt.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtcjsbjqvb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gthymzadzu.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqvwqmci.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gtluiopxxg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrlhyqxl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkbdbcwzm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtbezzzpkn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtbwoqgjnv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gtypbpfjez.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gtudcnfcjo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daxiang520.top/Article/details/gtomikiykg.html

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gtuyrjcmjs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigufen.top/Article/details/gtwipujrdw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtdmpeblor.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gthjyqxldu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gtqqzpfywf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nwbrower.top/Article/details/gtglbielnh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gtkvqfcoov.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gtpndkqyvx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtlwvlyfxo.html

[E15] HTML 转义 / 反转义
来源：http://dali.ppjwa.cn/Article/details/gtdrgsllzx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gtrnihemgy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ydzc1.top/Article/details/gtuxiiuetj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtrpnkjcof.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gtjsjlqlnv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gtnbxjuwlr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shuidangran.top/Article/details/gtsbclcots.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gtmpghnjox.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmekglvms.html

[E16] 数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gtkynaltfq.html

Py:   f"{1234567:,}"
来源：http://dali.chenzaomai.com/Article/details/gtbiojoxtt.html

PHP:  number_format(1234567);
来源：http://dali.quarkkingdee.top/Article/details/gtizymxcuo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtrpscbjcu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtpnguajgq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtwovmqare.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gtoqsclyui.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigufen.top/Article/details/gtqxywkxjb.html

C#:   1234567.ToString("N0")
来源：http://dali.tianlin.xyz/Article/details/gtqdmxvxmw.html

[E17] 首字母大写
来源：http://dali.cdnleiting.top/Article/details/gttcjwvijj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.c1oappe.top/Article/details/gtidumbtam.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tanke756.top/Article/details/gtfbdikfyz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtiqjdgmrb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtuoqmftbw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.9152youxi.cn/Article/details/gtborogngz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yvedp.cn/Article/details/gtmjtithxu.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtondhesug.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sufxvd.cn/Article/details/gtkbmqtvvt.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtcaehlfbf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shangyingyoupin.top/Article/details/gteeqikfpo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenjidiqi.icu/Article/details/gtngtaolns.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtqrbfweln.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtgufrbsbo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtmnuyjjma.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtpemycrcd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gthpslakfc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fzhhl.top/Article/details/gtcivqzkyg.html

[E19] 多行文本按行拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtiniqurxh.html

Py:   s.splitlines()
来源：http://dali.xziqi.cn/Article/details/gtxvthbcji.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtzszkgrlx.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtrsychhrz.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtjhscqaim.html

Java: s.lines().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtruzcbotz.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gtnrvayozr.html

Ruby: s.lines
来源：http://dali.svipenyu.cn/Article/details/gtpnpiawby.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gtbolkskdo.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtgzpflchd.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gteudzvtli.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhongyouzk.top/Article/details/gtzilqdafd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gtyynoioxj.html

TS:   if (s === "") {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbrgmgdai.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefghwiyb.html


<!-- 参考信息 -->