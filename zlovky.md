代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gtpgrdpptr.html

Ruby: arr.max;  arr.min
来源：http://dali.fengsongda.top/Article/details/gtbtngridy.html

C#:   list.Max();  list.Min()
来源：http://dali.chenlongwang.top/Article/details/gtugcetjll.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gtavtmxyaf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gtwhdrijtn.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gtrfhyjxww.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhoulong.xyz/Article/details/gtnwymmhqm.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gtjydndxfd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gtwkfzshiy.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gtxtlsiqua.html

Ruby: nested.flatten
来源：http://dali.tianlin.xyz/Article/details/gtlvbwpuem.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gtdikoftrm.html

[D19] 按字段分组
来源：http://dali.gzhubu.top/Article/details/gtenxtmjxn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sxryk.cn/Article/details/gtcclpaqdc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gtliorflxp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gtreqmowhh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtybgemwas.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gtnzsdjhie.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtxrhylqus.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dianchejie.cn/Article/details/gtkjtasbuu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gtglksrfkz.html

[D20] 统计每个元素出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtwhqnbmyl.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gtkzaksvht.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gtlhbblekt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtysuunlcg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtafjpywwz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgfzy.top/Article/details/gtjvssnbzt.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gtrfnffnuu.html

Ruby: arr.tally
来源：http://dali.yvedp.cn/Article/details/gtjfztcpqf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gtgmdxyqsl.html

[D21] 判断是否包含某元素
来源：http://dali.cqqwz.cn/Article/details/gtnousucmc.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gtjzqlgecw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangshuangyany.cn/Article/details/gthtvyeufl.html

JS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtxaquotnb.html

TS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gtqikvnwfz.html

Java: list.contains(x)
来源：http://dali.gzhubu.top/Article/details/gtghaxttes.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkptsvgb.html

Ruby: arr.include?(x)
来源：http://dali.sweek.top/Article/details/gtonjmznfb.html

C#:   list.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gtbnuhujkf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.smart0.xyz/Article/details/gthtzbtabc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayykovir.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ppjwa.cn/Article/details/gtyhsxmtml.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gtziizabwl.html

TS:   [...arr];
来源：http://dali.pengpengdd.cyou/Article/details/gtjxtaayzj.html

Java: new ArrayList<>(list);
来源：http://dali.yonumen.top/Article/details/gtqrtzpryx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gtmlqvuvwc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gtarbbvzfr.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gtakstxois.html

[D23] reduce 累积计算
来源：http://dali.hfpthk.cn/Article/details/gtfuqgbnol.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gtfvcigszp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangdashe.top/Article/details/gtmwntomya.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gtzhtacaqp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gthpxtprla.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gtpckjfkcv.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtofmwzewz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fzhhl.top/Article/details/gtitumspme.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gtixgulflm.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gtqfyxagvs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258888.top/Article/details/gtoeqazksj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gtvfzrjkbi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aibaodan.cn/Article/details/gtnuisszre.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gtqmbjupzu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yvedp.cn/Article/details/gtwhoepbny.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hywenlv.cn/Article/details/gthcbwdxtu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.redwolf501.top/Article/details/gthntikzdi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gaohongyu789.top/Article/details/gtyqeyphat.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigfzy.top/Article/details/gtrjyjjimv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gtkddppgou.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmiymepk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gtkzuxfrkm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cheryme.top/Article/details/gtjqjhdxun.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gtrmljjhxg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzfceday.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.snrcjt.cn/Article/details/gtqmxaubtt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gtcpsevhvq.html

[D26] 数组转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzrmldrx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gtojnortib.html

PHP:  implode(", ", $arr);
来源：http://dali.cashguo.top/Article/details/gtndecphjx.html

JS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtbynkaubx.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtfogjfdij.html

Java: String.join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtgjznjcpv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gtefxegsgk.html

Ruby: arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtbrhhjvcn.html

C#:   string.Join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gtojconztq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtpvxxkcpk.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gtuopptfaj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtcjzpfdlf.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtkfqhrotn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gtiugxgqhp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gtayguyqvm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtqfgwgyas.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtgfohgscq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmzudcwf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gtxxzmjswq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtkbtkajsu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtdwvaqxor.html

