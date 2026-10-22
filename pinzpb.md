代发 wailian999

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gtiqyhlouq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtmcxsrdsr.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gttgngssyl.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtmflvcwva.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gthxkdjiry.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gtihzqvyzm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gtchpitalh.html

Ruby: arr.uniq
来源：http://dali.nanxuanxn.top/Article/details/gtlsjcmssn.html

C#:   list.Distinct().ToList()
来源：http://dali.chenzaomai.com/Article/details/gtemktpdum.html

[D16] 求和与平均值
来源：http://dali.gzhubu.top/Article/details/gtbyscvdhs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnqzz.top/Article/details/gtjvowlngy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtcnrtxdyn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gtbgoztjxt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtvldqhtlx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gtlepobezi.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtoocnyxkb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gtllguzcmo.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gtvwpaensn.html

[D17] 最大值与最小值
来源：http://dali.sweek.top/Article/details/gtpbbshcft.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtppksnsyc.html

PHP:  max($arr);  min($arr);
来源：http://dali.svipenyu.cn/Article/details/gtevixgccj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gtwjhturzh.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gtwdmempwu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ivvv.top/Article/details/gtljusxgsc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gtkdlnwyvy.html

Ruby: arr.max;  arr.min
来源：http://dali.yongpay.top/Article/details/gtyqypgjqk.html

C#:   list.Max();  list.Min()
来源：http://dali.xylfe.cn/Article/details/gtjcocfyyi.html

[D18] 扁平化嵌套数组
来源：http://dali.hongshengwenyu.top/Article/details/gtyjjzlzif.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.svipenyu.cn/Article/details/gtjcqrcsld.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gtnwbvjkns.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gtzitynqzx.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gtgqklnbca.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fengsongda.top/Article/details/gtwxethwtq.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gtseikhalf.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gtelupakjr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aizwys.cn/Article/details/gtdskjcart.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gtftnevuft.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cdnleiting.top/Article/details/gtjdhrqlbo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj202588.top/Article/details/gtadgnzeka.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gtmlopaazu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gtwarytdzk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gttsmcnhsh.html

Go:   // 手写 map[string][]T
来源：http://dali.kuanghao11.cn/Article/details/gtvmqlcprv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnqzz.top/Article/details/gtjsiangbp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gttncqqtxc.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtznuplnck.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gtiwqlxdpt.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtljwsbqhe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsjvzfci.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtwtbbwzlp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gtvwiazxce.html

Go:   // 手写 map[T]int
来源：http://dali.daxiang520.top/Article/details/gtnesyqxhl.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gtpafzeext.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gtmwqvkogy.html

[D21] 判断是否包含某元素
来源：http://dali.cucudq.cn/Article/details/gtvnifllzb.html

Py:   x in arr
来源：http://dali.svipenyu.cn/Article/details/gtzudhwuqw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hfpthk.cn/Article/details/gtwjepxnkl.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtxqnupied.html

TS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtbgcxzard.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gtrgyzuavg.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtykvotwla.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gtjqijbzfv.html

C#:   list.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtqneynxke.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yanxiufei.cn/Article/details/gtwtshguzq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gtfxxgpurs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqovouas.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xylfe.cn/Article/details/gtmugwbfpk.html

TS:   [...arr];
来源：http://dali.ehwqpu.com/Article/details/gtfcghobsg.html

Java: new ArrayList<>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvmojnew.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pycfn.com/Article/details/gttkjqeujb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gtcvnxjuct.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtfevqcgpy.html

