代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aizwys.cn/Article/details/gttqtnbimg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jlsjyb.cn/Article/details/gtjmeagnfi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtjehugmdk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbruswjv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gtzjxzuylm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shuidangran.top/Article/details/gtbrwghggq.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfasbjdz.html

TS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtcdkzseog.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gtnavyvilg.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtlquebjkq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtqvwpljop.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtawobuwvf.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gtrnceavak.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gthfakchdp.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtdbxgbzag.html

JS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtijmvgeuy.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuqydqai.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jyoumei.cn/Article/details/gtubpxtmvr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sxryk.cn/Article/details/gtnxzolibu.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gtoacciexv.html

C#:   list.Distinct().ToList()
来源：http://dali.svipenyu.cn/Article/details/gtocbbebbm.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gtaqbgcidb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtmnkuxlyd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zycfv.cn/Article/details/gtmwnyzdus.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtqsmaobwr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtvyzagftb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gtddkcdvyk.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gtiwqynlqt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gtaumyaifx.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gtsqwzkren.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gtfeirncwe.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gteetekgxa.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gtcjcoiynd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.bjfxy.top/Article/details/gtytufnine.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gtiixwtxpw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkazbvyts.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtflqxepkn.html

Ruby: arr.max;  arr.min
来源：http://dali.fengsongda.top/Article/details/gteojuhksg.html

C#:   list.Max();  list.Min()
来源：http://dali.svipenyu.cn/Article/details/gtrrjsrexh.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gtybphvgvy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuanzx.com/Article/details/gtphezcpgh.html

PHP:  array_merge(...$nested);
来源：http://dali.zhongyouzk.top/Article/details/gtgxgwhboc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zdqjudy.top/Article/details/gtzeocktza.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gtgyjwzvrl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyybqkyiz.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gttspadvsl.html

Ruby: nested.flatten
来源：http://dali.andypj.xyz/Article/details/gttzrvvasf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtmlajybgp.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gtfonlbviz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fengsongda.top/Article/details/gtzjgtsczs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258.top/Article/details/gtidfjpcue.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gtoqpnshqi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gtcapdjrmc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxinkj.top/Article/details/gtwmiwjmjn.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gttattsbzf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gtsnqsmdcg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fengsongda.top/Article/details/gtumlifecf.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gtojzojdvo.html

Py:   Counter(arr)
来源：http://dali.sufxvd.cn/Article/details/gtwgoxjtev.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gtbxkauuxi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtolcmgakk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtaczjpwjj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.mhx1999.top/Article/details/gthwxfpleu.html

Go:   // 手写 map[T]int
来源：http://dali.pengpengdd.cyou/Article/details/gtznkkfbkp.html

Ruby: arr.tally
来源：http://dali.fzhhl.top/Article/details/gtyyecvtly.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtqevkkrdy.html

[D21] 判断是否包含某元素
来源：http://dali.xinyue.icu/Article/details/gturdakqrw.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtywoiclby.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbezenvz.html

JS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtygrzlykt.html

TS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtikmzholb.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtnaxwkfzw.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtfsfnkxky.html

Ruby: arr.include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtawtvxiwe.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gtdaigvzdn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gotoacloud.top/Article/details/gtxywpndpn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yueranfly.top/Article/details/gtsuuhwkrm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtdreyuryk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtdhexksyk.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gtesziwupg.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gtkearileg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.smart0.xyz/Article/details/gtewcrmivo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yueranfly.top/Article/details/gtqxnbkvkw.html

C#:   new List<int>(list);
来源：http://dali.yj202588.top/Article/details/gtacqzqsta.html

[D23] reduce 累积计算
来源：http://dali.yonumen.top/Article/details/gtfvdzedpj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cucudq.cn/Article/details/gtcrqqjsgo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtpczmrwdx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gtsbupazjx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtsgzllovr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj202588.top/Article/details/gthuwreifi.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtgrxmadfz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tian-w.cn/Article/details/gtvzqkitxu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gtcgenndfh.html

