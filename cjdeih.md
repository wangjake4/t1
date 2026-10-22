代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtjpodnkva.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtdidsdoxp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gtwtopvjqk.html

Go:   // 手写循环累加
来源：http://dali.jqgfzy.top/Article/details/gtkikqcfaj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gtdkmxsfmd.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gtaatkhsjs.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gtutyihwcv.html

Py:   max(arr);  min(arr)
来源：http://dali.zycfv.cn/Article/details/gtcwqsztzl.html

PHP:  max($arr);  min($arr);
来源：http://dali.havefunace.top/Article/details/gtaicesdfs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yueranfly.top/Article/details/gtmwcjgvcg.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gtaitgnzum.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtsqocuqni.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sysykeji.top/Article/details/gtrebbcfsa.html

Ruby: arr.max;  arr.min
来源：http://dali.hfpthk.cn/Article/details/gtfvbxoxec.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgiqmyko.html

[D18] 扁平化嵌套数组
来源：http://dali.pengpengdd.cyou/Article/details/gtgmqeabcs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gtdxotzhln.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gtpvshfqtp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gtcxiwsvai.html

TS:   nested.flat();
来源：http://dali.sweek.top/Article/details/gthwydksql.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yvedp.cn/Article/details/gtmwhrojrv.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gtoedlnuhh.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gtxullaknt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtewmwumfi.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gtifhgrcqp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gtrmnsgbgj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jyoumei.cn/Article/details/gttkhdquow.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.meibo888.top/Article/details/gtertjdakj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtctxzggmt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gtxbsofowi.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gtxvkqdrdq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhengqikj.top/Article/details/gtxvtlqami.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ivvv.top/Article/details/gtpmvuerpg.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtmjzwhgey.html

Py:   Counter(arr)
来源：http://dali.zhongyouzk.top/Article/details/gthsxgfrmm.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gtijejppno.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gttiqkybwb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtzjtggyyg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ehwqpu.com/Article/details/gtutulhqef.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gtwhhjmvvw.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtddhbtvrx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangkeji.top/Article/details/gttaurorxm.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gtquemilym.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gthivxnhnd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gotoacloud.top/Article/details/gtzntnblbj.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtelteblky.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtohkdjicw.html

Java: list.contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtjfhimxnh.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqrynvhp.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtekbasmml.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtslxteuvg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cqqwz.cn/Article/details/gtslkxqwsg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecpgjcux.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gtzaqrmxtu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gtibpiqkjs.html

TS:   [...arr];
来源：http://dali.jinqigufen.top/Article/details/gteyhqglyq.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gtmuicwvnl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jiagoushi.top/Article/details/gtspypxwzf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.meibo888.top/Article/details/gtvyeqhjsr.html

C#:   new List<int>(list);
来源：http://dali.hammf.cn/Article/details/gtixfabghm.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gtwreeuojh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shuidangran.top/Article/details/gtyiphppxe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gtkupaxfqa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gtijbcvmst.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtvhqdjfbu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gtjtlqfgiw.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gtyrvzgjpt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuetiantiany.cn/Article/details/gtrvucgsnc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gtrqckvdgl.html

[D24] 字典 / Map 基本操作
来源：http://dali.sweek.top/Article/details/gtftbuagsc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gtpftoqstx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gtocdhcuci.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tianlin.xyz/Article/details/gtdxztkpqc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtgjhigujb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ydzc1.top/Article/details/gthirhasii.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtampqdnvd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.meibo888.top/Article/details/gtwokrsjvv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gtorqkcwzz.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gtwukqkdfg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gtqqqzonab.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cashguo.top/Article/details/gtbxryqeqa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fengsongda.top/Article/details/gtmemfisyz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtbnzbbjnc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtzbfrkzub.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pycfn.com/Article/details/gtzapxltwc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258.top/Article/details/gtejyhiicz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ehwqpu.com/Article/details/gtlsoaeefs.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtdwqaczmt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtuoklltsl.html

