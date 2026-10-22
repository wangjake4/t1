代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtxnqkiwds.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yueranfly.top/Article/details/gtnkoxyupq.html

JS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gtsprdqsct.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtjhfjwgkk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gtpxjhixgm.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gtiwbvkgfh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sysykeji.top/Article/details/gthdrenybk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhboejgo.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gtwgxnwuzn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzjbsbee.html

PHP:  array_unique($arr);
来源：http://dali.smart0.xyz/Article/details/gtctihlurn.html

JS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gtqhugqwwg.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtgmlkbtzk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhznxvzw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gtyojyflrh.html

Ruby: arr.uniq
来源：http://dali.kuanghao11.cn/Article/details/gtkxekddtx.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258888.top/Article/details/gtuajmjyak.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gtbhyjvhlc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gtkhcjdrer.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gthnwulefv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtymwexiyv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtahbvmnpk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.mhx1999.top/Article/details/gttnwfazgt.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtxhusqmrh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtcmyibbok.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtviecwxaj.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gtxritwdll.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtzkpmnvjt.html

PHP:  max($arr);  min($arr);
来源：http://dali.aizwys.cn/Article/details/gtxyyspved.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.kuanghao11.cn/Article/details/gtloxvhyhr.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gthhqyqlyw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtwrvrvhqz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhengqikj.top/Article/details/gtwcmxamkr.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gtoqdndmel.html

C#:   list.Max();  list.Min()
来源：http://dali.xuetiantiany.cn/Article/details/gtdcwjmodt.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gtzxrqggmn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gtamjivxgm.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gtwjvrkskb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuanzhike.top/Article/details/gtfbjzipth.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gtiqmfhhzk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gtchvqdcbd.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gtyqkjyobt.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gtyxsbtyca.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuxming.cn/Article/details/gtxqwuumgy.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gtxuemnpxj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gtkmuuhezk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gtzzayskil.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gtphiibgkd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gtexnmnlac.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gzhubu.top/Article/details/gtsbcruiho.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gtnyhmfqkr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gtegkzolfn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojtbzhip.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtdmitweiz.html

