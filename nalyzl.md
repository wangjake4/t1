代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2ditjsgas.html

Ruby: arr.max;  arr.min
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtpdsnsd.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gt2afrbtbrw.html

[D18] 扁平化嵌套数组
来源：http://dali.gaohongyu789.top/Article/details/gt2ejvdxwbs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuanzhike.top/Article/details/gt2tvuyxqfq.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gt2geohcuoh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gt2rhmfnxty.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yenurmfa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fycjhalw.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gt2xwtxywvc.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gt2nvofjklr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2lksxolcd.html

[D19] 按字段分组
来源：http://dali.yueranfly.top/Article/details/gt2qhbqkrqv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jiagoushi.top/Article/details/gt2bqojorvp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gt2dnyojicw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gt2pnqmdhdo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hfpthk.cn/Article/details/gt2clhgfpoy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gt2zuqgindu.html

Go:   // 手写 map[string][]T
来源：http://dali.xuetiantiany.cn/Article/details/gt2afkdmmuv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aizwys.cn/Article/details/gt2qtkpazbw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gt2scecgozk.html

[D20] 统计每个元素出现次数
来源：http://dali.hysaishi.cn/Article/details/gt2gxmmzjcr.html

Py:   Counter(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2oosgxbmv.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2fzbaavgp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gt2zhdnqppu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gt2qariifdo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gt2zztcsnxr.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcvmxgk.html

Ruby: arr.tally
来源：http://dali.andypj.xyz/Article/details/gt2ggdalkbn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gt2zczrccyt.html

[D21] 判断是否包含某元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzpgdayj.html

Py:   x in arr
来源：http://dali.guannengcc.top/Article/details/gt2tewmrxlj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gt2mgwugbuf.html

JS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gt2mbljjhkm.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hrmlssbu.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2namlnfwh.html

Go:   slices.Contains(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2vwqakclf.html

Ruby: arr.include?(x)
来源：http://dali.bjfxy.top/Article/details/gt2bzmisgux.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2uodnuyct.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gt2mdsignys.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ivvv.top/Article/details/gt2wvojipav.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gt2xwpasxft.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gt2xbdardbu.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gt2smskykzr.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gt2ohszixis.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gt2qpdrlbvf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuanzhike.top/Article/details/gt2mguayuri.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gt2byhtnivi.html

[D23] reduce 累积计算
来源：http://dali.yueranfly.top/Article/details/gt2nkltfyhv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2wmkrfpnx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.birdmap.top/Article/details/gt2dlsgqwyv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckcckvoq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gt2nuyybzeh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gt2nlembkfj.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gt2pnkhxbmw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gt2bmjltcvn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigufen.top/Article/details/gt2czjacxzh.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gt2ibihtaav.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhixingplan.top/Article/details/gt2ntazjcoz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2okecwbof.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2wvohaqco.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2hcycjsmv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gt2kaojjgdf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gt2qgkdtdtd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hfpthk.cn/Article/details/gt2bzdnjmfr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fzhhl.top/Article/details/gt2mplmyqtk.html

[D25] Set 集合去重与交并差
来源：http://dali.aibaodan.cn/Article/details/gt2ipafeues.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gt2uipiaqng.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gt2vyfcoukn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gt2pxdnkpfe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuanzx.com/Article/details/gt2kxvdnxyz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vypvhkud.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gt2fcpbfwgd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yonumen.top/Article/details/gt2brhkvzas.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aibaodan.cn/Article/details/gt2heejxukv.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gt2owejmovt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gt2jezbshrk.html

PHP:  implode(", ", $arr);
来源：http://dali.xuanzx.com/Article/details/gt2otnllwdl.html

JS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gt2mtqecyga.html

TS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2rifjewrp.html

Java: String.join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2llrxuvvr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gt2wdwukqoe.html

Ruby: arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gt2wmiwbcwn.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gt2kvxawlef.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2rbvjahxz.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gt2svgktyas.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ztftqbhw.html

[E01] 拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2xmtqritk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gzhubu.top/Article/details/gt2mdjshort.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gt2fxzvziau.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gt2uvjwapyv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2nsivaums.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gt2safvbrbl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxeotqic.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jyoumei.cn/Article/details/gt2pnifpock.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egokhhvg.html

[E02] 重复字符串
来源：http://dali.yuxming.cn/Article/details/gt2yqbqegpm.html

Py:   "ab" * 3
来源：http://dali.meibo888.top/Article/details/gt2rhhmbmhp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xylfe.cn/Article/details/gt2byczsfsw.html

JS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxrbxcrg.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gt2brzzlhez.html

Java: "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gt2ymgetqvo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwbfwyjf.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gt2zujzgdql.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuanzhike.top/Article/details/gt2eclgroqh.html

[E03] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gt2swdzfikt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gt2qpuslhua.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbfrrhwa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxecugsh.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2cvbzvtvx.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2obkfduhr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hammf.cn/Article/details/gt2jqyivnew.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihavlepx.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2xdemazca.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gt2tsvutkar.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2zkjzlcdo.html

PHP:  strpos($s, "x");
来源：http://dali.tianlin.xyz/Article/details/gt2iflljjdo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ppjwa.cn/Article/details/gt2hmghjhzl.html

TS:   s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gt2orhhijoi.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gt2omvvxbav.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigufen.top/Article/details/gt2nxzjvrya.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gt2prwxwygv.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2vzgiavqb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hammf.cn/Article/details/gt2fyqwwixi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sxryk.cn/Article/details/gt2gpccxtis.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yueranfly.top/Article/details/gt2rexwodhh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2toljzipk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvgsear.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2emekwkoo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gt2yakjbbnl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2oxbxqejc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2ppohuukb.html

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gt2hvjvgnig.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2zwwjdfck.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gt2vpurwedd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2izuftbpq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2hclcweod.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2uzxgpaon.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gt2adpbyjzd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2dxjeezrw.html

C#:   s.Replace("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2aecllvvz.html

[E07] 按分隔符拆分
来源：http://dali.yj20258888.top/Article/details/gt2eqnqlsyk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jlsjyb.cn/Article/details/gt2baxwxlhz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2fegejpso.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2bxosgdfw.html

TS:   s.split(",")
来源：http://dali.sxryk.cn/Article/details/gt2tpcbvxem.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gt2lgmhfgie.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2llfmnrbj.html

Ruby: s.split(",");  s.split
来源：http://dali.yuanzhike.top/Article/details/gt2mhbbzovq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guowangkeji.top/Article/details/gt2fzdjongh.html

[E08] 数组按分隔符合并
来源：http://dali.smart0.xyz/Article/details/gt2damjwisn.html

Py:   ",".join(items)
来源：http://dali.zhixingplan.top/Article/details/gt2pvqfiplq.html

PHP:  implode(",", $items);
来源：http://dali.tanke756.top/Article/details/gt2vcziryyq.html

JS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gt2wpzekfdl.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gebxlwww.html

Java: String.join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gt2gkbnfpag.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gt2osjjnkxw.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gt2slwmtizx.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gt2hwbkrkcv.html

[E09] 去除所有空白字符
来源：http://dali.hysaishi.cn/Article/details/gt2yncvuwvs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.iojbl.cn/Article/details/gt2kqiodsmm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2accekaex.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gt2phhjzcvl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gt2mqkkketi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2twpulfus.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gt2gkehqtxu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hysaishi.cn/Article/details/gt2eezwszpz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gt2fqpzzgof.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gt2gmyxvauy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2jpfkdgsj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gt2vguqiveg.html

JS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gpltacbs.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2lzxwfibw.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gt2jqfhxjui.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2ntoxnans.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2rdxwhqmw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2byvgjrse.html

[E11] 反转字符串
来源：http://dali.yueranfly.top/Article/details/gt2qxxpmbmd.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbtvzehy.html

PHP:  strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gt2elzhxbue.html

JS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2czdwiwvf.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2nmquufsm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gt2djwhidwk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gt2psjessro.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gt2uzqysaxf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gt2bvnbsdal.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2toefpcfl.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gt2fyadmqyt.html

PHP:  substr_count($s, "a");
来源：http://dali.guannengcc.top/Article/details/gt2iduccssn.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urorhxts.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gt2agzqrjtn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mooiicfr.html

Go:   strings.Count(s, "a")
来源：http://dali.zhoulong.xyz/Article/details/gt2tundhxvq.html

Ruby: s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gt2zrfvadnf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gt2vjohgvwl.html

[E13] 逐字符遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2zlepwcng.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gt2fgoqmoit.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gt2vshnzzsq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxicxuim.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2nirovwmq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2vfktozml.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gt2awnruybm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nwbrower.top/Article/details/gt2jtgymwvv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gt2hybxnldu.html

[E14] URL 编码与 Base64
来源：http://dali.zdqjudy.top/Article/details/gt2qpqzxuis.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqyaeubk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cheryme.top/Article/details/gt2pvgujvur.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gt2ujfmtjrp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gt2dlnuycli.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2yvrrwmam.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nwbrower.top/Article/details/gt2sjfbhome.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gt2gvjcqcfm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gt2lptrlvst.html

[E15] HTML 转义 / 反转义
来源：http://dali.tianlin.xyz/Article/details/gt2bcmwzupu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gt2ijgbbopv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gt2qbajigmw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jianghu66.top/Article/details/gt2adxvfkze.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2nuszzuip.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cashguo.top/Article/details/gt2frjnbrto.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pcjazmpz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gt2ljprchia.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gt2azlsoszn.html

[E16] 数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gt2jzbbmhbx.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gt2gxjqllif.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gt2gmjmwgkj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ovsznlgk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gt2nlqfwzcv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gt2ntpdeitw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gt2opszzwwf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gt2hvovhlbr.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gt2lqcrnacf.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gt2wngcemyr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fzhhl.top/Article/details/gt2bysouwfh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gt2sglbyxxu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gt2jtxduqqe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gt2nkyzxdnt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gt2zddzrsfz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xinyue.icu/Article/details/gt2xwboedar.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gt2kwbnswwy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2lepgptvn.html

[E18] 模板占位符替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewwjvhlq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigfzy.top/Article/details/gt2fqkikyxj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sysykeji.top/Article/details/gt2cxeixzbl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gt2ifmduhaj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2nhvwossy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2hwmrspeh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2iacifkvs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gt2sdjlpfoz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hfpthk.cn/Article/details/gt2fkzapyfa.html

[E19] 多行文本按行拆分
来源：http://dali.snrcjt.cn/Article/details/gt2hcbbkhxf.html

Py:   s.splitlines()
来源：http://dali.cdnleiting.top/Article/details/gt2klrfxzlm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2omxnexyq.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gt2ubucpzvc.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2mbswsduv.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2qbhbyuqa.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gt2pzvehoqn.html

Ruby: s.lines
来源：http://dali.shuidangran.top/Article/details/gt2qswzwlds.html

C#:   s.Split('\n')
来源：http://dali.yvedp.cn/Article/details/gt2xtpcpxvf.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gt2mgqlkpqh.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gt2mfilpwfe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gt2jcsjjzic.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.9152youxi.cn/Article/details/gt2bzmerorx.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gt2jbdgsoqp.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gt2kqqmmnkn.html

Go:   if s == "" {}
来源：http://dali.svipenyu.cn/Article/details/gt2tckncedq.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gt2pomdsjic.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gt2ezwdladj.html

[E21] 超长截断加省略号
来源：http://dali.yvedp.cn/Article/details/gt2cvbvjyqg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gt2nunokmhs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2bxznhqcy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2sxdqbqsf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2wrabqaih.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2lriucvvz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gt2akmhohoi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2udqbqwhr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2qncnqrsf.html

[E22] 字节长度与字符长度
来源：http://dali.sxryk.cn/Article/details/gt2xgftdgwp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guowangkeji.top/Article/details/gt2wqiyacls.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2wkegzxvy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gt2umwkudlz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gt2wpvszdbd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sweek.top/Article/details/gt2naihbdtl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ircuwcxy.html

Ruby: s.bytesize;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2yaptcmky.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgjprhpp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2wyflxhnk.html

F. 文件与目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbakprvq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2dinrvuwm.html

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gt2jounlice.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sweek.top/Article/details/gt2jffifdji.html

PHP:  file_get_contents("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2hkczrbhw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gt2huxyvkqc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nwbrower.top/Article/details/gt2pswpygtu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2kfotpoxs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gt2khrofwwo.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2sywizihq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2rhiusimm.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gt2lpvrrbeo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gt2hxofoubl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gt2yukfmfyn.html


<!-- 参考信息 -->