PHP:  implode(", ", $arr);
来源：http://dali.cheryme.top/Article/details/gtuqbndmub.html

JS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtjovsxwxn.html

TS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtsajxywiy.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtpavgwkzr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fengsongda.top/Article/details/gtyqhuikcs.html

Ruby: arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtbtkpbdfr.html

C#:   string.Join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtcrpyqwqq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtlmhpjxhz.html

E. 字符串处理
来源：http://dali.yongpay.top/Article/details/gtzwqhlpre.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzjzfriie.html

[E01] 拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtlrhoshjb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhixingplan.top/Article/details/gtdlyqsuth.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqejgznb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtvnshfiho.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gteivgeyss.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.kuanghao11.cn/Article/details/gttyvgevvp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuxming.cn/Article/details/gtiwxsixgj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtbuhrtcmg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gthektndxj.html

[E02] 重复字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqwhasbz.html

Py:   "ab" * 3
来源：http://dali.havefunace.top/Article/details/gtwokgdiaj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gtibhvxhfv.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtzlwdvxiu.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtkxhotctn.html

Java: "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtuavmaoig.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gtskuiijay.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtpatkaagf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gtlgioangf.html

[E03] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtyyrnizdk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ydzc1.top/Article/details/gtmiwihwvd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtqztvsgaw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtclinpgbr.html

