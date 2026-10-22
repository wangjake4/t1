代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gt2dtmdwxev.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gt2fyzokdvn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuanzhike.top/Article/details/gt2ugzquymu.html

TS:   nested.flat();
来源：http://dali.jqgufenzy.top/Article/details/gt2xgevbdwj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2rlpfnzqb.html

Go:   // 手写双层循环
来源：http://dali.tanke756.top/Article/details/gt2tybsirik.html

Ruby: nested.flatten
来源：http://dali.zhengqikj.top/Article/details/gt2palrqjjs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2hyrhmlec.html

[D19] 按字段分组
来源：http://dali.hammf.cn/Article/details/gt2uzdulysz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gt2hpbfgxqz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gt2ytswdvzs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gt2zkwnzlvq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gt2jrngagmd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gt2vigkciha.html

Go:   // 手写 map[string][]T
来源：http://dali.quarkkingdee.top/Article/details/gt2wpkkpnkw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnqzz.top/Article/details/gt2dogedurk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gt2isulvifi.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gt2ogmfinve.html

Py:   Counter(arr)
来源：http://dali.smart0.xyz/Article/details/gt2ljxzymjq.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycbuqqyc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gt2uippdwfe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gt2wdyngawy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.iojbl.cn/Article/details/gt2jxeeccqo.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gt2ouqhfrpb.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gt2sktypzek.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gt2yvjhwavn.html

[D21] 判断是否包含某元素
来源：http://dali.316326.xyz/Article/details/gt2xgutkshh.html

Py:   x in arr
来源：http://dali.cashguo.top/Article/details/gt2kyyfppae.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2nzgjhpge.html

JS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hiqlerlk.html

TS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2vogrodvp.html

Java: list.contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2tfrkkzfc.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2zfavxmft.html

Ruby: arr.include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zkdpbnzi.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2solgpogc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.smart0.xyz/Article/details/gt2dmizawma.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2mupkljjr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cucudq.cn/Article/details/gt2vzrveggt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.birdmap.top/Article/details/gt2ggenknnk.html

TS:   [...arr];
来源：http://dali.jiagoushi.top/Article/details/gt2efkanats.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gt2imwvqxgu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gt2bwcvctyj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azcfleei.html

C#:   new List<int>(list);
来源：http://dali.havefunace.top/Article/details/gt2abndozpv.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gt2ojxxidhr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fzhhl.top/Article/details/gt2xfqtbmqg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gt2hmfuwxkd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gt2emhfsvup.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gt2iekkyxzl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yongpay.top/Article/details/gt2xjxukogm.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gt2wekkjknj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gt2pbrqjyvr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ywwbejzk.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigfzy.top/Article/details/gt2qtscdfgz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gt2plnsohzp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhuzwhvq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guowangkeji.top/Article/details/gt2trogavnt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2zvkxabyi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuxming.cn/Article/details/gt2wkcjgmbr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gt2ugubscio.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hfpthk.cn/Article/details/gt2xkmmwdsw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daria6918.cn/Article/details/gt2zimiuniw.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gt2yppkjzwd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnxiangtu.top/Article/details/gt2cyehvewe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xinyue.icu/Article/details/gt2bxduacze.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vpwbtgdm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gt2hiqhqeyi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258888.top/Article/details/gt2xfohtawr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gt2ijkchljs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2syelzqqa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aibaodan.cn/Article/details/gt2yhtyvdti.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gt2ssycbmdj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.meibo888.top/Article/details/gt2duabmags.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2njfodyyv.html

JS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zybsfmrp.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2stikxnil.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2tpdpzfid.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gt2pyiiewjr.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gt2jioennla.html

C#:   string.Join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gt2rbdwndlf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2oqfshzji.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gt2poogkjxq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2aizrvfxw.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2hmoqkhfg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2giyatvtp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cucudq.cn/Article/details/gt2uivoizox.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gt2ihyhsgxz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gt2rwjnyuvi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gt2caijzplq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2puwhcfrv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gt2sknlepue.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqirpqpr.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gt2najrqtdg.html

Py:   "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gt2nddnllgm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aizwys.cn/Article/details/gt2fioltnil.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2mjhjxvtw.html

TS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gt2jzdetlvu.html

Java: "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gt2lbvmspjk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbrzdaei.html

Ruby: "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gt2pjevfvhb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gt2esumnotz.html

