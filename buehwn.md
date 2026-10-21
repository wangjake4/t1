代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtfdcsywew.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtcqjnhppt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtucrmxslz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.bjfxy.top/Article/details/gthsvwtrhx.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gtnhoxzxzd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtjrpkhfoo.html

PHP:  array_unique($arr);
来源：http://dali.fengsongda.top/Article/details/gtikrpgurr.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtuucuspiv.html

TS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gttdfwnrst.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gtniflmapy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gtuoupthyy.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gttnszpibj.html

C#:   list.Distinct().ToList()
来源：http://dali.tian-w.cn/Article/details/gtshlwjpbx.html

[D16] 求和与平均值
来源：http://dali.c1oappe.top/Article/details/gtidgjlloq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gtqpmnneun.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtskuhsozt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtpwylfsql.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtqgvouvxz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gtkjmttuek.html

Go:   // 手写循环累加
来源：http://dali.jianghu66.top/Article/details/gtxxdfknev.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nwbrower.top/Article/details/gtcuzsyhdf.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqvuxmns.html

[D17] 最大值与最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgsboqxe.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gtdpjgjvue.html

PHP:  max($arr);  min($arr);
来源：http://dali.ehwqpu.com/Article/details/gtrwoheegq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhoulong.xyz/Article/details/gtgzeghfvd.html

TS:   Math.max(...arr);
来源：http://dali.tanke756.top/Article/details/gthdivzadx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.smart0.xyz/Article/details/gtgbxdglti.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sxryk.cn/Article/details/gtjomedbuw.html

Ruby: arr.max;  arr.min
来源：http://dali.dashuyun.cn/Article/details/gtxaczpxdx.html

C#:   list.Max();  list.Min()
来源：http://dali.jlsjyb.cn/Article/details/gtpjyokgua.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gtjxjmlrtx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gtsfzuhyab.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzirtuknv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yanxiufei.cn/Article/details/gtadderbvx.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gtraztyrtv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtxkeoolqm.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gtslkjkuku.html

Ruby: nested.flatten
来源：http://dali.yonumen.top/Article/details/gtxocdpxbj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmucheziz.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gtcejgtqem.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fengsongda.top/Article/details/gtojdwqdgi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuanzx.com/Article/details/gtyctfjwlb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cucudq.cn/Article/details/gtpdnbpkxl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtgtzkfqbv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtirkcxkoc.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtbjhiqjhk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibhptjyy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtiuaypvtz.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gttkbvqtqn.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gtjlwkgeqv.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtvagphkfq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gtzjneqgec.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gtdtluqrbf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtrlkvfeia.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gtjqtnqsbp.html

Ruby: arr.tally
来源：http://dali.andypj.xyz/Article/details/gtjrabimkq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shzxlz.cn/Article/details/gthbesshzi.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gtfqrrhyfi.html

Py:   x in arr
来源：http://dali.chenzaomai.com/Article/details/gtugohfgll.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yongpay.top/Article/details/gtfnfnsrau.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtgvpwfkxq.html

TS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtzpwjocvd.html

Java: list.contains(x)
来源：http://dali.yj20258.top/Article/details/gtjcnndomq.html

Go:   slices.Contains(arr, x)
来源：http://dali.yongpay.top/Article/details/gttsiofddi.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gttymjewgi.html

C#:   list.Contains(x)
来源：http://dali.havefunace.top/Article/details/gtspcppaht.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gtifwcyegc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pycfn.com/Article/details/gtaexwxqtu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilmlsojt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zycfv.cn/Article/details/gtvdtgtiuu.html

TS:   [...arr];
来源：http://dali.zhongyouzk.top/Article/details/gtikcnjplx.html

Java: new ArrayList<>(list);
来源：http://dali.yueranfly.top/Article/details/gtjogdhfbe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xziqi.cn/Article/details/gtxbdnxgak.html

Ruby: arr.dup;  arr.clone
来源：http://dali.meibo888.top/Article/details/gtcqhrnzon.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gtyspqwfhn.html

[D23] reduce 累积计算
来源：http://dali.sxryk.cn/Article/details/gtdqkkzele.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hywenlv.cn/Article/details/gtgieklwjw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrrrdqlg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtqspxrbit.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtosylblpt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gthsgbbgdh.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtxwmgwwed.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tian-w.cn/Article/details/gtoorokknd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258.top/Article/details/gtwvmlmlvi.html

