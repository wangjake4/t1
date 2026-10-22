代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtixdtynkn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtgjvijezj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.snrcjt.cn/Article/details/gtevdimpqu.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtfxyoiyrg.html

Ruby: arr.index(x)
来源：http://dali.smart0.xyz/Article/details/gtfhrenwnl.html

C#:   list.IndexOf(x);
来源：http://dali.smart0.xyz/Article/details/gtomsfmkdy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiiszfshv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtztdrzmaf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sysykeji.top/Article/details/gtufiuawti.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtnuxwyvxs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtfuxnorlp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gtilwegrup.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shuidangran.top/Article/details/gtjinynqbb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhoulong.xyz/Article/details/gtqfutbgwf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gtbonmeqbv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gtcobqfwtz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yonumen.top/Article/details/gtenzujwaa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtrsdhosjn.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtvgwmgwjh.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtfekogekm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiufyxdgw.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtugijzake.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gttgpvtzyc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.havefunace.top/Article/details/gtkdolzvoc.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzbzvhpr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtgpkqfyff.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gttgruvxol.html

JS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtrnrsslbm.html

TS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtghdapbzu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hysaishi.cn/Article/details/gtdcpfzkkv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gtdrgtfaoe.html

Ruby: arr.uniq
来源：http://dali.gotoacloud.top/Article/details/gtvcxysijj.html

C#:   list.Distinct().ToList()
来源：http://dali.xylfe.cn/Article/details/gtinjkywbu.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gtgbexfjcl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtioytemey.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gtoqqsqaui.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtaqfftlvl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtxauiekbx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gttcnbemkc.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gtxepnrceq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tanke756.top/Article/details/gteontazhu.html

C#:   list.Sum();  list.Average()
来源：http://dali.daria6918.cn/Article/details/gtmukqxuhd.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gtvqgurhdx.html

Py:   max(arr);  min(arr)
来源：http://dali.dashuyun.cn/Article/details/gthgssxmxj.html

PHP:  max($arr);  min($arr);
来源：http://dali.cucudq.cn/Article/details/gtzdvqglff.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dashuyun.cn/Article/details/gteadgbxlz.html

TS:   Math.max(...arr);
来源：http://dali.yangfankeji.com/Article/details/gtksaksxph.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gtvjbjjrsd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.birdmap.top/Article/details/gtjbhfitvv.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhnvgpbz.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gtwuwocswm.html

[D18] 扁平化嵌套数组
来源：http://dali.jianghu66.top/Article/details/gttjgvobeb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gtwlqtjwnl.html

PHP:  array_merge(...$nested);
来源：http://dali.feifeiyinyue.top/Article/details/gtdtjkdmxg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gtwsvoymnb.html

TS:   nested.flat();
来源：http://dali.ybcxt.top/Article/details/gtatmfgdyl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuiqzgmfp.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gtkvmykwcm.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gtwktjcotw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gthuqedlgo.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinifosxx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gtqtbhgjjm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gtbkavicwi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.iojbl.cn/Article/details/gtsicogdby.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylxsjsil.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gttamywevb.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gtnhvjidaj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gtncdvwpsd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gtfkntjcee.html

[D20] 统计每个元素出现次数
来源：http://dali.ybcxt.top/Article/details/gtpozpwjfz.html

Py:   Counter(arr)
来源：http://dali.aibaodan.cn/Article/details/gtcvknjcmx.html

PHP:  array_count_values($arr);
来源：http://dali.iojbl.cn/Article/details/gtaklkfxwi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnfqeinj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gthfcuptlw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aibaodan.cn/Article/details/gtyeuwonwb.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gtziwewcbu.html

Ruby: arr.tally
来源：http://dali.jiagoushi.top/Article/details/gtwllkrrnf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gtaeqqwfji.html

[D21] 判断是否包含某元素
来源：http://dali.yuanzhike.top/Article/details/gttyimcusa.html

Py:   x in arr
来源：http://dali.jinqigufen.top/Article/details/gthabrbyzx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gttbfveqby.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtobaimhpg.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtdnjxwvod.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezfryvty.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj202588.top/Article/details/gtrzaxquvl.html