[E03] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gt2bgprtqzx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gt2lqgnrllh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2abfjjnth.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2ldpvuwwc.html

TS:   s.slice(1, 4)
来源：http://dali.yonumen.top/Article/details/gt2vaiejogp.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2lsqtzuhg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gt2kgprheuq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gt2diaztfym.html

C#:   s.Substring(1, 3)
来源：http://dali.hnqzz.top/Article/details/gt2ipfljqfr.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gt2vearmnaw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2myzjpyzb.html

PHP:  strpos($s, "x");
来源：http://dali.nwbrower.top/Article/details/gt2tunjnadd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.havefunace.top/Article/details/gt2mgvjajwf.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2dycknprk.html

Java: s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gt2gmvdhyvc.html

Go:   strings.Index(s, "x")
来源：http://dali.cqqwz.cn/Article/details/gt2fhwxxpal.html

Ruby: s.index("x")
来源：http://dali.shuidangran.top/Article/details/gt2cdwjcxfg.html

C#:   s.IndexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2nlsvkffx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gt2lekqrych.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cheryme.top/Article/details/gt2gzijpsdz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shuidangran.top/Article/details/gt2kexpcmhc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gt2naoykcbb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuanzhike.top/Article/details/gt2shsntjqa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2afkmdacr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jlsjyb.cn/Article/details/gt2pqurwmkv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gt2dmakkqjq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cheryme.top/Article/details/gt2xqudihsl.html

[E06] 替换子串
来源：http://dali.redwolf501.top/Article/details/gt2kmaockmz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gt2kspumqal.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gt2bccpctvn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2onnmviqi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ehuvxtiz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbazkyqk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqcuhwyq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2qhusyugj.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2suvaqcrz.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gt2xetoixmd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ivvv.top/Article/details/gt2plwkulqm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2imlykncu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2oijudqik.html

TS:   s.split(",")
来源：http://dali.0kj1m.cn/Article/details/gt2qtwtobtk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenlongwang.top/Article/details/gt2aoosefcp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2sylabroy.html

Ruby: s.split(",");  s.split
来源：http://dali.zhixingplan.top/Article/details/gt2xsdyarbg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cucudq.cn/Article/details/gt2hpjiqouu.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gt2qpjpnjap.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gt2mxajleni.html

PHP:  implode(",", $items);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdybiffd.html

JS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gt2cxwdwhqk.html

TS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2putckxvi.html

Java: String.join(",", items)
来源：http://dali.fengsongda.top/Article/details/gt2acgfsfjp.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gt2vdtwtwoy.html

Ruby: items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2yiwbhhse.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gt2wthyseby.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gt2thbkdpmi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlrttizy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.smart0.xyz/Article/details/gt2egofnyln.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqjjdnna.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwdvqvgz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daxiang520.top/Article/details/gt2qssuvzdz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ehwqpu.com/Article/details/gt2wejgkszu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.haohaochexian.top/Article/details/gt2kgafjjee.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nwbrower.top/Article/details/gt2kshhjhgt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgufenzy.top/Article/details/gt2ewwvfijj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2evhvmgof.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fttvtwot.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2koqyvown.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2vtvrcxqb.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gt2vplnnynq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gt2nacxxlzy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2rlivqzro.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gt2djmcuxos.html

[E11] 反转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2xhhwjloq.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gt2tixgemyr.html

PHP:  strrev($s);
来源：http://dali.yvedp.cn/Article/details/gt2rzlqxmyu.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2aphghpiw.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2ptnfdbsy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gt2jtsapijy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gt2vkxzudmu.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2eyvnlefj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gt2zfcdbaxk.html

[E12] 统计某字符出现次数
来源：http://dali.hammf.cn/Article/details/gt2pccrwnxz.html

Py:   s.count("a")
来源：http://dali.shuidangran.top/Article/details/gt2ziehmipg.html

PHP:  substr_count($s, "a");
来源：http://dali.ybcxt.top/Article/details/gt2ryvnjpjc.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gt2wrvuzzjj.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gt2twoxrmtq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.havefunace.top/Article/details/gt2lffbwqnb.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gt2vutplggu.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gt2hscosrdz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ybcxt.top/Article/details/gt2trjyrsff.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gt2zkpwwavs.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gt2qqbwibxu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.andypj.xyz/Article/details/gt2qxvkekra.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gt2pqjmjnid.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gt2olrydkgj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2olirdoua.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gt2xeprjtgl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fengsongda.top/Article/details/gt2tqzlebnv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2znlqepdd.html

