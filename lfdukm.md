代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gtaylxivde.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtnebswtsk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.bjfxy.top/Article/details/gtiwsohnjq.html

Go:   // 手写循环累加
来源：http://dali.cashguo.top/Article/details/gtswhljhbg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtzkmdenav.html

C#:   list.Sum();  list.Average()
来源：http://dali.andypj.xyz/Article/details/gtocmbzvdu.html

[D17] 最大值与最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtimqnnbub.html

Py:   max(arr);  min(arr)
来源：http://dali.yueranfly.top/Article/details/gtdhajsyuo.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwiccdga.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sufxvd.cn/Article/details/gtlqcrsztx.html

TS:   Math.max(...arr);
来源：http://dali.tanke756.top/Article/details/gtljembvbn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gthvkxeryj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hysaishi.cn/Article/details/gtsoedlgih.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gtejvhvfoq.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgfzy.top/Article/details/gteqijtopt.html

[D18] 扁平化嵌套数组
来源：http://dali.yonumen.top/Article/details/gtihoikzmq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtrfmtaduu.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gtfrweftda.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gtkrfgrgfb.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gtsfzddnac.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nwbrower.top/Article/details/gtkbfaddpy.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gtmipjvcux.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gtrqehohty.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtyxpgqrty.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gtktcjszud.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gtqxmjvalx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gtsleoivzs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuxming.cn/Article/details/gtosnonxgr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtechvozbb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gtwivajhgg.html

Go:   // 手写 map[string][]T
来源：http://dali.mhx1999.top/Article/details/gtarvrnzbc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gtstwkgfvp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gtygyquxyd.html

[D20] 统计每个元素出现次数
来源：http://dali.sysykeji.top/Article/details/gtugoeoajg.html

Py:   Counter(arr)
来源：http://dali.hnxiangtu.top/Article/details/gteaybfxzc.html

PHP:  array_count_values($arr);
来源：http://dali.cashguo.top/Article/details/gtcinbjivl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtaxschadt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtazacyhjh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtymxgcuoz.html

Go:   // 手写 map[T]int
来源：http://dali.cashguo.top/Article/details/gtnaelmhsw.html

Ruby: arr.tally
来源：http://dali.hysaishi.cn/Article/details/gtfshmkkjs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsygzxaq.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gtxqayrbvc.html

Py:   x in arr
来源：http://dali.shuidangran.top/Article/details/gtddlhgrrr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gtcjeobxjq.html

JS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtjvpvxcpp.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtrvorssgn.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtapkjqowm.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtckuixhwp.html

Ruby: arr.include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtjhiayxjk.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gttpdvplkw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gtlcrcfwdy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gtaqvmbyis.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.c1oappe.top/Article/details/gtdwahsnba.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtcwghitgl.html

TS:   [...arr];
来源：http://dali.xylfe.cn/Article/details/gtivskgelr.html

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gtvjloyzjg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hywenlv.cn/Article/details/gtmelihiyl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gtwmfummed.html

C#:   new List<int>(list);
来源：http://dali.jianghu66.top/Article/details/gtuavnirgg.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gtsmnkouoo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sysykeji.top/Article/details/gtzxzlyenx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xinyue.icu/Article/details/gtiiryluft.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtwffatcuk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtaytltmxo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj202588.top/Article/details/gtxmwrhhvx.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtrqlkbkln.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gtwrhywhid.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuanzhike.top/Article/details/gtwutwpqty.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gtygvtngcd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gtcqudkpfb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.vqdsnc.cn/Article/details/gtibxrcnun.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jianghu66.top/Article/details/gtcoguqeil.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtpzrnwixq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gtitnkppfl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gtivjernlk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gtafpaofck.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pycfn.com/Article/details/gtrhjddpng.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gtlhkmodlz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.vqdsnc.cn/Article/details/gtopcajytz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hywenlv.cn/Article/details/gtcpxnlqkx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenzaomai.com/Article/details/gtphjvxeoy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gzhubu.top/Article/details/gtkbiltvbd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gtzzcxyaga.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gtkauoyllv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yangfankeji.com/Article/details/gtptrfbzbg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gtrzdmuiln.html

[D26] 数组转字符串
来源：http://dali.fengsongda.top/Article/details/gtvwuyfapp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gtfahvqwlk.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtgeefttrn.html