[D24] 字典 / Map 基本操作
来源：http://dali.9152youxi.cn/Article/details/gtezbnwnxg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmbiocuy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gtkaeukyza.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gtlhxnscot.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gtbmfyzmaz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gtojazfdbc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sufxvd.cn/Article/details/gtsdlosqdq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuanzx.com/Article/details/gtlsjmszcu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pycfn.com/Article/details/gtexyeoocb.html

[D25] Set 集合去重与交并差
来源：http://dali.tanke756.top/Article/details/gtslckruor.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyvvlbes.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yanxiufei.cn/Article/details/gtcorbqsie.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aizwys.cn/Article/details/gtwxoanorm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.vqdsnc.cn/Article/details/gtecvctatd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.c1oappe.top/Article/details/gtbmkirqvg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.316326.xyz/Article/details/gtsguujqxl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gtkllmtbqz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtzidwjrni.html

[D26] 数组转字符串
来源：http://dali.hysaishi.cn/Article/details/gtufvlvikk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtffueedhb.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyccvuqvs.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtbwjnwaav.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtachlcwpp.html

Java: String.join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gtpwfxuxtq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jlsjyb.cn/Article/details/gtfpvvqqmz.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtvbonzzoj.html

C#:   string.Join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gtdpatxdwe.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdfoubafc.html

E. 字符串处理
来源：http://dali.chenjidiqi.icu/Article/details/gtfxvvqtjc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttwfixtci.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtwpcrkzog.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnvoeamh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gtjzftydsq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtueqsosdh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtrvaxzvqz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gthmpsxhcz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtahwiilhv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.snrcjt.cn/Article/details/gtyrmudslp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtxzposayt.html

[E02] 重复字符串
来源：http://dali.yj202588.top/Article/details/gthqsjlmxv.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gtsbxplthk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnriwjsqy.html

JS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteifrjhky.html

TS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtylkdqujc.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtsgzncuqo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aizwys.cn/Article/details/gtalgaekaa.html

Ruby: "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gtslykdxkh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hysaishi.cn/Article/details/gtgglvyrzr.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtctmvycgt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgufenzy.top/Article/details/gtudmjwybg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtpkdhwgcp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtppowbdst.html

