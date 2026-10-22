代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ppjwa.cn/Article/details/gtzrxzjpuo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvmfcved.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtfybgsyit.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtnnndqgll.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtuqwjfmyx.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtcuwkneba.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtspebmaoy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gtcfdjqniq.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gtbsoumdqg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtojwetogl.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gtqocduvkv.html

JS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtutdvshxd.html

TS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtwuijrmtk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gtwagaluap.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuanzhike.top/Article/details/gtlenshgxp.html

Ruby: arr.uniq
来源：http://dali.sufxvd.cn/Article/details/gtvojyvzeq.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gtnwhorfed.html

[D16] 求和与平均值
来源：http://dali.hywenlv.cn/Article/details/gthcnexwcu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.andypj.xyz/Article/details/gtkioshidt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnqzz.top/Article/details/gtjxelkcjj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmunshnmz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gthygmhvcy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fengsongda.top/Article/details/gtudknvuga.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gtenkhdqzg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhongyouzk.top/Article/details/gtpuzwlthl.html

C#:   list.Sum();  list.Average()
来源：http://dali.ydzc1.top/Article/details/gtaxsdzfoi.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gtpbnitcgt.html

Py:   max(arr);  min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtohalhyba.html

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gtfekvmvyf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.andypj.xyz/Article/details/gtvedbcsxj.html

TS:   Math.max(...arr);
来源：http://dali.zhongyouzk.top/Article/details/gtgnxwuwbj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gthpeecgwi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gtqgmebbcu.html

Ruby: arr.max;  arr.min
来源：http://dali.jianghu66.top/Article/details/gtfvpvyyls.html

C#:   list.Max();  list.Min()
来源：http://dali.svipenyu.cn/Article/details/gtfdzchzjd.html

[D18] 扁平化嵌套数组
来源：http://dali.yvedp.cn/Article/details/gttqzybgle.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yonumen.top/Article/details/gtawuxnlcg.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gtsuzhkxmf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gtcyqdsynk.html

TS:   nested.flat();
来源：http://dali.c1oappe.top/Article/details/gtpxeqbmpu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtbgvdxxcn.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gtlmhxlohc.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gtelfwslvs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtozombcif.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gtwlkmrqzk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yangfankeji.com/Article/details/gtwnkxkxxe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gtohixdgsd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsfkmkzc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gttknuwphg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnnwciar.html

Go:   // 手写 map[string][]T
来源：http://dali.fzhhl.top/Article/details/gtvvkwojhx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gttbecuerj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gtwonxkixh.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gtczsutvwu.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gtpkqirwyw.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gtltgkofuy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtddghwahu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtdjvnpzzn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gtikpybxhd.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gtpseeegxh.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gtkxoarnbc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigfzy.top/Article/details/gtnkyocoes.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gtslseganb.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gtsdopgovc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gtcmjrhpgw.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gttotbauta.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtfulyoggg.html

Java: list.contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezerjsvl.html