[E14] URL 编码与 Base64
来源：http://dali.haohaochexian.top/Article/details/gt2wqfvdxzj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nalsevig.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gt2jgscddkz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.meibo888.top/Article/details/gt2vebgianc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.9152youxi.cn/Article/details/gt2qpgtnkaz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhyqgudb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jyoumei.cn/Article/details/gt2vasrocdd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gt2ibcwvdwg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2zwlecofn.html

[E15] HTML 转义 / 反转义
来源：http://dali.tian-w.cn/Article/details/gt2frklesni.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqlfndfr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gt2vzklxpwm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangdashe.top/Article/details/gt2flsjomdd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shuidangran.top/Article/details/gt2bhahqozd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brybcyjx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sxryk.cn/Article/details/gt2dkajtuof.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gt2zvbxjdba.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gt2cgspfpme.html

[E16] 数字千分位
来源：http://dali.svipenyu.cn/Article/details/gt2yqxckisq.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gt2tgeohadi.html

PHP:  number_format(1234567);
来源：http://dali.xylfe.cn/Article/details/gt2tlilwker.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2rvtfkaci.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gt2jwcbkavh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gt2cmozwboy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.bjfxy.top/Article/details/gt2jsowinhm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gt2zugfkghd.html

C#:   1234567.ToString("N0")
来源：http://dali.daria6918.cn/Article/details/gt2chxtzvwq.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gt2pnvyvybl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cheryme.top/Article/details/gt2sjodpmue.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gt2llkfywtl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gt2znwouaet.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gt2vcgwmxxj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.bjfxy.top/Article/details/gt2qwyohjij.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gt2jmgjronn.html

Ruby: s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gt2yvrniopq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gt2kfjxvyvg.html

[E18] 模板占位符替换
来源：http://dali.shzxlz.cn/Article/details/gt2yrduxypd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gt2skqreved.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gt2fqwmtmzk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2msrpjnto.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2wzaqlzlk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2prhpvbjp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2ugbwimzq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gt2wrqjemix.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hysaishi.cn/Article/details/gt2ymgkdswf.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gt2nwbficzs.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gt2nghfriib.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2dxpcoonl.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gt2hsgckntb.html

TS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gt2vkdqrqrd.html

Java: s.lines().toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2qsgzutxr.html

Go:   strings.Split(s, "\n")
来源：http://dali.tianlin.xyz/Article/details/gt2tvwtptkg.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gt2tazyslgg.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gt2gpepbesi.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gt2krcofpif.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gt2gjmgtqjd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuanzx.com/Article/details/gt2irtevvrv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.smart0.xyz/Article/details/gt2nbqrntzc.html

TS:   if (s === "") {}
来源：http://dali.tanke756.top/Article/details/gt2hnojhiim.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ysatcuzz.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gt2aemsqqve.html

Ruby: if s.empty?
来源：http://dali.yj20258888.top/Article/details/gt2vppreahc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258888.top/Article/details/gt2avyrlojc.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gt2twndgfbx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gt2lhiswmfl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2tpdkbxsm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2czbdzguj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufiyidiz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2hssgnpcr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gt2wyulrody.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2hioislkr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rbmbsoot.html

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gt2pfdszrre.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gt2kncsdvin.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2fvvtebqg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khpcklzz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gt2kafoxqhx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gt2hsglvmkl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nwbrower.top/Article/details/gt2ktuwefpa.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gt2clpumied.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gt2ymbnskpa.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2chfflhcy.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gt2gopdnule.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2kytlbuqz.html

[F01] 读取整个文件
来源：http://dali.shzxlz.cn/Article/details/gt2wcfrqzno.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gt2rkcvlypv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2vduftrzp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.9152youxi.cn/Article/details/gt2wumekepr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gt2rzxorsoo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2zezknipn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gt2kfllwmuy.html

Ruby: File.read("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2anbqdjzm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2twbizymx.html

[F02] 逐行读取文件
来源：http://dali.redwolf501.top/Article/details/gt2bwhsznck.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gt2hcmjrhwj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gt2vkfogptm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2djmrztsa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gt2aolwhlqf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gt2gglrqbfg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.vqdsnc.cn/Article/details/gt2lntcbrfh.html


<!-- 参考信息 -->