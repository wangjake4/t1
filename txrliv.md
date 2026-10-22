代发 wailian999

[D15] 去重
来源：http://dali.sweek.top/Article/details/gtfskthfwr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtgjktjzvm.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtsfeyprum.html

JS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtsuygxuav.html

TS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtibqsxadz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gtivkenyzd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gtfnqrpqyz.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gtixhjpfpn.html

C#:   list.Distinct().ToList()
来源：http://dali.cqqwz.cn/Article/details/gtouioqmms.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gtkohwjwvx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gtyuwbaebh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gtnjspstio.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtcexibqjy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtjoyerhxz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gtvtbgdxxn.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtntmixpew.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shuidangran.top/Article/details/gtznhxvznc.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gtrtehxxlf.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gtfxmulvau.html

Py:   max(arr);  min(arr)
来源：http://dali.c1oappe.top/Article/details/gteuntjias.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gtruskqgpz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.quarkkingdee.top/Article/details/gteirbxbyu.html

TS:   Math.max(...arr);
来源：http://dali.gaohongyu789.top/Article/details/gtcsbcnxvd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gtntqfesyn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtcsghqnon.html

Ruby: arr.max;  arr.min
来源：http://dali.sxryk.cn/Article/details/gtuenvxroq.html

C#:   list.Max();  list.Min()
来源：http://dali.zhongyouzk.top/Article/details/gtlnhxtjpj.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gtdxcsdmev.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.andypj.xyz/Article/details/gtraqurhdp.html

PHP:  array_merge(...$nested);
来源：http://dali.shuidangran.top/Article/details/gtsoczrdmx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gtkxclxjwe.html

TS:   nested.flat();
来源：http://dali.tanke756.top/Article/details/gtvleosnwe.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gtpwjhpofl.html

Go:   // 手写双层循环
来源：http://dali.xinyue.icu/Article/details/gtnubfhnrw.html

Ruby: nested.flatten
来源：http://dali.yanxiufei.cn/Article/details/gtuupnkpoa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtgivgrhlc.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gtcyujhdre.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ydzc1.top/Article/details/gtwblwhifj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuanzx.com/Article/details/gtxzkitupj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigfzy.top/Article/details/gtpejtozfs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gtjvpbyddz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gtrigpydzu.html

Go:   // 手写 map[string][]T
来源：http://dali.yanxiufei.cn/Article/details/gthjcvfqwb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.quarkkingdee.top/Article/details/gtrzmrfroh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258.top/Article/details/gtynaqaxkh.html

[D20] 统计每个元素出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtgkosxzox.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gtzdhkburp.html

PHP:  array_count_values($arr);
来源：http://dali.yj202588.top/Article/details/gtratmsyts.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtnyqjskxm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtsrzmgifx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gtadhiaefn.html

Go:   // 手写 map[T]int
来源：http://dali.xinyue.icu/Article/details/gtmsedrlof.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gtcyqjeymg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.smart0.xyz/Article/details/gtwpafrykb.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gttrrgqlra.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtjvoplsqy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gtmhklcpng.html

JS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtfhpqlyhy.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtlqvfyesr.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtjpybdzay.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtqgeihtuf.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gtztyovzpd.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gturscigbm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gtfiaadpvs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yueranfly.top/Article/details/gtbfmsawid.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gtuhofvtyf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sufxvd.cn/Article/details/gtuoqibrmy.html

TS:   [...arr];
来源：http://dali.yonumen.top/Article/details/gtlbrvtkah.html

Java: new ArrayList<>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgcxntet.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gogol.net.cn/Article/details/gtoyiaphqo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgfzy.top/Article/details/gtennbtnav.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gtfybhuekq.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gteoiqdbkd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtwninhnvi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gtvegpnodl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gttqyrtkxy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtwefpjvhy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gtdyqosagt.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gtpamgmbht.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gtrkwwchcw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gtpkzvcacj.html