Ruby: arr.include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtrscjlxkc.html

C#:   list.Contains(x)
来源：http://dali.cashguo.top/Article/details/gtjctkzxkh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinghuilouyu.cn/Article/details/gtygmptbee.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gtkzsdglpt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhoulong.xyz/Article/details/gteivrkshc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ehwqpu.com/Article/details/gtvvbgjgqg.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gtshyuxhec.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gtpwhrezlw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258.top/Article/details/gtxhgyqknn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aibaodan.cn/Article/details/gtoztxirso.html

C#:   new List<int>(list);
来源：http://dali.zycfv.cn/Article/details/gtztwusrpu.html

[D23] reduce 累积计算
来源：http://dali.gzhubu.top/Article/details/gtsedxzwii.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gotoacloud.top/Article/details/gtbucnodup.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gtmrtizomg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtfzwamxfb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gtjrvaxjkp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.meibo888.top/Article/details/gtxihvazee.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtkjozzkty.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gtnauvzzog.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gtmxrpjaqf.html

[D24] 字典 / Map 基本操作
来源：http://dali.birdmap.top/Article/details/gtahnksoab.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtxrepiaeq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ybcxt.top/Article/details/gtczixzfmp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gtwosduhyq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtcudsuxjq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ydzc1.top/Article/details/gtsfsjvgkk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gtonohzlzp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gtyqsadlah.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgfzy.top/Article/details/gtomsasond.html

[D25] Set 集合去重与交并差
来源：http://dali.316326.xyz/Article/details/gtcuipqkuu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtooakjgcf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shzxlz.cn/Article/details/gtojbkyfba.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guannengcc.top/Article/details/gteorpojkr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gttcllrymq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gtwbzmtnii.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtlmeirszl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zycfv.cn/Article/details/gtqqcuqseq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtfrnwqicp.html

[D26] 数组转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzynyqhe.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gtlxlfmmxv.html