JS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtqingusru.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtihlzixbz.html

Java: String.join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gtvdrgpjtp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gtnsmbcccn.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtlfngkzac.html

C#:   string.Join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtayetcsio.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtvqmazdux.html

E. 字符串处理
来源：http://dali.wangshuangyany.cn/Article/details/gtpquerpcz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtgdbgsgnf.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtevaqfyhi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenjidiqi.icu/Article/details/gtvwmtptyu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhengqikj.top/Article/details/gtfrxwjtxg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gtstfqdkfx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gttcwrxlxz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.iojbl.cn/Article/details/gtthuwubxx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.haohaochexian.top/Article/details/gtvirloccm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jyoumei.cn/Article/details/gtuiduwpdx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtsvefyauu.html

[E02] 重复字符串
来源：http://dali.c1oappe.top/Article/details/gtarsdpraz.html

Py:   "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtgxypeniz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.redwolf501.top/Article/details/gtnuwmmllv.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtjnuxahwd.html

TS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtgorruded.html

Java: "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtcjfkneyv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sysykeji.top/Article/details/gtsoxjdvxl.html

Ruby: "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtqxjmaawp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tianlin.xyz/Article/details/gtalbdwrum.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtderydwij.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gtwmyozsbx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gttmqmpbzs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtfkfklvud.html

