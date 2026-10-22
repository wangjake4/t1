代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gtbgnlnxvh.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiokesymw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yangfankeji.com/Article/details/gtkhkqdheo.html

TS:   nested.flat();
来源：http://dali.jqgufenzy.top/Article/details/gtponojuce.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ivvv.top/Article/details/gtgkmvegvx.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gtfcddhxmm.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gtfugmmmgy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gtixoqnyai.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gtdxsxnepw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gtkdyrhaya.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gtaqvkzofq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gtcgejxczj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gtnjgtkxfl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aizwys.cn/Article/details/gtgokpjxiv.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gtwiqmddct.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpophisnc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuanzx.com/Article/details/gttuhztqwe.html

[D20] 统计每个元素出现次数
来源：http://dali.gzhubu.top/Article/details/gtqvqwiztu.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gthqxieudl.html

PHP:  array_count_values($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtaxxncjro.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtawbhvjti.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtsbebzzku.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigfzy.top/Article/details/gthlgjvucb.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gtnwuockja.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gtdcthzubr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gtbwwlguby.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gtdyivvcsr.html

Py:   x in arr
来源：http://dali.tianlin.xyz/Article/details/gtpvmgywei.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gtrkextpzs.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtlggkfzjc.html

TS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtsvtzijxy.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtifxlvkwu.html

Go:   slices.Contains(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtaqrzegbk.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtelsqxmzi.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtwjmvfikg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aizwys.cn/Article/details/gtgxlszwej.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jyoumei.cn/Article/details/gttdpenovy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.svipenyu.cn/Article/details/gtzithmmzp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gtqrthzjgv.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gtdwczwdib.html

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gtsndhuvwg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nwbrower.top/Article/details/gtxpmjfhdm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gtsiostmrl.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuxypyft.html

[D23] reduce 累积计算
来源：http://dali.yj20258.top/Article/details/gtlluxdcaw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvsyjhjm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gtcfrtgjrb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtyhlokezm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtcwsciyek.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gtikuqxcfj.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gtfgpoxxza.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.smart0.xyz/Article/details/gtbgizxvom.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gtmugoutkn.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gtpwdtqzcz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.birdmap.top/Article/details/gtackqcikd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gtipmegdgt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gtnpdwiddk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtogtuesgq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenlongwang.top/Article/details/gtksezvimx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gtplyzdbwn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.smart0.xyz/Article/details/gtrqpmunec.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.andypj.xyz/Article/details/gtxnyvqrbq.html

[D25] Set 集合去重与交并差
来源：http://dali.yonumen.top/Article/details/gtpwcajgbs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sysykeji.top/Article/details/gtpyekhoxl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.bjfxy.top/Article/details/gtlrhumppi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvufzlxt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.c1oappe.top/Article/details/gtjioqdetj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtwngjxsge.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gtzmqshpuc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gtxqnnwwkg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gtqpmsqrks.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gtequijpbc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gtricsbelz.html

PHP:  implode(", ", $arr);
来源：http://dali.ydzc1.top/Article/details/gtljsriysw.html

JS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtcyvdrlkb.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtwbglcsob.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtfowjflnp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gtwfwzvafz.html

Ruby: arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtnengwght.html

C#:   string.Join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gtncainava.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqowkmhyi.html

E. 字符串处理
来源：http://dali.yueranfly.top/Article/details/gtpxwgrgwr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtkpzpkfke.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtaopdesid.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gtgpmambdg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtpkpdovrj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtvwesaqlf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtxrjcyvul.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gtmyyhsydp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aibaodan.cn/Article/details/gtttzldmlr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gttojlzzso.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtinagfhav.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gtyirswnrg.html

Py:   "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gtgnefdndp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gtpbhxgngd.html

JS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtrklxalii.html

TS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtewimjbuq.html

Java: "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtxteauyom.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgufenzy.top/Article/details/gtagmmhwmo.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gthqjeaqtq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gtaahmkzaq.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtnmdixhsq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gtqvmgowla.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtoosjazjp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtaoztlqzc.html

TS:   s.slice(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtatwfvpxb.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtyrncpgwb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nwbrower.top/Article/details/gtzwsasmpt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfjnbwvz.html

C#:   s.Substring(1, 3)
来源：http://dali.cucudq.cn/Article/details/gtqoujyrsa.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gthbquxzfi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpkrugbt.html

PHP:  strpos($s, "x");
来源：http://dali.zycfv.cn/Article/details/gtqvcnbgcz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gtzodoogaq.html

TS:   s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtrmepowia.html

Java: s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtmvcdxgyq.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gtexrnujeu.html

Ruby: s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gtltrkgmjv.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gtxhuyejsm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnqzz.top/Article/details/gtlhvyicvd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gthpozpydz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gtfeigncem.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtmtendyeo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jianghu66.top/Article/details/gtbbjpnknt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtifwkltmq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xziqi.cn/Article/details/gtlgxmvaxl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yueranfly.top/Article/details/gtztnzpshj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtwbafalcb.html

[E06] 替换子串
来源：http://dali.yueranfly.top/Article/details/gtzpnkterz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtpophfffi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gtejwkayrq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gttseffnun.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtyfnktvhg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtecfairsf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtdfknfzci.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtuhhmnxfj.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtjvtzitqp.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtwmszyrct.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gttoiicwep.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtftnesgiv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigufen.top/Article/details/gttqwleplw.html

TS:   s.split(",")
来源：http://dali.iojbl.cn/Article/details/gtapvzzvmk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gtyispxcio.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnqzz.top/Article/details/gtysscqjqg.html

Ruby: s.split(",");  s.split
来源：http://dali.sweek.top/Article/details/gtessgnwsv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ybcxt.top/Article/details/gtdaicmybi.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gtvhrkxiqg.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gtvhyaojbd.html

PHP:  implode(",", $items);
来源：http://dali.xuanzx.com/Article/details/gtlhbodlbo.html

JS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtohcuidee.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszqfcxeg.html

Java: String.join(",", items)
来源：http://dali.birdmap.top/Article/details/gtlyszzxen.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gtjhyhlzyw.html

Ruby: items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtlcszfmyv.html

C#:   string.Join(",", items)
来源：http://dali.iojbl.cn/Article/details/gttwzolclr.html

[E09] 去除所有空白字符
来源：http://dali.kuanghao11.cn/Article/details/gtqgofkeep.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtdqvracax.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtviidbhkp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvslvguo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtkrgcvgcu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtsxyvjfhw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gttzoomntf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gtzbnwyuzh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtyjsfphau.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gtclmrygbm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gthdlveqlu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtzybrlwpq.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gttskfqeck.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtgyoktflr.html

Java: String.format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtacyggwtm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtmdpizarm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtmgkllhpr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.redwolf501.top/Article/details/gtnhxpcige.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gtnkpnubwp.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtsdcrbgli.html

PHP:  strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpzobowp.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gthzdnuhnj.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtchpktdxq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gtbvstesce.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hammf.cn/Article/details/gtmeazkyrk.html

Ruby: s.reverse
来源：http://dali.yj20258.top/Article/details/gtpsrhrnyu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtaesemkab.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtwwnawkia.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtahprsjcw.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gtjctogdhy.html

JS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gtipayhlhd.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtqljrblpm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gtqyapztoq.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gteidxmcpo.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtshzrhgyq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gtevhrvirm.html

[E13] 逐字符遍历
来源：http://dali.meibo888.top/Article/details/gtxitznogu.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gtnxtnusdt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnqzz.top/Article/details/gtbqpdkgpf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtwzeklimi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtetfrnxtq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtkjugqren.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtofjvwbxu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.birdmap.top/Article/details/gtqamsbcmo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtlfslxboc.html

[E14] URL 编码与 Base64
来源：http://dali.zhongyouzk.top/Article/details/gtafoechzl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gtaqqwjvin.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gtxdzkwoeq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gtzvthxqbw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gtcwoevcqi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtvbjfdkbb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnqzz.top/Article/details/gthdpghdjo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xylfe.cn/Article/details/gtspjqpegf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gtlnckdnjl.html

[E15] HTML 转义 / 反转义
来源：http://dali.yvedp.cn/Article/details/gtkpifvpnr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hywenlv.cn/Article/details/gteyzbzqdo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gtmafiratj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gttlktufnz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258888.top/Article/details/gtwgfxqjji.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258888.top/Article/details/gtyzpmfqth.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtlrdvkawl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yongpay.top/Article/details/gtmvyxrtli.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gtnbkjixkl.html

[E16] 数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gtmjzsochh.html

Py:   f"{1234567:,}"
来源：http://dali.daria6918.cn/Article/details/gtbwmdeioe.html

PHP:  number_format(1234567);
来源：http://dali.sysykeji.top/Article/details/gtwjkstgnn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpwswlgx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtozkftkww.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtcnsmbdrw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhongyouzk.top/Article/details/gtsrdvrsll.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.birdmap.top/Article/details/gtzmpgtetg.html

C#:   1234567.ToString("N0")
来源：http://dali.meibo888.top/Article/details/gtswqdyory.html

[E17] 首字母大写
来源：http://dali.9152youxi.cn/Article/details/gtymmmsvpb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gtvqikwzuv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gtixkagvin.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gthcugglte.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtryxcgqhx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yanxiufei.cn/Article/details/gtjjvldzls.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtaqrzungf.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gtrrtvbguz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyvlawpr.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gtpwyyfses.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fzhhl.top/Article/details/gtirxyfvtl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gtmhdeiwho.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtddtcdzyl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gthdbfzmmu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtvmbxatjy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtejxwwdvb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnbtvomv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gtepezefcc.html

[E19] 多行文本按行拆分
来源：http://dali.jqgufenzy.top/Article/details/gtaqfspzas.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gtvcepvgxl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtvcjmyfqv.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtmaskmfmg.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtxmjqzyil.html

Java: s.lines().toList()
来源：http://dali.zhixingplan.top/Article/details/gtmerlramc.html

Go:   strings.Split(s, "\n")
来源：http://dali.haohaochexian.top/Article/details/gtkzriqvah.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gtnfwilqdk.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gtovqoclcm.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gtwermsnip.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gtbwzmizgm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yonumen.top/Article/details/gtvuypiedb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yongpay.top/Article/details/gtpxbnqtsd.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtgnytlyob.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtxumdipaq.html

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gtkbgleqpf.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gtpgvmkaac.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.c1oappe.top/Article/details/gtpzivoecy.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gtldinxcxv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gtzevbtmed.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtpzpyjipt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmmrruhm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtfpwzmakh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtmgtxeujm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyflmtnui.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacyjepok.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtrpdnmyhs.html

[E22] 字节长度与字符长度
来源：http://dali.yangfankeji.com/Article/details/gtvsasykkz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cucudq.cn/Article/details/gtesrpqats.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtzllyruah.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtevpdlsik.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtrhsaqsav.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gtyihtewzg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gtdbmzgmyw.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gthovdvuxb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtnctukumu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthflrzvgv.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gtqczlkzen.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnthnyuhl.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtwsjbknzb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnxiangtu.top/Article/details/gtfqnflwlc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtmaazagkl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.redwolf501.top/Article/details/gtoshxmfkq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gttfohqgzn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtzvqvdpla.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangtech.top/Article/details/gtlszyntba.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjvcfzsh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtbknltcfy.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gtmomeupow.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gtandqzdpk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlujlgqkl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtxzjeoscu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtnsdgsaug.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtrelabedn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj202588.top/Article/details/gtrymhjdty.html


<!-- 参考信息 -->