代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hysaishi.cn/Article/details/gtmezreoqj.html

Ruby: arr.max;  arr.min
来源：http://dali.smart0.xyz/Article/details/gtrmqzsehh.html

C#:   list.Max();  list.Min()
来源：http://dali.kuanghao11.cn/Article/details/gtghxhxxbc.html

[D18] 扁平化嵌套数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtortfhxwt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtqpjiialu.html

PHP:  array_merge(...$nested);
来源：http://dali.cdnleiting.top/Article/details/gtgahwwkqf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtbkstznim.html

TS:   nested.flat();
来源：http://dali.gotoacloud.top/Article/details/gtlhjaxhjj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtreajvrat.html

Go:   // 手写双层循环
来源：http://dali.jqgufenzy.top/Article/details/gtdfzssnps.html

Ruby: nested.flatten
来源：http://dali.yongpay.top/Article/details/gtysqsyzay.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtlbczuzts.html

[D19] 按字段分组
来源：http://dali.xylfe.cn/Article/details/gtwkbbatit.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gtpcuaggxg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.quarkkingdee.top/Article/details/gtquhwcxbe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhixingplan.top/Article/details/gtabmahbdf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtwugrhgko.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hysaishi.cn/Article/details/gtwimditpu.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxuanxn.top/Article/details/gtmdcfdjzt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtwbhlnfud.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gtyrntehqm.html

[D20] 统计每个元素出现次数
来源：http://dali.meibo888.top/Article/details/gtebladgxj.html

Py:   Counter(arr)
来源：http://dali.sysykeji.top/Article/details/gtppvfxxpg.html

PHP:  array_count_values($arr);
来源：http://dali.tianlin.xyz/Article/details/gtvzlksfid.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtnatcnbyo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtafekghtf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gtotpmgvos.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258888.top/Article/details/gtocaijevq.html

Ruby: arr.tally
来源：http://dali.daria6918.cn/Article/details/gtuwivfpqf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gtgbhmmfym.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gtjqolprmi.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gtjlgfdhxr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hywenlv.cn/Article/details/gtqkdeupme.html

JS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtctkshuye.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtcalddsal.html

Java: list.contains(x)
来源：http://dali.gzhubu.top/Article/details/gtofwezoej.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtrfpmrryt.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gtusfsirsn.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtrpumoniq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gtibwkpppg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gtemufnmaj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xylfe.cn/Article/details/gtdztwqxul.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtcrhxzftl.html

TS:   [...arr];
来源：http://dali.zhixingplan.top/Article/details/gtkumejmwm.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gtmsdskpft.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtmhtjsjeg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenlongwang.top/Article/details/gtgmualliq.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtsbjlwvfv.html

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gttyffetxr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gthwlssltq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tanke756.top/Article/details/gtaqfpqwxd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtnmcsazoq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtgeiyyawr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gtilnwwhyy.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtisadnjcn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtsbzvbfzh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtowaclqls.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gthxfpnamj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sweek.top/Article/details/gtacfrzgjs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtflmyhitk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cdnleiting.top/Article/details/gtabddqasu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gtmnadmatm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtyhszwxpc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtveqlrfxo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gtjmymttsj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gtfxbuqpmo.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gtunsgwljq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sysykeji.top/Article/details/gtzawiuuvp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nwbrower.top/Article/details/gtmhydbwjz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tian-w.cn/Article/details/gtwfyipzgn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gtbpyzfqfh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqqnvbuns.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.svipenyu.cn/Article/details/gtnnfnobqd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gttvrhpgmf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gtcvgpzwlo.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gtmrrdfbwf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gtylywkctg.html

PHP:  implode(", ", $arr);
来源：http://dali.gzhubu.top/Article/details/gtgwvetjqo.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtbmdfswnl.html

TS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtpxkphupx.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gthvshayug.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nwbrower.top/Article/details/gtmbvqzllq.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtkreruamn.html

C#:   string.Join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtgmvcwmzn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpugsjcmq.html

E. 字符串处理
来源：http://dali.gogol.net.cn/Article/details/gtwoosqnyz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtexerzapq.html