[D23] reduce 累积计算
来源：http://dali.nanxinkj.top/Article/details/gtzgitlpgt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hammf.cn/Article/details/gtjzcrodrp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gtvepddqaj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtdpncdbtv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtmgkokeld.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gteiziofae.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtefzcyabm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tian-w.cn/Article/details/gtazzswped.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xinyue.icu/Article/details/gtxxcjfcsp.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gthgzrrboi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dianchejie.cn/Article/details/gtzmzazhes.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aizwys.cn/Article/details/gttztsiunk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtkqgndxlr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtbxnispzi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfduigedz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gtzluwgklm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tian-w.cn/Article/details/gthyrnrjah.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gtgiotzqvv.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gtcaozfzui.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gttrvxzjee.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gtowxhqjeb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gtrlywapxl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gtcepxhikx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtouoobdxd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.andypj.xyz/Article/details/gtncqwyyug.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtdtvuhall.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtyjjwwdip.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gtprvxzjqg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gtxkiztqoh.html

PHP:  implode(", ", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqphcscbw.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtrrkqdyaf.html

TS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtnjucyixr.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gtlqahycmq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.c1oappe.top/Article/details/gtsnnvybdc.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtsfehahox.html

C#:   string.Join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtusxlrgwr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gttebbjfww.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gtynizkksb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtngrigfoy.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmdijnmr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnqzz.top/Article/details/gtmwecxhhq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygpzhzbt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtmeskdmdf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gtdearzsub.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gtbhgxvdqp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxinkj.top/Article/details/gtdqqkocjp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gtbzfliamg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecqogdti.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gtlxujtydc.html

Py:   "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtldvbpcwu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gtvjfqgneb.html

JS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtyfcxcgiq.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gttwhnzukv.html

Java: "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtvuinjvwd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aizwys.cn/Article/details/gtgkvqukuk.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtqejjwczk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daxiang520.top/Article/details/gtgczdgxgd.html

[E03] 截取子串
来源：http://dali.sweek.top/Article/details/gtpvvqaody.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgufenzy.top/Article/details/gtccotxbhs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtuwotgddv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gthebeofnt.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtwuszdbmz.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtqwhzrywp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.redwolf501.top/Article/details/gtznlnnrgm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xinyue.icu/Article/details/gtywxprmcf.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gtliqssyuq.html

[E04] 查找子串位置
来源：http://dali.vqdsnc.cn/Article/details/gtnbruydwl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfdhnzrs.html

PHP:  strpos($s, "x");
来源：http://dali.daria6918.cn/Article/details/gtpminczbf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pengpengdd.cyou/Article/details/gtmsxaxwmw.html

TS:   s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtiwegagwa.html

Java: s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtoczjobqv.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gtoucnatgw.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtzdrqxzks.html

C#:   s.IndexOf("x")
来源：http://dali.pycfn.com/Article/details/gtvcbltkpv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nwbrower.top/Article/details/gtuoobuqfd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.andypj.xyz/Article/details/gtsfzddxqo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cdnleiting.top/Article/details/gtrepfjixz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtjnscxcdb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnqzz.top/Article/details/gthhnqmiew.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtoqtvpuhm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gtuusnvesm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ppjwa.cn/Article/details/gtwuygpbbm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtnympibjl.html

[E06] 替换子串
来源：http://dali.hongshengwenyu.top/Article/details/gtbypdkscs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtntaxvaul.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zdqjudy.top/Article/details/gtjsaelxfr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtfqmaxdxn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtczaqndsm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtljjmwoay.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtxrcfepvd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtsdpmsufz.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztdkdznq.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gtpjbhehho.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinghuilouyu.cn/Article/details/gtskflomgq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gthftimhan.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.mhx1999.top/Article/details/gtjodyikwl.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gtdcuwwiki.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gtakgkueni.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gtpkoxoaut.html

Ruby: s.split(",");  s.split
来源：http://dali.daria6918.cn/Article/details/gthtruxgkd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gtnkbifami.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gtbtxjlalk.html

Py:   ",".join(items)
来源：http://dali.yangfankeji.com/Article/details/gtonlckjqm.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gthoykomrt.html

JS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtoaikarjk.html

TS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtvsyjhkkm.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtcnosymmg.html

Go:   strings.Join(items, ",")
来源：http://dali.chenzaomai.com/Article/details/gtiqciuxsd.html

Ruby: items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtjkclaljn.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtbfipnucj.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfzkpeqc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtoeryvgcu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbxjttmq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtgpjptvxv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtbgfrmurh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtaimgjehn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gtmwhfnyus.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cheryme.top/Article/details/gteewtvwcu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtnseysuml.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tianlin.xyz/Article/details/gteasyfsol.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtfhfvadcq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gtzyfwyira.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjhayoxx.html

TS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtxlatfccw.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtwhwuhxso.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtuahjngxq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gthnljtlux.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gtoindjwkd.html

[E11] 反转字符串
来源：http://dali.guannengcc.top/Article/details/gtlraqrknd.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gtlvzqjlvw.html

PHP:  strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtbyrqyrdk.html

JS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gteykgzgek.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkujylnbo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtblvjrpre.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gtoufhvava.html

Ruby: s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtqsxrqqzh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtktouctkc.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gtiehoivhb.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gtynjylbgy.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gtbefykenf.html

JS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtjcqqvckj.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtvgpgjhwj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gtjxhiqlrz.html

Go:   strings.Count(s, "a")
来源：http://dali.ydzc1.top/Article/details/gtxkslojfe.html

Ruby: s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtxoasnjfj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gtpcnqhpfg.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gtkizhcxzb.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gtppdzkybm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gthalpkhnu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtcwckmkgp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtgolerffd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtfgxjswpf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gthnhkywup.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gtrcfagurn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tanke756.top/Article/details/gtzextafxu.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gtexxkqdpu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpopqaeu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yangfankeji.com/Article/details/gtvghyvfox.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gtjnjvyyxx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gtlnibzmrq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtoofxsgfm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangdashe.top/Article/details/gtstolcvxu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyaotfshw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtgdgvjdtq.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtenvoksry.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnxiangtu.top/Article/details/gthkooinux.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkddtdkib.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gtpewlbykn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gtpojhlzju.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gtcjibhaug.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtizzumtmv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlfxzdjf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gtxdqedugs.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gtztvgbkrh.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtvfxthtwe.html

PHP:  number_format(1234567);
来源：http://dali.nanxuanxn.top/Article/details/gtztqvxiww.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gtvettnytw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtpkfftdqp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtlxnihavt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gtnfersibs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gaohongyu789.top/Article/details/gteitagczz.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtezattxcd.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gtrozdibwx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gtrskcyoev.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtwiwytzwi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtebgukjlw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtyhkpkffu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gtvrxwwxbi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gtojhcduob.html

Ruby: s.capitalize
来源：http://dali.fzhhl.top/Article/details/gtjtctopyk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxinkj.top/Article/details/gtewbfwxhm.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gtpthxteal.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtixptgpdd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gtipbxwljn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gthsiyslvd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gteggxjixp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtsxymwvec.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtkjhhtpmu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gtscgdnoci.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tian-w.cn/Article/details/gtstgpnqag.html

[E19] 多行文本按行拆分
来源：http://dali.xylfe.cn/Article/details/gtivcpzfco.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtfoadtjcg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gtnycwueuf.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gtmearskpx.html

TS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtkltifhfs.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gtbhvdrvub.html

Go:   strings.Split(s, "\n")
来源：http://dali.xylfe.cn/Article/details/gtkceqoiue.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gtuoqrnroe.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gtuibagcyb.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gtuvciehza.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gtirvlxizn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gtvqgrznss.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sxryk.cn/Article/details/gterdqhger.html

TS:   if (s === "") {}
来源：http://dali.birdmap.top/Article/details/gtxopipsci.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtrjhaaxih.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gtxjomkisv.html

Ruby: if s.empty?
来源：http://dali.hammf.cn/Article/details/gtdgtgyxja.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gtazlntzly.html

[E21] 超长截断加省略号
来源：http://dali.sweek.top/Article/details/gtsnrzlhon.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yongpay.top/Article/details/gtjjhyrwip.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtbqwwkokg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtceaznora.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtokspgkkf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtzhceynaw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gtjvazuaer.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtqulophql.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtndputzou.html


<!-- 参考信息 -->