PHP:  implode(", ", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtuoopovib.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtjchaaxjt.html

TS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtnwqsekva.html

Java: String.join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtixatjmoe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtqjxlkorf.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gthbyzaoyo.html

C#:   string.Join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gthsblqcdu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtbfeuwtun.html

E. 字符串处理
来源：http://dali.wangdashe.top/Article/details/gtoigopjim.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gttymogvhq.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtcwraprgb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpepmedgo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtmrlqebcp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtpupfaidu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtqkjlfgxy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtechbbizp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnqzz.top/Article/details/gttryplelt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yongpay.top/Article/details/gtqlrtoygk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.meibo888.top/Article/details/gtqpcsukzy.html

[E02] 重复字符串
来源：http://dali.pycfn.com/Article/details/gtycvhxgfj.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtnihukcqn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zdqjudy.top/Article/details/gtpeeijkdg.html

JS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtgvgtxgas.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtebppeybx.html

Java: "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtiduhabni.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gtjmcynpyu.html

Ruby: "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtcmrktfmh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hammf.cn/Article/details/gtujyeclnj.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejzlonzf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gtzqtmrrmd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtfswovbdx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtghhvrynf.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtqgjztmho.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtvyegmuqx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuxming.cn/Article/details/gtiiobjihs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dianchejie.cn/Article/details/gthbbwpjny.html

C#:   s.Substring(1, 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtaxggngdp.html

[E04] 查找子串位置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtxqpmgy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtbkafebon.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gtjlqurnff.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hywenlv.cn/Article/details/gtmsannkkn.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtplvreklt.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtwwowrtxa.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gtqqkheryg.html

Ruby: s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtavhgzvhy.html

C#:   s.IndexOf("x")
来源：http://dali.sweek.top/Article/details/gtfssmceqq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gtwgxetgsk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszxxwdmn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizimdaoj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtjnbgglla.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xylfe.cn/Article/details/gtshpolntb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtnnhnxoqb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sxryk.cn/Article/details/gtyfdetcbz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtngkcibda.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtltmkxijr.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gtcypfcdqg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtnbffqmpr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gtpixjwajj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbiqujyh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtpfrxdvjh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtvbyjduoe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtipnqujjo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtstehhmgx.html

C#:   s.Replace("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtnqycfcod.html

[E07] 按分隔符拆分
来源：http://dali.jinqigufen.top/Article/details/gtsktnfgub.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.redwolf501.top/Article/details/gtciuussgw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtmfrvyfds.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtaitcgivr.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gtsubbjcwl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.kuanghao11.cn/Article/details/gtzxqqwela.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gtemqpxrqw.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gtbyzpbdgg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gtgchgvger.html

[E08] 数组按分隔符合并
来源：http://dali.aibaodan.cn/Article/details/gtegtixojl.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtzhfedumz.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtemqlwqox.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtedptzwoz.html

TS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtykabrveo.html

Java: String.join(",", items)
来源：http://dali.hnqzz.top/Article/details/gthasxjnry.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gttwxzaiew.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtrhnwuhbb.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtwnierpyf.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gtttsrubuq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shzxlz.cn/Article/details/gtoejnewzl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shzxlz.cn/Article/details/gtjxglbfcl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtyxibbdtc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtopvclfyp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gthfpblhns.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gteesubszu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gtvboucsjo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.havefunace.top/Article/details/gtevgayyze.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnpmutsm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwwmfwpj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gtypugzlra.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtnpevoefx.html

TS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtegjxmrcr.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtuphmxgpu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtwpksntos.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtrgnrxylf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gtcfrpzmbm.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gtnryzjgoa.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtotqfbdbn.html

PHP:  strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtmopdpynn.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtwjeelogl.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtrnmoikiw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.bjfxy.top/Article/details/gtqeyxsqdj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtgplxydps.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gtyrtodcvc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gteizofsep.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsgkfpoe.html

Py:   s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtfugjbuoo.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gtrwbgnnlp.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtospxptiw.html

TS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtvxgbzhnh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ivvv.top/Article/details/gttrpuhwjq.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gtvfybqrdl.html

Ruby: s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtwlyzamdz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.quarkkingdee.top/Article/details/gtsfaphaon.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gtzeqjtzlo.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gthfvciqfn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.c1oappe.top/Article/details/gtslkbwpqz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtvdnoidyl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gtllcmvzrq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gtbnqptqsi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gtrubdqodx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sysykeji.top/Article/details/gtcdjxkgag.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.mhx1999.top/Article/details/gtcayoczce.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gteiiaybqf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tanke756.top/Article/details/gttpnpxhcg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.havefunace.top/Article/details/gtrztqdjfe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gtgasvliie.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dashuyun.cn/Article/details/gtwuuzwsjo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtfzswxwop.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.316326.xyz/Article/details/gtrzhlloqd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gtfakujviq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtpnloqndm.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuetiantiany.cn/Article/details/gtspthqmfv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xylfe.cn/Article/details/gtmqnrchyq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gtlatebvtd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gthmgntxix.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtlgjkojpo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gtubclltwu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtgtucsgna.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.haohaochexian.top/Article/details/gtkfkzvkqk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtfkuelobd.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gtsguakrlc.html

Py:   f"{1234567:,}"
来源：http://dali.nwbrower.top/Article/details/gtmeaoomrh.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gtrodgxmfa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbjecbno.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtkedgvuaj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gtadrzoblr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gtvxloyhex.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hammf.cn/Article/details/gtikgdbcgl.html

C#:   1234567.ToString("N0")
来源：http://dali.xuetiantiany.cn/Article/details/gtefdfyhlm.html

[E17] 首字母大写
来源：http://dali.daria6918.cn/Article/details/gtkllyqjra.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtemvtjljt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuyyitwy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtjskghdgq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtqrdjnuvb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgfzy.top/Article/details/gtbyprmthg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtdmnfsoom.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtozqvejyc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuxming.cn/Article/details/gtgahpcdvb.html

[E18] 模板占位符替换
来源：http://dali.shuidangran.top/Article/details/gtykwggoeu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gtblcimced.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cucudq.cn/Article/details/gtobsatedo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtlovbauya.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtgeswvcbl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtnoafvcql.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gtgamldefi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfnmvlpp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtmujslltw.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gtovaquqkz.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gttwnrhbdw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtoipfhgky.html


<!-- 参考信息 -->