Py:   Counter(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtgkwztgsl.html

PHP:  array_count_values($arr);
来源：http://dali.snrcjt.cn/Article/details/gtzroqbeiu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtyiwvvxgq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gtnmomfhxx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhoulong.xyz/Article/details/gtlxsbpksb.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gtcaqnwebv.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gtamkemqyw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gtdicroojq.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gteugstlhg.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gtjcrkhkci.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtsfqdpswg.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtamwpjtpe.html

TS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtxiunactc.html

Java: list.contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnykuxmot.html

Go:   slices.Contains(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtydlxajvb.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gteloejebu.html

C#:   list.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gthcinhkvm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ppjwa.cn/Article/details/gtdopbqued.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gthupcsidn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gtxfuqjznp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xylfe.cn/Article/details/gtalcwedgk.html

TS:   [...arr];
来源：http://dali.tianlin.xyz/Article/details/gtdobmivmg.html

Java: new ArrayList<>(list);
来源：http://dali.chenzaomai.com/Article/details/gtxeojytdb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tianlin.xyz/Article/details/gtauuagunf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gtvpoopfcd.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gtragwfkdq.html

[D23] reduce 累积计算
来源：http://dali.sxryk.cn/Article/details/gtyplmcilf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pycfn.com/Article/details/gtbuufsaie.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtjxuvdfiz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtguyvgpow.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtffshxyii.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gtcugktrdv.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtkxcvxshp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jyoumei.cn/Article/details/gtsscsgsjk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gthynlszbz.html

[D24] 字典 / Map 基本操作
来源：http://dali.kuanghao11.cn/Article/details/gtovkjmvnt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hammf.cn/Article/details/gtjcyjufcu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtmwacykld.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gtkywvlsap.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtdxayfowl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gtyqbggpxa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daria6918.cn/Article/details/gtgngzkoms.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ehwqpu.com/Article/details/gtzxspfsum.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gtvnlkcwwb.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gtoqrcaewg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsmjcjie.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guannengcc.top/Article/details/gtjctnnwqn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gtfjidkpkd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gtqjrlktpl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gtumjaavlk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zycfv.cn/Article/details/gtjthlhcat.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gtswthgzol.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtmobvstfc.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gtxrzjqklg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gtxhhhfzln.html

PHP:  implode(", ", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtmkjawmrb.html

JS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtzabxhlrd.html

TS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtvmswledv.html

Java: String.join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gtnhtrenft.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tianlin.xyz/Article/details/gtlgkxmdnx.html

Ruby: arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gttxxgdfqs.html

C#:   string.Join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gtlnyevdqo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtozomvgqt.html

E. 字符串处理
来源：http://dali.mhx1999.top/Article/details/gtixodallq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtztthnfmg.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtxattigln.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gtiscgynbe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gtkczrxfms.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtsakpyvzq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflarxjun.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gtcfshcinc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbydfllgj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gtzzdxekix.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ivvv.top/Article/details/gtvjrhonbg.html

[E02] 重复字符串
来源：http://dali.jiagoushi.top/Article/details/gtbukfpodu.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtverlnwkk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gthikmfjhb.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtywpargxc.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtoroiauok.html

Java: "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtcmdnxukg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtqcmecxkn.html

Ruby: "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gtfxeiuwip.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gtqoltbagn.html

[E03] 截取子串
来源：http://dali.hnqzz.top/Article/details/gtwlohuggb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gtrnlorgkj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtwugdprsy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gttaytbcyc.html

TS:   s.slice(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttttuacuw.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtdaggeqoi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aibaodan.cn/Article/details/gthwuiayyu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxuanxn.top/Article/details/gtwjkoefqg.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gttnsyxrof.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gtbzchcpjc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtxumobouc.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gtdhfutiia.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jiagoushi.top/Article/details/gtdlwjbzyz.html

TS:   s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtqpofxksz.html

Java: s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gterhblcjq.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gtydvhsydd.html

Ruby: s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtysnffoju.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtrayhcwyv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbogepeze.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gtuwclkcyx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jyoumei.cn/Article/details/gtcijmcjwr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gtsuupznna.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gtncbypsgy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gtbnslyzux.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.bjfxy.top/Article/details/gtmmdslkou.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jiagoushi.top/Article/details/gtrfrdwtpc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtzpbgdfab.html

[E06] 替换子串
来源：http://dali.gzhubu.top/Article/details/gtdzbgtlwh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtgaefqgts.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.svipenyu.cn/Article/details/gtxuikozsn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtbfekajwg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuampskuz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtmxrbmsva.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtgaorcpfk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtxyqtoniz.html

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtmghbdzii.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gtkdafbqyd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.snrcjt.cn/Article/details/gtwwiqrean.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtxlooyjkj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gtrkldguez.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gtpjvsnxer.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gtstjzfdjw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gthlrsgikm.html

Ruby: s.split(",");  s.split
来源：http://dali.vqdsnc.cn/Article/details/gtdhvbupgy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqahvdlbz.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gtadbkxvwi.html

Py:   ",".join(items)
来源：http://dali.shzxlz.cn/Article/details/gtthxizsej.html

PHP:  implode(",", $items);
来源：http://dali.feifeiyinyue.top/Article/details/gtlhwhpxiu.html

JS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxckesghm.html

TS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtngztenqy.html

Java: String.join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtypxxapik.html

Go:   strings.Join(items, ",")
来源：http://dali.andypj.xyz/Article/details/gtappmueew.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtcpapdgdg.html

C#:   string.Join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtueomlwbk.html

[E09] 去除所有空白字符
来源：http://dali.hnxiangtu.top/Article/details/gtnrnnsdgl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gtehdlxrew.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.meibo888.top/Article/details/gteckmobkp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtemtwqujm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtvphaherf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gtrwhilala.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ivvv.top/Article/details/gteolnismh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jianghu66.top/Article/details/gtklywzkne.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gtcztwtmzy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhongyouzk.top/Article/details/gtzeaklqbv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gtfegxqfxf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangshuangyany.cn/Article/details/gtlchuhyma.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtrltbpmhj.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtogbzikow.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gttsgwictj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtulrrupui.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtrimbveft.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gtkfpyaejv.html

[E11] 反转字符串
来源：http://dali.tanke756.top/Article/details/gtthqqnmnp.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtxqkjruyl.html

PHP:  strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtvfjebxkh.html

JS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtjoxyfnni.html

TS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtcdmtwdol.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.bjfxy.top/Article/details/gtnetmtwat.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gtiisowdie.html

Ruby: s.reverse
来源：http://dali.andypj.xyz/Article/details/gtzzpzgroz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gtfpqcpjea.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtdfplfdsu.html

Py:   s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtlkakditu.html

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gtshjkppos.html

JS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gtqbwpjplv.html

TS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtwxlrwotk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xylfe.cn/Article/details/gtciurheqn.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gtzcfwdxrm.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtscqdbzpt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tanke756.top/Article/details/gtsdmevtcg.html

[E13] 逐字符遍历
来源：http://dali.andypj.xyz/Article/details/gttjytjjfc.html

Py:   for ch in s: print(ch)
来源：http://dali.yongpay.top/Article/details/gtxtyyutux.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zycfv.cn/Article/details/gtdxegbxrd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtuxgcfmho.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtjaznnczh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvmudsul.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gtmgwfmooy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cashguo.top/Article/details/gtybodpuug.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hammf.cn/Article/details/gtpsbxaqqx.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gtanoxkfdu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtaihkgtms.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gtwrcemuly.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gtzzddsner.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gtykiiihsp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtslywjqie.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gtezdpraiz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gthbizfyvh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtqlsvyuqs.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuanzx.com/Article/details/gteonigkga.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzehnbogx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtpfarrzbu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ydzc1.top/Article/details/gtxvviqezl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gtunvflttf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jianghu66.top/Article/details/gtauhwusny.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gtojmpmusu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gtndireyov.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtrvtpshfl.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gtdhhjpqez.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtlcipcubu.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gtbarigkme.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtcsysqivc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtdtbmnfgy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nwbrower.top/Article/details/gtjflflpiy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gtchidozyn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavpgddmb.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gtpfwcpvcx.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gtkoinqgqa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gturhkntzc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gtngetrgag.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gtivdxlhjg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtbltkvtws.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gtlkluaria.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gtqcfrkkhi.html

Ruby: s.capitalize
来源：http://dali.9152youxi.cn/Article/details/gtyxaakfqm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yangfankeji.com/Article/details/gtfquwltts.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gtcdcamhxo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yongpay.top/Article/details/gthqrratcy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gteuhslyeo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtswtlwwnt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gttkwhjemt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gttpsqvjie.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gtfdzpghsd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hywenlv.cn/Article/details/gtyumtbyxu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcmnteds.html

[E19] 多行文本按行拆分
来源：http://dali.bjfxy.top/Article/details/gttjsvxsnl.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtluuoavoz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gticpbwegb.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtdkeqsfpm.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gtrozcyefs.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gtnqixdpja.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtwfrxjfcj.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gtfdaftnfs.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtvbzhwuig.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyghkvcb.html

Py:   if not s:
来源：http://dali.zhengqikj.top/Article/details/gtzqvoghls.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gtndxuunel.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.quarkkingdee.top/Article/details/gtbscrssip.html

TS:   if (s === "") {}
来源：http://dali.xylfe.cn/Article/details/gtofazlwhy.html

Java: if (s.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtzajuhthx.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gtbnqndleq.html

Ruby: if s.empty?
来源：http://dali.c1oappe.top/Article/details/gtwkstilnl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gtkoxdolab.html

[E21] 超长截断加省略号
来源：http://dali.meibo888.top/Article/details/gthzvxppel.html


<!-- 参考信息 -->