[D24] 字典 / Map 基本操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjjnqtzk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xylfe.cn/Article/details/gtlypldxvb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gtvhtonpol.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.andypj.xyz/Article/details/gtellrrfhz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtwtqadmlg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.haohaochexian.top/Article/details/gtjdejkegs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gtpkgpdjci.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fzhhl.top/Article/details/gtocodljpe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gtijszqhnf.html

[D25] Set 集合去重与交并差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupubakxe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gteswcgvmu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikkkvapm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.9152youxi.cn/Article/details/gtwnwapsmt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jianghu66.top/Article/details/gtoouqdscb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtoaanogfr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.bjfxy.top/Article/details/gthkgvahzr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gtnmrwuocp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtyzvzqtmn.html

[D26] 数组转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtexoccfcy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gtygvoucbh.html

PHP:  implode(", ", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtqmeexira.html

JS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtuqoeqgov.html

TS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtmgoevotp.html

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtxfystbqb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtxmtgtbya.html

Ruby: arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtrysyhbtf.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtbneappdi.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtgwruuxoi.html

E. 字符串处理
来源：http://dali.yangfankeji.com/Article/details/gtgrzegkmo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtohoktrle.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtqyshgbfy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzeeilph.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuanzhike.top/Article/details/gtsaybbzkg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtyujrvnla.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtdfecwyoq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yvedp.cn/Article/details/gtiojisjdz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hywenlv.cn/Article/details/gtyumkasyr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj202588.top/Article/details/gttpkwmada.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtsudnqvjw.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gtyucswgwy.html

Py:   "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtmbdjsyol.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gtxyxnwnll.html

JS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtcaxtvsqf.html

TS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtwwvpsuea.html

Java: "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gttfltlbwc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gtkknagzqm.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtxuarhujg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.haohaochexian.top/Article/details/gtrgsviyvm.html

[E03] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gtzrdpcofj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtmaiffpyr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtggwcgrir.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gttgpycwls.html

TS:   s.slice(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtctucimac.html

Java: s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtueblzzhx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtjhroxjsk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtmxaykgqp.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gtdjyorkpb.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gtvlkdrbnf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtragwqxjx.html

PHP:  strpos($s, "x");
来源：http://dali.cheryme.top/Article/details/gtvtpycykk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gtdbsxoalm.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtgkhjyxlg.html

Java: s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbozptchy.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gtyunifktw.html

Ruby: s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gtuzpwyidh.html

C#:   s.IndexOf("x")
来源：http://dali.yonumen.top/Article/details/gtyiunzwjw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258.top/Article/details/gtvksnhqwx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.andypj.xyz/Article/details/gtrikzmewa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhengqikj.top/Article/details/gtulezingw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtexlejixl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtynrnjhfp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtorcxgffh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigfzy.top/Article/details/gtyjvhctiw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dashuyun.cn/Article/details/gtpxsocnfm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtkvvbonag.html

[E06] 替换子串
来源：http://dali.zdqjudy.top/Article/details/gtxsnctkko.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtcdkdydut.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sweek.top/Article/details/gtalhdgzhv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtugprumku.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtriztjimg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtuzwqvybk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtpycbxuno.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtovenfrhv.html

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtxtgcvkai.html

[E07] 按分隔符拆分
来源：http://dali.pycfn.com/Article/details/gtmeuqckxo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cheryme.top/Article/details/gtyeybtjfy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtajtuwkej.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhengqikj.top/Article/details/gtdhlkbyrd.html

TS:   s.split(",")
来源：http://dali.shuidangran.top/Article/details/gtvgggnzmh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gtgxnrloxd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnujpwlyt.html

Ruby: s.split(",");  s.split
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjhgoazu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.snrcjt.cn/Article/details/gteflrlvhn.html

[E08] 数组按分隔符合并
来源：http://dali.cucudq.cn/Article/details/gtyxunvetp.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gtwrppztyp.html

PHP:  implode(",", $items);
来源：http://dali.tian-w.cn/Article/details/gtmycvexld.html

JS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtpsdhybaf.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtgriwzlik.html

Java: String.join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gtcawudfbc.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gtdqeuimlb.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtuiwonxzx.html

C#:   string.Join(",", items)
来源：http://dali.xziqi.cn/Article/details/gtphdfachc.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gthzutobuy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cqqwz.cn/Article/details/gtzvnagxmg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dianchejie.cn/Article/details/gtrkyioppx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtjofccizv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtmbhmjggz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtqoktawqa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gtyiiduqvl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gttpquvfca.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtgzxrmycd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzeydgbk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtbnuecibv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yongpay.top/Article/details/gtznzbhhiw.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtqjcohbdq.html

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gtrksklbyn.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtvwgxtcbw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gteynijthj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtdjmajenz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gthnzlhqou.html

[E11] 反转字符串
来源：http://dali.xziqi.cn/Article/details/gtuebindnw.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtccfrysvw.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtozbyjxlc.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtrckoxqfn.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gthhfdpjkj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangdashe.top/Article/details/gtztvyluan.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sysykeji.top/Article/details/gtqzxsmusv.html

Ruby: s.reverse
来源：http://dali.zhixingplan.top/Article/details/gtlkmfaema.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtyachkqdp.html

[E12] 统计某字符出现次数
来源：http://dali.yonumen.top/Article/details/gtpnggonea.html

Py:   s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtntaqdmbi.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtbkilalue.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtpedvzihs.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcebrnqc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gogol.net.cn/Article/details/gthffmolfc.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gtbddzcdxh.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwwgbapy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gtgpwsmddk.html

[E13] 逐字符遍历
来源：http://dali.yuanzhike.top/Article/details/gtgijenlnc.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gtjlsqxgjf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zycfv.cn/Article/details/gtxydtewxc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtcejngoem.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtbpigzepy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hammf.cn/Article/details/gtrsykhxgd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jianghu66.top/Article/details/gtvexvuays.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gtlcdkkokx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtudxcaeqp.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcycubinl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gtlcabzukm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ydzc1.top/Article/details/gtqfjvfhgt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkabekzca.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hysaishi.cn/Article/details/gtgfzoirxa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtaiiifhah.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gthjreieft.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gttvpptenw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtzatedqog.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtdggumfsx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gtjkgxmlif.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gtouifvhqi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gtdugkgmci.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gtrzoshufo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmaxivxa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtdfkevqqf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gtogygcgbl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ppjwa.cn/Article/details/gtlmyotlob.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gtevgputey.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gtfheoluyj.html

PHP:  number_format(1234567);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiskpubbk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtrvlmuaus.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtjyisfbkt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gtcoxokxpi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cdnleiting.top/Article/details/gtlelgrmky.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pycfn.com/Article/details/gtehlikzbr.html

C#:   1234567.ToString("N0")
来源：http://dali.zhiwuduotai.top/Article/details/gtjdroqeam.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gtnjwkzmfu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gtdhdmjyhp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xinyue.icu/Article/details/gtlccataep.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcjlomqrn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtfylahsqz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gtfdvjjqhy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtqdtcaapc.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtptxasuue.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlylqdgs.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gtakepismf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gtqtovzaju.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sysykeji.top/Article/details/gtclzvfejj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gteigbaopo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtiikqerdp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtgpwpapjq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtchgvagyl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sxryk.cn/Article/details/gtzdzotoex.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gtzxcxtlgd.html

[E19] 多行文本按行拆分
来源：http://dali.snrcjt.cn/Article/details/gtnroyxwyu.html

Py:   s.splitlines()
来源：http://dali.cqqwz.cn/Article/details/gtkbgbhcqi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtgeybahjm.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gtpwnmopad.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwksansje.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gtyloxzyzw.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gthurizpcc.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gtywrijqnc.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gtyeobeimu.html

[E20] 判断字符串是否为空
来源：http://dali.andypj.xyz/Article/details/gtgiuxfbmo.html

Py:   if not s:
来源：http://dali.snrcjt.cn/Article/details/gtrdtguyje.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gtgkmqfvlb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtssgrcfgw.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gtrqaapwyr.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gttznsbrxp.html


<!-- 参考信息 -->