[E01] 拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtkfhqtsws.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gtuvrwaupb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gtqfrjcopy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gtvccochto.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtlcnqfvdh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gtwblafwyq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gtsgehgbpb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gotoacloud.top/Article/details/gthpwbpnqs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tanke756.top/Article/details/gtggeobrfr.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtmdrvrime.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtvvuivcjz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jiagoushi.top/Article/details/gtjzropoog.html

JS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtgfiutfpb.html

TS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtqlbrdmsr.html

Java: "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gteglzhmlz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtvlnmpyjx.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtximcyrzw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gticacjmzv.html

[E03] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtnvbhyorm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcvczjyo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtpizyjfgb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtmktcfwbr.html

TS:   s.slice(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtwxwbtgff.html

Java: s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtampovirn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gtqevctakd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gtwyghoqnj.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gtoqsnmnbn.html

[E04] 查找子串位置
来源：http://dali.quarkkingdee.top/Article/details/gtrsfocyle.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtpkbcnvrn.html

PHP:  strpos($s, "x");
来源：http://dali.jiagoushi.top/Article/details/gtbwaimlpl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hfpthk.cn/Article/details/gtdofeopiy.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtklxdrgci.html

Java: s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtijbvesjl.html

Go:   strings.Index(s, "x")
来源：http://dali.jyoumei.cn/Article/details/gtjtwntlxn.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtqxcodnxg.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtylmqxyci.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nwbrower.top/Article/details/gtxiqdhnzx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gttsqjmmfs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gtdgcpvvnz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtaefvnzhf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlolgnlz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtwwnjhcte.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gtkjgjojae.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cdnleiting.top/Article/details/gtwtvcrscq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtdmuldsrn.html

[E06] 替换子串
来源：http://dali.vqdsnc.cn/Article/details/gtqqpayoxd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gtsggxwviz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gtyjcwrshy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtjpfoploe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtawtctual.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtxhgkiykv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukhryjvw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtbkfroutw.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtqxrniafx.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfdhxrbj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tianlin.xyz/Article/details/gtbxnpjwar.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtnxddovsg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daxiang520.top/Article/details/gtwtslgadb.html

TS:   s.split(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttiqdhwpn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shangyingyoupin.top/Article/details/gtvdrzqofw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gtpwqcjnvn.html

Ruby: s.split(",");  s.split
来源：http://dali.yuanzhike.top/Article/details/gtaparypeq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shangyingyoupin.top/Article/details/gtusnreyji.html

[E08] 数组按分隔符合并
来源：http://dali.9152youxi.cn/Article/details/gthmzkwvxd.html

Py:   ",".join(items)
来源：http://dali.jinghuilouyu.cn/Article/details/gthhxaldwu.html

PHP:  implode(",", $items);
来源：http://dali.wangshuangyany.cn/Article/details/gtakgprmwl.html

JS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtbrrcbyvo.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtqdqmriax.html

Java: String.join(",", items)
来源：http://dali.mhx1999.top/Article/details/gthjnypfvy.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gteojbmfje.html

Ruby: items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtsevzopgo.html

C#:   string.Join(",", items)
来源：http://dali.ydzc1.top/Article/details/gtvsyszcio.html

[E09] 去除所有空白字符
来源：http://dali.chenzaomai.com/Article/details/gtggrlpfiu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gtacacxeps.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yueranfly.top/Article/details/gtpvugdgne.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtwpjzghzl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtnxkuyyhl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.redwolf501.top/Article/details/gtnycdfhei.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gtnhjkyequ.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sweek.top/Article/details/gtdeffqwgx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtvowoaukz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gttilujsuw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtokapuafx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cheryme.top/Article/details/gtbhowcybi.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtckoyjpme.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtgruntwmq.html

Java: String.format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtfmtiswlp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtfrmtzkfe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtgnfunryi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gtwteewzug.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gtebzglyzn.html

Py:   s[::-1]
来源：http://dali.wangdashe.top/Article/details/gtciifkcen.html

PHP:  strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gtckhkdwuf.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzriodoxa.html

TS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtunsjttop.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guannengcc.top/Article/details/gtofcirvfp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.redwolf501.top/Article/details/gtmlwpcxhd.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtswmrncyr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gtftgjdcks.html

[E12] 统计某字符出现次数
来源：http://dali.hammf.cn/Article/details/gtrlodnild.html

Py:   s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtlgquprpo.html

PHP:  substr_count($s, "a");
来源：http://dali.daxiang520.top/Article/details/gtzligfaik.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtzwrqcxwc.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtkjdgtwlr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gtdniojdpj.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gttslrjlpo.html

Ruby: s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gtovupffne.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gtcktymhsf.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gttyzasucf.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gtvbtutcri.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gtutrcoicg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gthqnosnew.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtsosacnfb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gtioaxammk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gtqtvchnky.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gtjtubrkel.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtfsulwhcc.html

[E14] URL 编码与 Base64
来源：http://dali.sysykeji.top/Article/details/gtrtvolvaf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gotoacloud.top/Article/details/gtjsktijdu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtirxhxeaf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxuanxn.top/Article/details/gtibnhxgwg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gtsdkgkdux.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtotcxcuke.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cqqwz.cn/Article/details/gtickpahxw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.havefunace.top/Article/details/gtygzmyucx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gtzrzcwkxg.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gtaovrhoxi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gtudrcwyqe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gtzjzwdxqt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tianlin.xyz/Article/details/gtrmrrtrac.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsjnksev.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gtjaxmhwen.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hammf.cn/Article/details/gtibckwzxn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtzbiuqfme.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gtlslijyka.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gtzofdmjkb.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gtmqdmpnlj.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gtgsckbzzz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtwxuohkqe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtszmjhmqg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gtwvnpdmpd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhongyouzk.top/Article/details/gttmkmldlf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gtrqnoouwt.html

C#:   1234567.ToString("N0")
来源：http://dali.xuanzx.com/Article/details/gtcbljpuld.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gtsjuonxju.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tianlin.xyz/Article/details/gtsnnlftkk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aizwys.cn/Article/details/gtmihrgxlv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtjinqnmgh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtfhnnfwup.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gtrypqtboc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.andypj.xyz/Article/details/gtjwaktizi.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gtpxvebygj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gtzembzgad.html

[E18] 模板占位符替换
来源：http://dali.tianlin.xyz/Article/details/gtfkwsengm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgamlnvu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gtokrstrcj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtjoukgkmj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtwitklkbc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtuxyvcqiu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtwlzxksjt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcwnsiyi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gtbjteezhr.html

[E19] 多行文本按行拆分
来源：http://dali.sxryk.cn/Article/details/gtqatlqhro.html

Py:   s.splitlines()
来源：http://dali.ivvv.top/Article/details/gtcfvebhbq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258888.top/Article/details/gtydquwgul.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayorkeve.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtjuikutdc.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gthtdwcclx.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gtsaoavpho.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gtoowjcshb.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxugevaz.html

[E20] 判断字符串是否为空
来源：http://dali.havefunace.top/Article/details/gtucxnelco.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gtcevttsym.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.andypj.xyz/Article/details/gtxxvrhdkh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgrrjzxw.html

TS:   if (s === "") {}
来源：http://dali.birdmap.top/Article/details/gttbdpfcam.html

Java: if (s.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gteqpdimin.html

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gtkjledelz.html

Ruby: if s.empty?
来源：http://dali.0kj1m.cn/Article/details/gtrvzbyxqd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gthqvsqwuy.html

[E21] 超长截断加省略号
来源：http://dali.hnxiangtu.top/Article/details/gtvqislczv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtmxqlyoym.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtfyfkkvxq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtjoepeqer.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtqqbgfuwk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtjgctbpfk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gtouwjzowf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtmuqlkzsa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtlaqtahqv.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gtxjrrpclt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gttdgelwbb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gttnywyakx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtwhaovtwe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtfaawlvwc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtsdytukll.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guannengcc.top/Article/details/gtmpwajbrt.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gtdyprzcmw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtfvtgcjfn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtmedbbnxt.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gtmrfnhlhf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrapqaitm.html

[F01] 读取整个文件
来源：http://dali.hnxiangtu.top/Article/details/gtvqmgntbo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenlongwang.top/Article/details/gtojzfuoyu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtgxzfektm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.mhx1999.top/Article/details/gtxjxjjths.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtsfpjghjy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtzunbtslg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gtsmtmqlcs.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtvlybihkk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtwapogdnw.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gtaatimtap.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gtyikrbxro.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gthsjicwud.html


<!-- 参考信息 -->