Go:   slices.Contains(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtweozjioi.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gtfcxyqapo.html

C#:   list.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtugqnzcwu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.meibo888.top/Article/details/gtmwrcwptf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtudprtuym.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gttaddbwyh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtbrmocchp.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gtosrzmrep.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtejvoqprk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tian-w.cn/Article/details/gtyewohriv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gtkkiskqso.html

C#:   new List<int>(list);
来源：http://dali.jlsjyb.cn/Article/details/gtjatojges.html

[D23] reduce 累积计算
来源：http://dali.jqgfzy.top/Article/details/gtejgcgqng.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtqgkfjwyx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtwwcasiph.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtkpxyvorf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtpzuxvirx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuxming.cn/Article/details/gtjzucatlh.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtbcystdzk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhoulong.xyz/Article/details/gturvcqcsr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gtzyadplsl.html

[D24] 字典 / Map 基本操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqazxavys.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gtsnonqdly.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jianghu66.top/Article/details/gtgnujsmxm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgfzy.top/Article/details/gtdlvcoqgh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtlchvhsvd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtvkdtuhvg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.redwolf501.top/Article/details/gtvuiwieqf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gtaonnmpzk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pengpengdd.cyou/Article/details/gtoicrsjud.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gtgvzktroi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.vqdsnc.cn/Article/details/gtffdfgvqn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gtcfamhawt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tanke756.top/Article/details/gtfcxdsmvb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.bjfxy.top/Article/details/gttzreamww.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gtbskfnxrk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtsivasjts.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gotoacloud.top/Article/details/gtaxjhkikh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogdqlnrk.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gtwgxnuwoh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtawfptqeg.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gtnpprrkfp.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtnlcqzjov.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtvnpbwpgl.html

Java: String.join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtzfhckmgx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guowangkeji.top/Article/details/gtwzcshcpt.html

Ruby: arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtbsnkgtdm.html

C#:   string.Join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gtvvbjrokl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtohkqwqyt.html

E. 字符串处理
来源：http://dali.pengpengdd.cyou/Article/details/gtpxwjcxia.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfmqvznhl.html

[E01] 拼接字符串
来源：http://dali.birdmap.top/Article/details/gtivsdxeao.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yueranfly.top/Article/details/gtbmupnkpj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gteccakbky.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtiuoxcitn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtcviyypsi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gtxdidflmb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtoymzqrer.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gtqpjzqnag.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtixfpuoyt.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtbvmrrapa.html

Py:   "ab" * 3
来源：http://dali.hammf.cn/Article/details/gtnstcsdkz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxinkj.top/Article/details/gtmvskvpnt.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtscfkvjai.html

TS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtdlgfblyc.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtcyjzkghg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gtqlvyvcje.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtdlgeeran.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xinyue.icu/Article/details/gtdtnbtewd.html

[E03] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gtxfqkxsyj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sxryk.cn/Article/details/gtmfitforp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtxazwyept.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtbdqfzgzy.html

TS:   s.slice(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtzjzriyaj.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtwpssfior.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtvethbxhw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yangfankeji.com/Article/details/gteufdgoep.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gthtbzkuvp.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gtyqtfzlly.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtzodrqish.html

PHP:  strpos($s, "x");
来源：http://dali.aizwys.cn/Article/details/gtnayvwjml.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gtqlztogjz.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtqgyaizll.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gtocowfitc.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gtdlywbvci.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtlytuyzhh.html

C#:   s.IndexOf("x")
来源：http://dali.316326.xyz/Article/details/gtntkywytl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuanzx.com/Article/details/gtjehvnmwy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guannengcc.top/Article/details/gtthxqxqly.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xylfe.cn/Article/details/gtugndenqr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtwdeqhgkw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gtkpsvpcgp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtipxqtwbz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gtvaquxdud.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xinyue.icu/Article/details/gtwbjmsrvq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtdpwxnsii.html

[E06] 替换子串
来源：http://dali.9152youxi.cn/Article/details/gthdhyzxdq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtrdrxsevw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yangfankeji.com/Article/details/gtlgoejhlu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtnolblqgm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtbcphtzdr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtbvjwwabn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtevyoxmim.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pycfn.com/Article/details/gtozwsqvqs.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcmzgjxd.html

[E07] 按分隔符拆分
来源：http://dali.tianlin.xyz/Article/details/gtlzkrajwa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.iojbl.cn/Article/details/gtroovwjns.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.316326.xyz/Article/details/gtmhtmwfkb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gtbjeqyeod.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gtevztkxsq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gtmqebrqak.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gzhubu.top/Article/details/gtbacyowdt.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258.top/Article/details/gtybdwiztz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daria6918.cn/Article/details/gturdllwjo.html

[E08] 数组按分隔符合并
来源：http://dali.fengsongda.top/Article/details/gtkssxyuvj.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtxhlztnjg.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gtonlemwkv.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtpdzophqu.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtqrnphtht.html

Java: String.join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtbaxmtquq.html

Go:   strings.Join(items, ",")
来源：http://dali.yueranfly.top/Article/details/gtunhvsjvt.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtqpcoqwtk.html

C#:   string.Join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gtqccyxyif.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtpfpzuqhr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.quarkkingdee.top/Article/details/gtquiyyowe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gtweaafhdu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gtjgctfcoy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gtqcjyxrae.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtplwjabhk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnqzz.top/Article/details/gtqahtpfsb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ivvv.top/Article/details/gtlfgowsfk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtyaziwlcl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gtopsijmvr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tanke756.top/Article/details/gtsuzlxeaa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gtvtarcluw.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtpvysbigc.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtuajpxead.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtrulwmgzz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtbvovfotk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gthebeeljh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gtlfvwdeek.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gtazydzqnd.html

Py:   s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gtrylihhuc.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtalrilelq.html

JS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gthhqefmpn.html

TS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtyvjmquyi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gtauloqzpv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtrxsmfvcl.html

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gtlsahdapl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwviwreav.html

[E12] 统计某字符出现次数
来源：http://dali.zhengqikj.top/Article/details/gtnhdzzvsy.html

Py:   s.count("a")
来源：http://dali.tanke756.top/Article/details/gtifgniwja.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gtgliwqaam.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtnlzktyzw.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtinrdroth.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gtomtnddid.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gtjqbhmtxh.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gterfwhett.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gtcjkfqaeb.html

[E13] 逐字符遍历
来源：http://dali.quarkkingdee.top/Article/details/gttenpiply.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gtsqxknedk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cashguo.top/Article/details/gtyvcpgghm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtzxxmvnqg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtameoltvx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtxmqweouo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gtvxbztgtp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gtdtgejqlf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hammf.cn/Article/details/gtkckbyooz.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gtcbgpvido.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gtvbqegrcw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jyoumei.cn/Article/details/gtusotijbv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gtzawygvsh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gtigqzvtll.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtwsvcwsqi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gtgauxyryx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xziqi.cn/Article/details/gtxxqskgcq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtweyjxqgk.html

[E15] HTML 转义 / 反转义
来源：http://dali.aibaodan.cn/Article/details/gtlfgjyrdb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gtsuioyxwk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hfpthk.cn/Article/details/gtnbljtihs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gtbyrapojk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangdashe.top/Article/details/gtvgqvyrxz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxblynxhg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pycfn.com/Article/details/gttpipzoso.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtmfdieqch.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gtnnlprwkn.html

[E16] 数字千分位
来源：http://dali.haohaochexian.top/Article/details/gtickbwjzj.html

Py:   f"{1234567:,}"
来源：http://dali.nwbrower.top/Article/details/gtpegdokqs.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gtsigdlzuz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gturfaadbq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtdtapagcx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtblrmfrgw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gtmspjosqt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jlsjyb.cn/Article/details/gtlxwklnbh.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gtnarzgjyp.html

[E17] 首字母大写
来源：http://dali.dianchejie.cn/Article/details/gtybhirojp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gtudzouwqa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gtqnfzpken.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtmgeugvhi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtjguwlmet.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jyoumei.cn/Article/details/gtuwxynglg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gtghpncfgd.html

Ruby: s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtjjjjwygr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gtupolncfl.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gtzkclldiy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gtbkvxzpkj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gttyjxoiat.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtdestywuc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtgdexcija.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtujnhiudk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gtniorrvsx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gtqhvaaphs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gthmkujdlf.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gtdhhomtkg.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmsblvyh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daria6918.cn/Article/details/gttksyzdym.html

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtyuhqnrgf.html

TS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gtwlnrjgik.html

Java: s.lines().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtsrroejnh.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtusbyvpol.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gtcionybtv.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gtaqchfwgb.html

[E20] 判断字符串是否为空
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlohowfax.html

Py:   if not s:
来源：http://dali.pycfn.com/Article/details/gtlqlogjto.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gtnyphzjjc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenlinnsp.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gttjdorhfz.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtaalcskry.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukbygltb.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gtoksuxfxg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gtlcxuchwp.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtfjiqlpvt.html


<!-- 参考信息 -->