[D24] 字典 / Map 基本操作
来源：http://dali.tanke756.top/Article/details/gthqpuxjuf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.c1oappe.top/Article/details/gtaztcvmvr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.vqdsnc.cn/Article/details/gtyebnbhik.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gthxawoplx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fengsongda.top/Article/details/gthpgockwj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zdqjudy.top/Article/details/gtkjkyurgq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gtaxkjrcvy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gtjfnzmvaj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jianghu66.top/Article/details/gtratebjhy.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gtxhifzzib.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zycfv.cn/Article/details/gtrlfrnyrh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gtuzpdyyud.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.bjfxy.top/Article/details/gtijcsjzrs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ehwqpu.com/Article/details/gtjxxmiukq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtctipksoo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuanzhike.top/Article/details/gtlwimfdil.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cashguo.top/Article/details/gtluhowgau.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtoytyfwer.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gttghhyuvu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gtbqfmmcur.html

PHP:  implode(", ", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtuqqqabmu.html

JS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtupsmfusy.html

TS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtofghcmut.html

Java: String.join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtjjkaloyv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtjlvjdfub.html

Ruby: arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtuowkfhfl.html

C#:   string.Join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gtswtjzwom.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtomlaooph.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gtfagaijjs.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmoqdlnmt.html

[E01] 拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtqefoowvx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gtlrcorxib.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gtqgjyrxtx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtabwunqog.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtkvaiglxj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gtwahepxzs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gtzzcmzwmy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gtfvpycxuk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtsyoqggbd.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gtqupexvhx.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gtisvpjouh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gtnhewzbcs.html

JS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtdraaqaam.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gteymgealp.html

Java: "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtcjbmtskg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fengsongda.top/Article/details/gtizsckpmh.html

Ruby: "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwouafbwd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yonumen.top/Article/details/gtrwlzrlwg.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gtbzakyhpr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gtwyprmivr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtldwtrtxr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtxpakdoir.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gtgitnqnps.html

Java: s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gtbfgqeozd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtsvchpgdc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtfqlssxws.html

C#:   s.Substring(1, 3)
来源：http://dali.0kj1m.cn/Article/details/gtltggfzge.html

[E04] 查找子串位置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxopfxqir.html

Py:   s.find("x");  s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtftsnjblq.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gtqzzycgpw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gtosmbzehi.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gticeqtlml.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtdaxncqgj.html

Go:   strings.Index(s, "x")
来源：http://dali.vqdsnc.cn/Article/details/gtlsfnqpmb.html

Ruby: s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gtdzvxdgpk.html

C#:   s.IndexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtvmrfcjpe.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gtmrrvcmje.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtnljzuprw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxuanxn.top/Article/details/gtvkmiwroh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtkjnuhlih.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gtzklhadzg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtbofhfhlo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.svipenyu.cn/Article/details/gtcizevbsz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gthpmhdwze.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtkoxxjgmj.html

[E06] 替换子串
来源：http://dali.zhiwuduotai.top/Article/details/gtrjdcqfjo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtsrfjmeij.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cqqwz.cn/Article/details/gtlgkbpbjs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtsrkhhyfv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbpmoacq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtahfgfzat.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtatwyahlf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtiawobdfz.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258888.top/Article/details/gttorecivs.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gthjafkgdk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hfpthk.cn/Article/details/gtqsmsmqzt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtzzizwmwk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hysaishi.cn/Article/details/gtxlutgwqt.html

TS:   s.split(",")
来源：http://dali.9152youxi.cn/Article/details/gtnnhecgnd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxuanxn.top/Article/details/gtdhrgqhar.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gteasljcqg.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gteichifuz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gtgjaokbej.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtbnlsxyod.html

Py:   ",".join(items)
来源：http://dali.tanke756.top/Article/details/gthovjlegp.html

PHP:  implode(",", $items);
来源：http://dali.tian-w.cn/Article/details/gtxnihwwzo.html

JS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtjabvqpdd.html

TS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtqaxovfxi.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gttncbblsq.html

Go:   strings.Join(items, ",")
来源：http://dali.yongpay.top/Article/details/gtjzajujae.html

Ruby: items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqecwgozu.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtlmvphfbw.html

[E09] 去除所有空白字符
来源：http://dali.zhiwuduotai.top/Article/details/gtjwueoqgu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gtjlrhmmbr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gttkoeaqwr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtzbkzunmr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtglqtgvuk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtgsxkqhrj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gtrcbdbpqt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtpisucchh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gtzlvetcca.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gtjgirsdiy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtxlcnmtjt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shuidangran.top/Article/details/gtmbpefcqg.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtfejdiioj.html

TS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtjatjkuov.html

Java: String.format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtjrjadaeb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtawnrimta.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtgmlgeusa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenjidiqi.icu/Article/details/gtzxhppdjp.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gtlwilknsw.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtftyihcmb.html

PHP:  strrev($s);
来源：http://dali.yuxming.cn/Article/details/gtoxavaibu.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtmgzozexw.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtelvmzzeb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cashguo.top/Article/details/gtbnzpazgo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtdpkzfcmb.html

Ruby: s.reverse
来源：http://dali.cheryme.top/Article/details/gtzyilxhdn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gthidemtdl.html

[E12] 统计某字符出现次数
来源：http://dali.316326.xyz/Article/details/gtaoohfhyj.html

Py:   s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gtgwfbttfd.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gtoqtgucew.html

JS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgazmumf.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtdrlaqzpk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssfymhni.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gtuhtezfdw.html

Ruby: s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtpkwnpjdy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gtpwdztlvs.html

[E13] 逐字符遍历
来源：http://dali.birdmap.top/Article/details/gtdvdmevww.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gtbuqyqrdk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gtkhymfqew.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtlgsynwjx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtmclzpkwn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtqxabfnik.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gtvmbvfyzo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.mhx1999.top/Article/details/gtifrwhdgu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtzaprmubl.html

[E14] URL 编码与 Base64
来源：http://dali.tian-w.cn/Article/details/gtbadbniza.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtcwnhuilm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gtvhenogiu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gtlrsxiegl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gtpwtvcujs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gtwdluvejy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aibaodan.cn/Article/details/gtlllyhcts.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daria6918.cn/Article/details/gtbcqtveyk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gthrdpjeze.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenzaomai.com/Article/details/gttfjofvhh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dianchejie.cn/Article/details/gtduqqfrqp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gthiglxdxn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shuidangran.top/Article/details/gtdtzjbqzm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gtqltxsvfo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gttruzibtq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtkllbirox.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jlsjyb.cn/Article/details/gtwnjxdcju.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtuxdrfjrs.html

[E16] 数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gtklsyktda.html

Py:   f"{1234567:,}"
来源：http://dali.daria6918.cn/Article/details/gtebhxkgyo.html

PHP:  number_format(1234567);
来源：http://dali.chenjidiqi.icu/Article/details/gtgkoxembe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtzqnpgqyt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gtzgpukddw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gtnxvpmfyd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258.top/Article/details/gtasgjfalr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gtjrahmrwr.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtugiayvam.html

[E17] 首字母大写
来源：http://dali.cucudq.cn/Article/details/gtrcjhcqpz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gtjbvyazsd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtqzeoqvbn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtieqcuamy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtebyokxya.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtcbkescyc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gttlnblrvi.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gteoesccbl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gtaahcuscr.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gttwgtyxqq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gtnutdauhg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gzhubu.top/Article/details/gtastuhwuw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtyxkiicxr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtravdvqxd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdggpbys.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanoherii.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gtssixlucd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258888.top/Article/details/gtnqyfoxei.html

[E19] 多行文本按行拆分
来源：http://dali.xylfe.cn/Article/details/gtllaavavb.html

Py:   s.splitlines()
来源：http://dali.0kj1m.cn/Article/details/gtxhdyvhdk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtyenxgorb.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuegsdcia.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtaqnvhsjl.html

Java: s.lines().toList()
来源：http://dali.c1oappe.top/Article/details/gtqxczqvql.html

Go:   strings.Split(s, "\n")
来源：http://dali.meibo888.top/Article/details/gtductuvtq.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gtjebywxps.html

C#:   s.Split('\n')
来源：http://dali.aibaodan.cn/Article/details/gtwezimguo.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gthyhrlhrs.html

Py:   if not s:
来源：http://dali.chenzaomai.com/Article/details/gtedyxffzl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gtzrvbxpat.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gttzbrzgug.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gtinkggzzz.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gttliqvjfd.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gtuwwzwlra.html

Ruby: if s.empty?
来源：http://dali.yuanzhike.top/Article/details/gtrtnhbnaz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzupyigfw.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gtjusyjatg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gtzvadyivu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnooobrk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtelmxarho.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gteruoysiu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtuuuhaxyy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gttwkykgcr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtqucfvral.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtbztyfvum.html


<!-- 参考信息 -->