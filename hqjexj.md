代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtvbpkokpn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtkrhwjbzm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gtavlfzfzx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gzhubu.top/Article/details/gtcskhrujc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gtvmilwdvc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yongpay.top/Article/details/gtlgsstwlr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gtwuqeorxb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.meibo888.top/Article/details/gtadrgylcv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gtnzmrvovv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.smart0.xyz/Article/details/gtqjqiwrpd.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gtazgdtluc.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtindvrfex.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xylfe.cn/Article/details/gtotrnizbu.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gteekepxwz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtkwzaidjh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gtztdmbsfs.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gtdibttiyw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gtmbonoxxi.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gtdkgijvlt.html

JS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gtcpdbzlxm.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtuybvdncs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gtyxihaxct.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gzhubu.top/Article/details/gtrhsibnhe.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gtweunjeaz.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gtrymqbgex.html

[D16] 求和与平均值
来源：http://dali.fzhhl.top/Article/details/gtdrgcpfjy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtiyqvyypk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtegspogyl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtrvsjsyjl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtusbpdqlg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aibaodan.cn/Article/details/gtypnszqrl.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gtlectjmyc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gtmbbuxyxp.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gthtknbwag.html

[D17] 最大值与最小值
来源：http://dali.316326.xyz/Article/details/gttxdsyssv.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtsuurdjsp.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj202588.top/Article/details/gtkvmjypqu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gtltnsutmh.html

TS:   Math.max(...arr);
来源：http://dali.haohaochexian.top/Article/details/gtkwqsvsxf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gtnaywwlce.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.svipenyu.cn/Article/details/gtdcbkluyb.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gtxippkjde.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gtyuiuuuas.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gtbuzvfwhx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gtmtcktukt.html

PHP:  array_merge(...$nested);
来源：http://dali.tian-w.cn/Article/details/gtdbxgzwwr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gtntqfaoys.html

TS:   nested.flat();
来源：http://dali.chenlongwang.top/Article/details/gtyrcpuotr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gtbnfkqcul.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gtxbpxspwf.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gtqcwxhoyu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuanzx.com/Article/details/gtxzcknpuz.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gtmagvgvxz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gzhubu.top/Article/details/gtubjjblqu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ivvv.top/Article/details/gtyqbpecyb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hongshengwenyu.top/Article/details/gtotdotnmt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gtbqdhagad.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gtahfuoeza.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigfzy.top/Article/details/gtajzgkkfb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aizwys.cn/Article/details/gtosvaigsy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gtobilmsep.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gtfkzkzdto.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gtbeuntwik.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtlrugwhzl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gttwmzklwf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkscrbflo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedexwwxy.html

Go:   // 手写 map[T]int
来源：http://dali.bjfxy.top/Article/details/gtjtclxmae.html

Ruby: arr.tally
来源：http://dali.wangdashe.top/Article/details/gtbedxqgkt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hysaishi.cn/Article/details/gtqxvgluyx.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gtesbidjsp.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtbejybrss.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ybcxt.top/Article/details/gtxuggdpmk.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcivdvbyr.html

TS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gttwqgnguq.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtyoqhylru.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtgnfxzojy.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtbllglbxt.html

C#:   list.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtsrqngcfb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.snrcjt.cn/Article/details/gtgkjphtfz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gtleliujvs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gtbuzziolv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258888.top/Article/details/gtyngklhsd.html

TS:   [...arr];
来源：http://dali.cqqwz.cn/Article/details/gtsjihdwcm.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gtmzaslwvs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gtupluggev.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cdnleiting.top/Article/details/gtzxxhovwy.html

C#:   new List<int>(list);
来源：http://dali.ehwqpu.com/Article/details/gtfcekosga.html

[D23] reduce 累积计算
来源：http://dali.xziqi.cn/Article/details/gtznbpojaj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylglhjpt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtkpjfybdb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gthaarmlab.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gtxiuxtdcr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuanzx.com/Article/details/gtzdslzvbr.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gtrgtxglno.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gtjckwilvk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gtofgdrcpn.html

[D24] 字典 / Map 基本操作
来源：http://dali.ydzc1.top/Article/details/gtcuryxgax.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.9152youxi.cn/Article/details/gtdayuumgg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gtfexmvuxa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ehwqpu.com/Article/details/gtbkisypqa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtbpihqafi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hywenlv.cn/Article/details/gtadpayrut.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gtsbiajjgt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gtmycjidje.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yueranfly.top/Article/details/gtrainpuqd.html