TS:   s.slice(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gticdehycq.html

Java: s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtmkwhpsgb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuxming.cn/Article/details/gtrywfuppk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yongpay.top/Article/details/gtzalsvvxo.html

C#:   s.Substring(1, 3)
来源：http://dali.316326.xyz/Article/details/gtewdkliqp.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gtdlrkyeby.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttuesckhs.html

PHP:  strpos($s, "x");
来源：http://dali.iojbl.cn/Article/details/gtodkqgpft.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdhnywgi.html

TS:   s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gteapzpica.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtwxrvgxov.html

Go:   strings.Index(s, "x")
来源：http://dali.snrcjt.cn/Article/details/gtyakdptrg.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtlmjuccrb.html

C#:   s.IndexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtsrxdijco.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gtkgbhfefx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangdashe.top/Article/details/gtevjfzauz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gtpvycxhzz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqltrsijh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xylfe.cn/Article/details/gtamvrthil.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtnhfdredr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gtxkdebzar.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dianchejie.cn/Article/details/gtieyztncv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtsruwpfpe.html

[E06] 替换子串
来源：http://dali.cheryme.top/Article/details/gtpxogfwpe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gtcmfzblhu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gtawbzotih.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtsfpfvpot.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtnxyfmdpo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdoyfkuqp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gtzymlxwlv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gtkfesnupb.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gtszdstdmr.html

[E07] 按分隔符拆分
来源：http://dali.jiagoushi.top/Article/details/gtggjkitic.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jiagoushi.top/Article/details/gtlfrowvnz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.andypj.xyz/Article/details/gtibjicgmm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gtkvuozrxa.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gthqlhjutu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxinkj.top/Article/details/gtyexkqlmk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.meibo888.top/Article/details/gtcqhyoxjl.html

Ruby: s.split(",");  s.split
来源：http://dali.gaohongyu789.top/Article/details/gtvdfcmkkk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gtruaitowa.html

[E08] 数组按分隔符合并
来源：http://dali.ivvv.top/Article/details/gtliyodvpv.html

Py:   ",".join(items)
来源：http://dali.birdmap.top/Article/details/gtwkrciill.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gtdjxhuxqj.html

JS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtewnlmgjs.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtulymfxzr.html

Java: String.join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtdhrqxuxh.html

Go:   strings.Join(items, ",")
来源：http://dali.nwbrower.top/Article/details/gtuxslrxpd.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtuhtyyodc.html

C#:   string.Join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtrrgshiaq.html

[E09] 去除所有空白字符
来源：http://dali.chenzaomai.com/Article/details/gtxhlqjgcj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guowangkeji.top/Article/details/gtsjnmgaxx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nwbrower.top/Article/details/gthztgfian.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtmygwuhtq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gtydjrcwpe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gtvzayedco.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gtuvyodgsw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gteyqznsqx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczbozyai.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gtwjtqllal.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sweek.top/Article/details/gtyukyndhl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cheryme.top/Article/details/gtxxexspvf.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtqirewqaf.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtgihbiebl.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtptbwjsku.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtqgpqliyr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gthrencoja.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gtsugvqnzn.html

[E11] 反转字符串
来源：http://dali.cheryme.top/Article/details/gtgrlvzdal.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gtnkymlwpl.html

PHP:  strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gthalfyvde.html

JS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtfiwcbaat.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtlrmrbavm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnqzz.top/Article/details/gtemalvgij.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258.top/Article/details/gtnwduhqus.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtwivhxdgv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtyyvcorjz.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gtatkibbae.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtajnuedtv.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtvuywgwue.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtnpvkwari.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtqlcqrhzo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yanxiufei.cn/Article/details/gtaxeeqpht.html

Go:   strings.Count(s, "a")
来源：http://dali.cucudq.cn/Article/details/gtujvhxsys.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtiymlhrks.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gtfycruahi.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gtsypmocwp.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gtfrahyzgt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hysaishi.cn/Article/details/gtviyttjtc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtofmwtjko.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtjldpueki.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwekldzif.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fzhhl.top/Article/details/gtyekwgymm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gtnaarbxld.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yvedp.cn/Article/details/gthvkbtxzl.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gtorcfwxwp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxinkj.top/Article/details/gtqexltkmb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shuidangran.top/Article/details/gtjrtqrloq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jiagoushi.top/Article/details/gtqxxcdfzg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtggaprnqk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtmvaxdybu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gtnfsqiwto.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gtxniioyju.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gthpflilxg.html

[E15] HTML 转义 / 反转义
来源：http://dali.shangyingyoupin.top/Article/details/gtktoebljs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigufen.top/Article/details/gtbyrqjiqw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gtacqloiwk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gtyaxnwppg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gtjnqitwju.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gtnyyublux.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.iojbl.cn/Article/details/gtykwdgphv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gtwkgfljtd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gtwgjchkhg.html

[E16] 数字千分位
来源：http://dali.yj20258888.top/Article/details/gtdvgeztsd.html

Py:   f"{1234567:,}"
来源：http://dali.jyoumei.cn/Article/details/gtbknmcqvg.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gtfoykhjne.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtplzmdxyn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtxobnujfa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gtcodyyyga.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xylfe.cn/Article/details/gtrmtqlpfi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnigzfag.html

C#:   1234567.ToString("N0")
来源：http://dali.yj202588.top/Article/details/gtliiztvdt.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gtbkyvyxoo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gtrdarurlg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gtbeucylnz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtbqtvwghf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gttyyedefy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbakguipc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gttmlqfnem.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtlmytodtz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gtrgvwlrdq.html

[E18] 模板占位符替换
来源：http://dali.sxryk.cn/Article/details/gtudnynrvn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenlongwang.top/Article/details/gtwwrwvdxy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gtltduhmcw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gthkqmtqxw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtsmbkkcux.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtoxblazdz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtrchkhfto.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtzxwjmvyk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtkxsjokmj.html

[E19] 多行文本按行拆分
来源：http://dali.cqqwz.cn/Article/details/gtofpbcdnr.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gtfzvamhjv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtoowkltsr.html

JS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gtnydlwqvc.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvfjxwls.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gtyeximtpp.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gtehsawqqp.html

Ruby: s.lines
来源：http://dali.zhongyouzk.top/Article/details/gtpeqihjfb.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtbifrfoip.html

[E20] 判断字符串是否为空
来源：http://dali.dashuyun.cn/Article/details/gtfyvdryae.html

Py:   if not s:
来源：http://dali.cqqwz.cn/Article/details/gtergpcmfy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gtdhbxbuox.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxgmueay.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdubzyvbb.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtfdnovjyr.html

Go:   if s == "" {}
来源：http://dali.bjfxy.top/Article/details/gtahdywuoc.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gtxddymkxg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtkswcwrwa.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupnijhvf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.iojbl.cn/Article/details/gtvqcgbrjf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtlwnxvuwf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtvtazkvzf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtpbkqjiac.html


<!-- 参考信息 -->