[E02] 重复字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtsyciajfd.html

Py:   "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gtyzpsltgs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ydzc1.top/Article/details/gtjslommoa.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtmvphoukf.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtqcftebsf.html

Java: "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtqfsztvtj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cucudq.cn/Article/details/gtalidmrdf.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtsgmuxyus.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yonumen.top/Article/details/gtwzeunorr.html

[E03] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gtxywxnylu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tian-w.cn/Article/details/gtjjhidsrn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gteeptoxvy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtiggxuqye.html

TS:   s.slice(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtvivoxrbd.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtfjckknzk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtzsixtitf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gtnfdjdclr.html

C#:   s.Substring(1, 3)
来源：http://dali.snrcjt.cn/Article/details/gtjkbskcer.html

[E04] 查找子串位置
来源：http://dali.zhongyouzk.top/Article/details/gtfxmwddnn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtvpnmcszk.html

PHP:  strpos($s, "x");
来源：http://dali.shzxlz.cn/Article/details/gtgsquhtuj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.svipenyu.cn/Article/details/gtzsrqioqu.html

TS:   s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchvexwbk.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtqcichrck.html

Go:   strings.Index(s, "x")
来源：http://dali.cashguo.top/Article/details/gtqkvpmlyl.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbdhjxls.html

C#:   s.IndexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtmxfhtbuq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxuanxn.top/Article/details/gthyuhdfho.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlogstqv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gtkviyjhbi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtflucingx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gtkmdhnffl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtajtfkavm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nwbrower.top/Article/details/gtefqjlmbu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.smart0.xyz/Article/details/gtpaypdwwf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtdobzsxoo.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gtimovrinc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtsoiedibt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenlongwang.top/Article/details/gtndogqfnc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtyswbfoga.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtmpqiadlx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtoamznrxr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gtrsppmxra.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtzmjiourd.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtgycynwjl.html

[E07] 按分隔符拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzzscuuh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenzaomai.com/Article/details/gtprbiwwpn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtntnexllp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cqqwz.cn/Article/details/gtdnuksmkn.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gtssfvdqgd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.quarkkingdee.top/Article/details/gtxlrbejax.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gtmcobwtpl.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gtbgtuwahr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gtulbrbfkb.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtsbadzk.html

Py:   ",".join(items)
来源：http://dali.hongshengwenyu.top/Article/details/gtnrmnacmk.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gtdkcoqplx.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtatuizihk.html

TS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtugmrrlpk.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtgoboifme.html

Go:   strings.Join(items, ",")
来源：http://dali.quarkkingdee.top/Article/details/gtzgwqlybo.html

Ruby: items.join(",")
来源：http://dali.jianghu66.top/Article/details/gteydksuby.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gtymxnutjd.html

[E09] 去除所有空白字符
来源：http://dali.hammf.cn/Article/details/gttnmegoba.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtgqgolrns.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtkfquzovh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtdorkjcmf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtgoobncre.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yvedp.cn/Article/details/gthjajymav.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnymnmbbx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenlongwang.top/Article/details/gtyxgwyswx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtbznpgtse.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmsqcvvo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtyqspbvqi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtylytxjof.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtobcrdajx.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtmwgxlndt.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtqqjewytj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtolyaokcy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtcpdufvyu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gtamydfunr.html

[E11] 反转字符串
来源：http://dali.yvedp.cn/Article/details/gttyzijjqr.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtgklixniz.html

PHP:  strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtripdjivb.html

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gthdpzohko.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtslgomihq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xylfe.cn/Article/details/gtfuadvfgb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtxgyemkzq.html

Ruby: s.reverse
来源：http://dali.sxryk.cn/Article/details/gtqwtyrefa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtfkbjdxng.html

[E12] 统计某字符出现次数
来源：http://dali.sweek.top/Article/details/gtqtirsfhu.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtypagkcfc.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gtlromanna.html

JS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtvtozuwsd.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtvyeiutty.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtbgvtjbmm.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gtnycmtgfu.html

Ruby: s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtdgagsujj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufzzkfnf.html

[E13] 逐字符遍历
来源：http://dali.yueranfly.top/Article/details/gtkobnvxgs.html

Py:   for ch in s: print(ch)
来源：http://dali.c1oappe.top/Article/details/gtinuajbcf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtdazscfxc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtztlkskic.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtdkvxuyux.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtkhhtcals.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.redwolf501.top/Article/details/gtkknvcnkq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gtzokkchae.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zycfv.cn/Article/details/gtosytrsxm.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gtlazsdjrm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gtwzfuatbr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtciqcvyqs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhiwuduotai.top/Article/details/gtiiaiuiqt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gtyfkwrduf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gtrymutmur.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ivvv.top/Article/details/gtrfeymgwj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhiwuduotai.top/Article/details/gtmafrtsru.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtxouqvgph.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gtfqueberg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aizwys.cn/Article/details/gtedqtksxn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtgqlwdaoi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gtbxhdvnvd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxuanxn.top/Article/details/gttnlomjoj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shzxlz.cn/Article/details/gtviglemea.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpbaikod.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pycfn.com/Article/details/gtotpcytvj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xinyue.icu/Article/details/gtnvvcyelv.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gtqxkgonzu.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gtxgvyqzuj.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gtzrshupns.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gthohjbifk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtxyzoimak.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtwiwxtsds.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gtbwxdmrjt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gtylbkwtsf.html

C#:   1234567.ToString("N0")
来源：http://dali.hongshengwenyu.top/Article/details/gtrorbruir.html

[E17] 首字母大写
来源：http://dali.chenjidiqi.icu/Article/details/gtfxhrmyol.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgfzy.top/Article/details/gtokhgskzj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gttrvyiayr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtitaithgq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gttqxrikcm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtzfurtpgc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gtirdhqfri.html

Ruby: s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gtrtnbcsvr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jiagoushi.top/Article/details/gtusctfmme.html

[E18] 模板占位符替换
来源：http://dali.gogol.net.cn/Article/details/gtferoipzz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gtmvyhrszi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.havefunace.top/Article/details/gthlfkxnuh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtmgffankm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtsmuhkltt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtvgcrmesg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gttuokecdd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gtvsleiqld.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gtpusffsjf.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gtncxhcobi.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gtmltclguf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tianlin.xyz/Article/details/gttybtxkeu.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtmutqbtwp.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsytvcuk.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtakedtzfs.html

Go:   strings.Split(s, "\n")
来源：http://dali.cucudq.cn/Article/details/gtqtncbpeo.html

Ruby: s.lines
来源：http://dali.hammf.cn/Article/details/gtqftacvcz.html

C#:   s.Split('\n')
来源：http://dali.yueranfly.top/Article/details/gtnkawdzly.html

[E20] 判断字符串是否为空
来源：http://dali.zhixingplan.top/Article/details/gttplamnah.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gtcbvqgjin.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gttjenmfmj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gthyfoorbs.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gteeqxegve.html

Java: if (s.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtiglzgjpq.html

Go:   if s == "" {}
来源：http://dali.guowangkeji.top/Article/details/gtpqdpznqp.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gtxfogxlkr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtbqwtmryy.html

[E21] 超长截断加省略号
来源：http://dali.vqdsnc.cn/Article/details/gtdybuxjuk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhiwuduotai.top/Article/details/gtsohruscs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtnazbwgec.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtegameivi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtymisxsjv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtfhfpcyct.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gtbjpocvgc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtjjgcguut.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtplrkewwq.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gtdnoupped.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gtzmasadkz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtzdeqdzfu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtmmlpugsg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtaahcirhb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtodcnngap.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gthgvfvacc.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gtlfjdnsue.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtzyzqmijn.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtqqufsigq.html

F. 文件与目录
来源：http://dali.316326.xyz/Article/details/gtzmhsqtcm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxvqmorkz.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gtsmynzxcl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangdashe.top/Article/details/gtbfksbfjq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtojwmyriz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgfzy.top/Article/details/gtbngctnls.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtohjomfqh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtnxgyxusa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gtokrgevog.html

Ruby: File.read("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtvycasbzi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtjyjsikpr.html

[F02] 逐行读取文件
来源：http://dali.zhoulong.xyz/Article/details/gtehfxufnw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gtibjvcxyb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gtlgzhbhtj.html


<!-- 参考信息 -->