TS:   s.slice(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtlghymokv.html

Java: s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtobxlflht.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hfpthk.cn/Article/details/gttcoxuocg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.smart0.xyz/Article/details/gtxdeqamqm.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gtjreodmow.html

[E04] 查找子串位置
来源：http://dali.yj20258888.top/Article/details/gtcmzvqukn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtkgdcwbgk.html

PHP:  strpos($s, "x");
来源：http://dali.birdmap.top/Article/details/gtuypgnunl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.kuanghao11.cn/Article/details/gtomdsbess.html

TS:   s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtjzxirumr.html

Java: s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gthmomahmg.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gtcljhefnl.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gtdiplvqts.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtmczwxkgr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gttsvhkcfu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtwscpeklg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daxiang520.top/Article/details/gtyqctakdu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcnflmpx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgfzy.top/Article/details/gtzwndvpig.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtabrdjvns.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gtgbzpslap.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gtgdbnitrw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtzzpgwpvk.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gtwqtfrldv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtkryfmzmu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gtytrylmei.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtfmuxommq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtggbalfsn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtthmnbdbq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtofgbwxay.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yonumen.top/Article/details/gthmxfbuyi.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtpapjzqny.html

[E07] 按分隔符拆分
来源：http://dali.sweek.top/Article/details/gtnddsvurf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258888.top/Article/details/gtkrhspgyl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtayaqoemn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yangfankeji.com/Article/details/gtfucgzqou.html

TS:   s.split(",")
来源：http://dali.meibo888.top/Article/details/gtepqglfxo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cdnleiting.top/Article/details/gtjbtnzghp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gtsvphvbec.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gtwjuujapa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.haohaochexian.top/Article/details/gtgehbpbcf.html

[E08] 数组按分隔符合并
来源：http://dali.gotoacloud.top/Article/details/gtpdubzlwo.html

Py:   ",".join(items)
来源：http://dali.smart0.xyz/Article/details/gtuhtwswdo.html

PHP:  implode(",", $items);
来源：http://dali.pengpengdd.cyou/Article/details/gtdljnkggj.html

JS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtpbwgrzzf.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtinkhbjkq.html

Java: String.join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtaywfznna.html

Go:   strings.Join(items, ",")
来源：http://dali.hfpthk.cn/Article/details/gtsjcrxmwh.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gtudhsreok.html

C#:   string.Join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtuvpeoquo.html

[E09] 去除所有空白字符
来源：http://dali.yj202588.top/Article/details/gtdelbolkp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj202588.top/Article/details/gtcukzesgk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ppjwa.cn/Article/details/gtttxqphxa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtyczyfctx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhqnlodl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtqdenxpkp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xziqi.cn/Article/details/gtayswoxhl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sweek.top/Article/details/gtfitswtly.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gtgyillbev.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnxiangtu.top/Article/details/gtvjixkswv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tanke756.top/Article/details/gttynynrxx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gtmnaeztue.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtsmndcgoc.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtamlwpgxk.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtzuitptqa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gttwjhyvqo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtvszlygyt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.havefunace.top/Article/details/gttrrujiff.html

[E11] 反转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtvkmjcrjq.html

Py:   s[::-1]
来源：http://dali.sxryk.cn/Article/details/gtqoqbvqkp.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gtdyfvlqkz.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtrkvamqli.html

TS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtsnaecfeu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gtvyolevvh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gtofsipdxo.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gtbgqhqltz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtxamxyjqg.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gtohaxmuuy.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvutuglzp.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gthtyhpaqx.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gthdyidhev.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gthdffbrwi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ppjwa.cn/Article/details/gtferstkfx.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gtqihhmqok.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtqxykzquq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gtmvowsrmk.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gtsymwtmun.html

Py:   for ch in s: print(ch)
来源：http://dali.xuanzx.com/Article/details/gtisfqbxtw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.9152youxi.cn/Article/details/gtzsudyspq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtqcdriygh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtfycrzkyl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gtlgmjckam.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gtfqzhdkzi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aizwys.cn/Article/details/gtcygquxdw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ydzc1.top/Article/details/gterhmvvut.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtpueerdww.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gtrolfwmlc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtwitbgrnn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xziqi.cn/Article/details/gtbsuuxmny.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gtvezwupxl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtnrpfzgcb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gtkeqpezzo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aizwys.cn/Article/details/gtnkeqpxyk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtdbtytjju.html

[E15] HTML 转义 / 反转义
来源：http://dali.vqdsnc.cn/Article/details/gtkqimcuwj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gtfyhzgsth.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gttmyndafb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gtvazrgnih.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gtvnllkscp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258888.top/Article/details/gtnemzuigi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gtwipesuej.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shangyingyoupin.top/Article/details/gthxzvpikc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gtnfprxpde.html

[E16] 数字千分位
来源：http://dali.daria6918.cn/Article/details/gtbnywtmrk.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gtsedodeck.html

PHP:  number_format(1234567);
来源：http://dali.yj20258888.top/Article/details/gttiyuxmcc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gthruuqmtm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtbvbgrctf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtxvasejts.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xylfe.cn/Article/details/gtrphbfbxd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gthebtvpuu.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gtvhyghplm.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gtxvyphups.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gtiqblzlch.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gtpogfkpur.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gttymkkqyj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtrecwqnjn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jyoumei.cn/Article/details/gtwgebrccl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gtemekmzqk.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqoiwdnx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gtflabejlc.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gtlnkaddan.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gtykjbafhd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gtoantlxnc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtjgcsjybc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtbegsyxkb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtkgmvbewu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtgdtjnaij.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gtcuzgynwk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtzebogqtc.html

[E19] 多行文本按行拆分
来源：http://dali.gaohongyu789.top/Article/details/gtsyhltoly.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gtbgokyjyy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtxzoxnzym.html

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtndnuxltf.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtafzubrti.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gtotwhvzam.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtkbqpstbm.html

Ruby: s.lines
来源：http://dali.andypj.xyz/Article/details/gtohrugcwj.html

C#:   s.Split('\n')
来源：http://dali.yueranfly.top/Article/details/gtjqsueiim.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gtjsmsnmqm.html

Py:   if not s:
来源：http://dali.xinyue.icu/Article/details/gtxnggxlyx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtfucfsykv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gtipctnehp.html

TS:   if (s === "") {}
来源：http://dali.hammf.cn/Article/details/gtsjytcbjk.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtmhmlwlfo.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gtwyoxeywz.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gteuwlyuxv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtwdidwfls.html

[E21] 超长截断加省略号
来源：http://dali.xziqi.cn/Article/details/gtzrpglymu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeosmpzy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtekchnjic.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpyppgba.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtnhumexbh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtnrpmfrlq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gthpvweukl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtndijxyyh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtdyxqbhmn.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gtvprmeryy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gthykrwwur.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtlotsrwbd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtrmprmrxk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtkzhybrzx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtkimecmau.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guannengcc.top/Article/details/gtypcwupsa.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtjkqpxllt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtpicuufpm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtzrrahbga.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtsezxgdyj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzwqpdxln.html


<!-- 参考信息 -->