[D25] Set 集合去重与交并差
来源：http://dali.iojbl.cn/Article/details/gthztpmtgn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenlongwang.top/Article/details/gtjxxzbrss.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gtttopghgi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbskzdeu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yvedp.cn/Article/details/gtzrquiwya.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtjmmwuqcx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnxiangtu.top/Article/details/gtjnmkhkjo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjqmhocl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gtvnelwvpr.html

[D26] 数组转字符串
来源：http://dali.fengsongda.top/Article/details/gtbntzvbgn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nwbrower.top/Article/details/gtuquovkbt.html

PHP:  implode(", ", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnnqmmnh.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtlzmhhrqy.html

TS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtsdwcdnqb.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gtlwcswkuw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gtppifdsxc.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gturbssfke.html

C#:   string.Join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtokastrmx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtftunhnky.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccelszkv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtawxqmrwv.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gttuhndqvm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigfzy.top/Article/details/gtxdyfudlm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gtkxfdivxh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gttjjbzaop.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtuiplocva.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigfzy.top/Article/details/gtibsutbay.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jyoumei.cn/Article/details/gtqcokpmjf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gtukedewah.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gteodxxbue.html

[E02] 重复字符串
来源：http://dali.tianlin.xyz/Article/details/gtwmyticrx.html

Py:   "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtpnrfvqmt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jiagoushi.top/Article/details/gteudhvopa.html

JS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtdwnxmwwj.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtfhmviqpu.html

Java: "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtxxapfesd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xylfe.cn/Article/details/gtztulzhrw.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gthztsuptf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiecqkkbn.html

[E03] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gtlfzzqnyw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuxming.cn/Article/details/gtjnptleum.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gttedntfoa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtzgcuajtq.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gteuuntnuw.html

Java: s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gtkbwgrgts.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gttitddwii.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sxryk.cn/Article/details/gtqhlvrfnz.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gtfhemmjgd.html

[E04] 查找子串位置
来源：http://dali.gotoacloud.top/Article/details/gtjxwimlnk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtsglqfbat.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gtykrdsxdl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.9152youxi.cn/Article/details/gtnwrxzxid.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtcmqueupu.html

Java: s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gthrxialqd.html

Go:   strings.Index(s, "x")
来源：http://dali.mhx1999.top/Article/details/gtiypvtcci.html

Ruby: s.index("x")
来源：http://dali.cashguo.top/Article/details/gtqsjmajki.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gtdhgqcddj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.iojbl.cn/Article/details/gtxnpoosxj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gtlpggwtby.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gturmjskmq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtinguleph.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.redwolf501.top/Article/details/gtnfibeedi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtbmcnzwcv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.snrcjt.cn/Article/details/gttczcweaz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.bjfxy.top/Article/details/gtxlvualwb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtvkxmxznp.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gtkeysfgwt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gttzoddhtr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hysaishi.cn/Article/details/gtdesnwtcz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtiezvtybg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtdoqarowl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gthrpadrpx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtkahywmfp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaqvljom.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtbptcmocn.html

[E07] 按分隔符拆分
来源：http://dali.sxryk.cn/Article/details/gtgupblmbo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gtytajrocr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtdjjgjcvd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gtzudeleoo.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gtfkqqorht.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pengpengdd.cyou/Article/details/gtjqwnzgia.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gzhubu.top/Article/details/gtgjodwayb.html

Ruby: s.split(",");  s.split
来源：http://dali.feifeiyinyue.top/Article/details/gtwqmjkobi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pengpengdd.cyou/Article/details/gtvzhnhvmo.html

[E08] 数组按分隔符合并
来源：http://dali.wangdashe.top/Article/details/gtwjhxuyhy.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gtbbsknjrn.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gtocmeozpo.html

JS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtgyoysmvi.html

TS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfjeomxq.html

Java: String.join(",", items)
来源：http://dali.cashguo.top/Article/details/gtaovmuwlj.html

Go:   strings.Join(items, ",")
来源：http://dali.haohaochexian.top/Article/details/gtkjwtfxcx.html

Ruby: items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtekgrzqcm.html

C#:   string.Join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtpwbjwrqr.html

[E09] 去除所有空白字符
来源：http://dali.shzxlz.cn/Article/details/gtjqvqgmay.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangdashe.top/Article/details/gtuflupleg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtlkvizvij.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gthvdtbeny.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtosvbheqc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xinyue.icu/Article/details/gtvbjedolw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gtaiflgpgq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gtwjpkocgg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtjguroplj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gtqjofjjkr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtfjzyhhfx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtwohdkfzw.html

JS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtejuzysre.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gthxtcrzih.html

Java: String.format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtaolsilch.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtxcvqkxyq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtjnyncscl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gtdzayiqqr.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gtfuhncwmy.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtvhogwifl.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtnvemcdox.html

JS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtkdqmybja.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtfcejjqrk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gtekbpnxfx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gthnbxreht.html

Ruby: s.reverse
来源：http://dali.fzhhl.top/Article/details/gtuyyextzw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtkuwxxbqx.html

[E12] 统计某字符出现次数
来源：http://dali.bjfxy.top/Article/details/gtgcbycjhf.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvglavtid.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gtqlkobdiy.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gtzedmtvud.html

TS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtwbrpwyer.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gtqyfqavtb.html

Go:   strings.Count(s, "a")
来源：http://dali.ivvv.top/Article/details/gtidilqwzd.html

Ruby: s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtwvzqwzwq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gtzhioyerq.html

[E13] 逐字符遍历
来源：http://dali.hammf.cn/Article/details/gtfmmevyyu.html

Py:   for ch in s: print(ch)
来源：http://dali.jinghuilouyu.cn/Article/details/gtydvusstp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gtacxisdtk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtvmehdbmf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtzqrifyhk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gtaxuoqdpu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gtauzbnldm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gtkghtookl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtviztqmfr.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gtiofbrpru.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gttbgxrjam.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gtmqgkszjy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtmdgzvojw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gtdyjkvkqu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gthqnyavpr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gtjrbjgowr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gtudjrykki.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtajbeihhu.html

[E15] HTML 转义 / 反转义
来源：http://dali.vqdsnc.cn/Article/details/gtublofzvx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gtwzumijup.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gtcapfhdli.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.birdmap.top/Article/details/gtjlolzmyh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.birdmap.top/Article/details/gtbkpfjqhh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gtvmxkivid.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gtwxhkrwse.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtwyzujwxl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.316326.xyz/Article/details/gtpdzebpqi.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gtrcwksmny.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gtiyhjxsql.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gtcyymnlte.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtimcgadqy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtsogpyjzg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtphzeysmp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gtkjrtnlyr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtpqeronex.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gtzspebscd.html

[E17] 首字母大写
来源：http://dali.chenlongwang.top/Article/details/gtbzizxlvi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gtwptinmsm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gtpmutpuxn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtombqqwah.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtesbajskt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dashuyun.cn/Article/details/gtylcdajka.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtzgexenjg.html

Ruby: s.capitalize
来源：http://dali.jyoumei.cn/Article/details/gtxxpjgxbp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gtfjjpgfyl.html

[E18] 模板占位符替换
来源：http://dali.dashuyun.cn/Article/details/gtwziufdoo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dianchejie.cn/Article/details/gtaqgilwfk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gtbawtkiev.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtcntffilj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtupumpsuu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtgiyfhdxv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwczkzzhd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gtycwggoca.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hongshengwenyu.top/Article/details/gtvhtajosv.html

[E19] 多行文本按行拆分
来源：http://dali.shzxlz.cn/Article/details/gtrbysnvnx.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtstsunyxt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xinyue.icu/Article/details/gtfgezbvmb.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtxuheulyd.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtylskeqve.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gtoovients.html

Go:   strings.Split(s, "\n")
来源：http://dali.haohaochexian.top/Article/details/gtwbjsuezq.html

Ruby: s.lines
来源：http://dali.nanxuanxn.top/Article/details/gtolbiwtii.html

C#:   s.Split('\n')
来源：http://dali.smart0.xyz/Article/details/gtxsmoumbl.html

[E20] 判断字符串是否为空
来源：http://dali.9152youxi.cn/Article/details/gtjezxnhmm.html

Py:   if not s:
来源：http://dali.hfpthk.cn/Article/details/gthccpgjks.html


<!-- 参考信息 -->