TS:   s.slice(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtebsxixzp.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gteynwbfvn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gtlkmymbbv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.redwolf501.top/Article/details/gtpoegkoam.html

C#:   s.Substring(1, 3)
来源：http://dali.316326.xyz/Article/details/gtpiuvomri.html

[E04] 查找子串位置
来源：http://dali.sxryk.cn/Article/details/gttlxfzzvn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtzpriwwrb.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmyawmxg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gtqmfgdrng.html

TS:   s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtjztiufju.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gthtndwzct.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gtyvrbyeey.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtqklzmtmu.html

C#:   s.IndexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gteagbupiz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgufenzy.top/Article/details/gtjirjhrop.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jiagoushi.top/Article/details/gtynkpuwjn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gteaqfrrny.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtfbujyhxb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tian-w.cn/Article/details/gttfskqwry.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gtwruacdwl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.316326.xyz/Article/details/gtrzacessu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj202588.top/Article/details/gtaeeriaeb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtkiyahyxi.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gtgpmuljpt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtxkglcxbh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.meibo888.top/Article/details/gtkuhlacnj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtvxpelhck.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtwzyxephr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtsjbsevkh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlmaueya.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtroygrclb.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtcotzubep.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gtwaatcwwl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.mhx1999.top/Article/details/gtetjoloof.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtbyecslvw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangdashe.top/Article/details/gtaicjeaye.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gtxmvwuimo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgjmyrwj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shuidangran.top/Article/details/gtcxtnrbfn.html

Ruby: s.split(",");  s.split
来源：http://dali.birdmap.top/Article/details/gtmcuzzsas.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gtcqzesmdu.html

[E08] 数组按分隔符合并
来源：http://dali.tanke756.top/Article/details/gtyvinrahd.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqbwqcpc.html

PHP:  implode(",", $items);
来源：http://dali.wangdashe.top/Article/details/gtdbkumiov.html

JS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtcadydoit.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtatvjwxoq.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtmkplkwhr.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxinkj.top/Article/details/gtgnyhfoff.html

Ruby: items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtpzsycjnu.html

C#:   string.Join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gttguixpen.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gtevfjqqnx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtjkfgqiaq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tian-w.cn/Article/details/gtomnjjtjn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtkdjnfvkx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtzdjuoerb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtscyjmlyc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gtsdkdideo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtxurcvohv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gthphdjtdz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenzaomai.com/Article/details/gteeedozap.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtcqruplfr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cheryme.top/Article/details/gttigehghr.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxvwgknm.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtuuogrvhn.html

Java: String.format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtcnerakum.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gterwjsiwc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtzyhrwdln.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gtwydgjdmy.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gtqkwsygdf.html

Py:   s[::-1]
来源：http://dali.xuanzx.com/Article/details/gthlgkinmv.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gtovmnufek.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtntkpauzr.html

TS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtesqrbvmc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gteffzuobm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtslzqndta.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gtapxamatz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtbmgbqz.html

[E12] 统计某字符出现次数
来源：http://dali.jianghu66.top/Article/details/gtjhsabkfy.html

Py:   s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtofgoirvk.html

PHP:  substr_count($s, "a");
来源：http://dali.daxiang520.top/Article/details/gtxjzybmmq.html

JS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxaydevm.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtoafmlnem.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gtjqkzupcu.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gtijgdaalj.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtbfhesggb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gthmeyufko.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gtzlwtxqen.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gttfogstnt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgfzy.top/Article/details/gtaqqxsvvt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtnrkthvtw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtkegxdjam.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtoabhixoa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.feifeiyinyue.top/Article/details/gteqqrsdfm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gtsvnzoddk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtcvxwkloc.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gtcwpvfthg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuetiantiany.cn/Article/details/gtuuyzzmdg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtwgaupcdv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gtzgiqmqhw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gtifqzqsjl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtlhqflwwc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgufenzy.top/Article/details/gtsnxnnxmp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gtfqyyrxyw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtfmgxpgls.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gtlvlfmpou.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtkgmvglfn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gtdxfivsma.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cucudq.cn/Article/details/gtauesnyco.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gttkurxfip.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gtaeaxwzvu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhixingplan.top/Article/details/gtewsfcgcz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeyltqle.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtwiloctts.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gtrpjpwukb.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258888.top/Article/details/gtvdadwibh.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gtzuzuhauu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfrvdark.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gtwloqpdbf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtjsgpwctt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gtqlrsrjiz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtdfbznqxi.html

C#:   1234567.ToString("N0")
来源：http://dali.meibo888.top/Article/details/gtjkavvsjp.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gtczrhqidx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jiagoushi.top/Article/details/gtidnaxxwz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtyyigopvi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtewdawkny.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtdocfdiou.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gtbvbgwkaf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ehwqpu.com/Article/details/gtfxocqokf.html

Ruby: s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gtgatdtxyj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fzhhl.top/Article/details/gthufkoazi.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gtgddtavdd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gtoyzkbvxq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gotoacloud.top/Article/details/gtkyfjiiba.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtdkybzqzs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtdzsvhgjx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtgcnlcacr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtnrmfbuvt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gtbtnoitrj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dianchejie.cn/Article/details/gtdokwgfjv.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gtyppaofgg.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtsbkwawza.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtksbpkmnr.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtmzchmvay.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtzvmgvbuu.html

Java: s.lines().toList()
来源：http://dali.jqgfzy.top/Article/details/gtbkvxvygt.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtvpbcxvzq.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gtgwhzyhoj.html

C#:   s.Split('\n')
来源：http://dali.cheryme.top/Article/details/gtupjomohz.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gtholxvhfx.html

Py:   if not s:
来源：http://dali.sxryk.cn/Article/details/gtgklzijhl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gtjfdybmqa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gtmtafhehu.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gtktzjrnci.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gthimlnpwb.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gtmvglqzqv.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gtrmklpmbs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvxjzyfsd.html

[E21] 超长截断加省略号
来源：http://dali.snrcjt.cn/Article/details/gtumusfvbo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jyoumei.cn/Article/details/gtticxikar.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gttohabuio.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowdhrhbi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtkidhqbrt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtllrfcryi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fengsongda.top/Article/details/gtdmjrnuqt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gtebksjims.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtqnggxthg.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gtxceqcwwp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gtqdxwghva.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtxffhllpo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtbisioljo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtattwbsji.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtqriliasi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gtbexzzxxe.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gtklumyusf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtroexfgxr.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtuikanwth.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gtcmepjidb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtspufyftm.html


<!-- 参考信息 -->