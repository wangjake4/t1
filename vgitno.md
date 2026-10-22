代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gt2psplcefn.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gt2jhjphghl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ppjwa.cn/Article/details/gt2kxklhgon.html

TS:   nested.flat();
来源：http://dali.aibaodan.cn/Article/details/gt2wuznlyqd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2fdstjzfb.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gt2ywiiwbuq.html

Ruby: nested.flatten
来源：http://dali.gogol.net.cn/Article/details/gt2fyetqybu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2vvgdxjih.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gt2adrtuhdd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ivvv.top/Article/details/gt2tzycewwz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gt2xjouhwat.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gt2xohsalgj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gt2jllrlpyz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gt2lvzeizmq.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlzbgwmx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.snrcjt.cn/Article/details/gt2eypsmqnq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjiucupc.html

[D20] 统计每个元素出现次数
来源：http://dali.aibaodan.cn/Article/details/gt2pbonuiua.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2vzdvyzaa.html

PHP:  array_count_values($arr);
来源：http://dali.bjfxy.top/Article/details/gt2gehqvefu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gt2zoevtobv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gt2ryhrfkgy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gt2qlokjrqu.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gt2iwgwgjaa.html

Ruby: arr.tally
来源：http://dali.hfpthk.cn/Article/details/gt2mbkdnztl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hywenlv.cn/Article/details/gt2flvzwxba.html

[D21] 判断是否包含某元素
来源：http://dali.ppjwa.cn/Article/details/gt2vmjyfrmn.html

Py:   x in arr
来源：http://dali.zhongyouzk.top/Article/details/gt2lzxkvbif.html

PHP:  in_array($x, $arr, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2wcrsblhp.html

JS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gt2ttrlyjbm.html

TS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2kicmzjgb.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hfinwywo.html

Go:   slices.Contains(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2nrpmpvts.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gt2dhkhlrlm.html

C#:   list.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gt2qxerlmef.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gt2gnrmcsrs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pycfn.com/Article/details/gt2ewwiacgd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gt2erkeknpo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hammf.cn/Article/details/gt2fpkqbqyi.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gt2zhrtqimd.html

Java: new ArrayList<>(list);
来源：http://dali.dianchejie.cn/Article/details/gt2bcnontum.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hammf.cn/Article/details/gt2ttylejqt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ppjwa.cn/Article/details/gt2fkszdgjg.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gt2yxxeuofi.html

[D23] reduce 累积计算
来源：http://dali.hnxiangtu.top/Article/details/gt2dblzcacs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2jqhffupy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gt2lxhthnnn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gt2lqaukhhb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2odjlguga.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.bjfxy.top/Article/details/gt2vjjpjrbn.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gt2kcvdyopc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.havefunace.top/Article/details/gt2npgfhaks.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gt2iqpslvba.html

[D24] 字典 / Map 基本操作
来源：http://dali.daria6918.cn/Article/details/gt2yhjghake.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2psaxoovu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gt2yzxnkapj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gt2wlhqhlhx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtluwocb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnivturp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sysykeji.top/Article/details/gt2gigtyitv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ppjwa.cn/Article/details/gt2bstcflpw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zdqjudy.top/Article/details/gt2idezryle.html

[D25] Set 集合去重与交并差
来源：http://dali.bjfxy.top/Article/details/gt2usjncnkg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258888.top/Article/details/gt2wpspcmhw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenzaomai.com/Article/details/gt2rqlgueid.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sweek.top/Article/details/gt2vcggjcjw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuxming.cn/Article/details/gt2rruurwsl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258.top/Article/details/gt2xrhtylfw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sweek.top/Article/details/gt2agyunrup.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yonumen.top/Article/details/gt2hmwdwnec.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2habhfdit.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gt2icgjcpyg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gt2houscnrz.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gt2vviyzcii.html

JS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gt2mjgxypja.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2cimfqmjp.html

Java: String.join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gt2ufaiaahb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxinkj.top/Article/details/gt2bmzfbxty.html

Ruby: arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2xdemcopn.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gt2mqpxpdeo.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2xcxmmdlk.html

E. 字符串处理
来源：http://dali.ydzc1.top/Article/details/gt2qcfhybdh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2supflgzd.html

[E01] 拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2iwieocdh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258888.top/Article/details/gt2jqxnulmt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guowangkeji.top/Article/details/gt2vrhxpuog.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gt2wkbozrxa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2huqhzubo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gt2zsmeknqx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj202588.top/Article/details/gt2ykzoxngo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.mhx1999.top/Article/details/gt2ekdtawiw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kepyktof.html

[E02] 重复字符串
来源：http://dali.cashguo.top/Article/details/gt2ncpracwn.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gt2ibxbpdlt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjmevmml.html

JS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gt2ytugdwqn.html

TS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gt2icjcospj.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2tbzkprxm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gt2bmhqjkya.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gt2buozhosz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sweek.top/Article/details/gt2acrftlhl.html

[E03] 截取子串
来源：http://dali.wangdashe.top/Article/details/gt2qwjohvck.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.c1oappe.top/Article/details/gt2kzntztmy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2iioytoxf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2lnapvmwm.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2hcmlsfun.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2jjqqzbra.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gt2tyttwayk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gt2xxmeddss.html

C#:   s.Substring(1, 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2wyxwlqsc.html

[E04] 查找子串位置
来源：http://dali.havefunace.top/Article/details/gt2kcyuwmaj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gt2zlrfayer.html

PHP:  strpos($s, "x");
来源：http://dali.shangyingyoupin.top/Article/details/gt2htvdaimp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.vqdsnc.cn/Article/details/gt2pifhkbyh.html

TS:   s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gt2uhbbhqxe.html

Java: s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gt2bcrmbbzw.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gt2yfaxzmbs.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2tqnsdzzl.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gt2xxzzolbp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fzhhl.top/Article/details/gt2rfqtpflm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2ontrtgmy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenjidiqi.icu/Article/details/gt2oavssdyp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gt2iiykevit.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbtobjoo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2yzveduak.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daria6918.cn/Article/details/gt2rbubncfr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2zsswzlri.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2xdxditgp.html

[E06] 替换子串
来源：http://dali.shuidangran.top/Article/details/gt2nxraqzub.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gt2dtxmituu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gt2cdajzyno.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2qhrcufzy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2hpaudmvu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2tmreuruv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gt2aekiuiwx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2ckuofcii.html

C#:   s.Replace("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2wmswmgao.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gt2cqlsmvkb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.vqdsnc.cn/Article/details/gt2vpnhsqyl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2pdgzzpsq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.svipenyu.cn/Article/details/gt2qmiiwiqq.html

TS:   s.split(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2anobwbzs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.quarkkingdee.top/Article/details/gt2nhrhkqmp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nawtkdcz.html

Ruby: s.split(",");  s.split
来源：http://dali.daria6918.cn/Article/details/gt2bafolnyl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnxiangtu.top/Article/details/gt2kbfxnize.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gt2pyiklecx.html

Py:   ",".join(items)
来源：http://dali.jinqigufen.top/Article/details/gt2wenofdex.html

PHP:  implode(",", $items);
来源：http://dali.vqdsnc.cn/Article/details/gt2vmnlsruj.html

JS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gt2debtxlwv.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gt2szfxruft.html

Java: String.join(",", items)
来源：http://dali.pycfn.com/Article/details/gt2ndgqiovz.html

Go:   strings.Join(items, ",")
来源：http://dali.meibo888.top/Article/details/gt2vkiomwnb.html

Ruby: items.join(",")
来源：http://dali.daria6918.cn/Article/details/gt2vvhkilxp.html

C#:   string.Join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gt2pugjwpos.html

[E09] 去除所有空白字符
来源：http://dali.svipenyu.cn/Article/details/gt2rmddpvoj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ppjwa.cn/Article/details/gt2cbvykyyq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2netbmiwm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gt2mkhbejcx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gt2yehmjyvn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gt2yreemhik.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gt2yubopuov.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mpvwhpzh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gt2mhbqyzeo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gt2zvrqbplt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2sbbrzuek.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gt2loymazsj.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2epjgnavn.html

TS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2iutlbkiu.html

Java: String.format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gt2qmdlsjql.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2dythhrfs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2onetxhni.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gogol.net.cn/Article/details/gt2lqsvadcq.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gt2ddmwmavl.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gt2ygtordto.html

PHP:  strrev($s);
来源：http://dali.sweek.top/Article/details/gt2jeiqkjbn.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2vnhazenc.html

TS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wzzenjsi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrupatk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gt2xzyzvowr.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gt2ecjxrbge.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gt2bfhtlxnp.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gt2klpxxioy.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gt2gfzcdljj.html

PHP:  substr_count($s, "a");
来源：http://dali.daxiang520.top/Article/details/gt2bodfcjor.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gt2phitwbpm.html

TS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gt2rwygxspj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gt2oepanftw.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gt2lljyxnum.html

Ruby: s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gt2gwrtvyqt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebtqxjqf.html

[E13] 逐字符遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2uafwgrri.html

Py:   for ch in s: print(ch)
来源：http://dali.xziqi.cn/Article/details/gt2ohzwuuht.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aizwys.cn/Article/details/gt2xerlymoi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agmgborn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2wdfahbrf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2ruoaahyp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gt2uybcrggc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gt2wdvbnghf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2ewywcfqf.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gt2cnupchyd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pengpengdd.cyou/Article/details/gt2akbxolam.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gt2pihydcwt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gt2cjvjxvox.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jianghu66.top/Article/details/gt2nainbnhg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfyautde.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gt2ksaxmzcy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhengqikj.top/Article/details/gt2jzdfhpkg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gt2zcleimhq.html

[E15] HTML 转义 / 反转义
来源：http://dali.hammf.cn/Article/details/gt2ftsbkwpe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aizwys.cn/Article/details/gt2sqkpllmb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gt2ywkyhnyu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fengsongda.top/Article/details/gt2xxskwdvv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gt2dyntglmp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gt2snjbteaf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nwbrower.top/Article/details/gt2ckfhxiuu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2tdfmxkha.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gt2ypnpjnrb.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gt2gicewwox.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gt2jmutqzym.html

PHP:  number_format(1234567);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkkbfxul.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gt2gyiljibv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gt2cieqptrk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gt2mpujiwle.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gt2csqsjvuz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yonumen.top/Article/details/gt2zkmkcyir.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jvvrkyxh.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gt2odgqpkjr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hfpthk.cn/Article/details/gt2slyqeatv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gt2xankogxg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gt2svwykwtm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2pplgcloc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuxming.cn/Article/details/gt2fkzpmxdp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daria6918.cn/Article/details/gt2yjaebvbj.html

Ruby: s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gt2duugtiff.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xziqi.cn/Article/details/gt2kjuiebxm.html

[E18] 模板占位符替换
来源：http://dali.xinyue.icu/Article/details/gt2azbrmqiu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hysaishi.cn/Article/details/gt2avuyyyly.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jixslcjl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2btgeioaz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2neuaejpx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2tbaibqbm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezvxdywb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gt2kjtsbnlj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sysykeji.top/Article/details/gt2riwvmbqx.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gt2zexiyxkl.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gt2ufahwvnm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yodaydbe.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2zvlfpivb.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gt2tcnhlafg.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2bnahmkfq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gt2jjcezilc.html

Ruby: s.lines
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wexrjnln.html

C#:   s.Split('\n')
来源：http://dali.snrcjt.cn/Article/details/gt2efqouyxk.html

[E20] 判断字符串是否为空
来源：http://dali.9152youxi.cn/Article/details/gt2llbphxyz.html

Py:   if not s:
来源：http://dali.aizwys.cn/Article/details/gt2ygxifthw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gt2coytzwwa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdayamcp.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gt2grcbqsji.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zvneozcy.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqxpserx.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gt2jylsjnza.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2wludhhyl.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gt2fnkqzjqd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gt2tsizmpei.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2ftpuyqao.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2gxrefmrn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2rowjhmim.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2onplqfge.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tianlin.xyz/Article/details/gt2kxyaibpo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2hlafhsjq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2yizxonfy.html

[E22] 字节长度与字符长度
来源：http://dali.snrcjt.cn/Article/details/gt2uazwtjzl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnzjtufi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2rurtsjyl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gt2fdahxcvb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2wdkyyway.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhengqikj.top/Article/details/gt2qhketwuh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258888.top/Article/details/gt2gajvngdh.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2zeltqftp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gt2nlejbreu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2tykgrmju.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gt2yquqlsrl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2oanrppdq.html

[F01] 读取整个文件
来源：http://dali.nwbrower.top/Article/details/gt2ukhtvefk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zdqjudy.top/Article/details/gt2csylpyfo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnkllkfc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hongshengwenyu.top/Article/details/gt2gpopeojd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2fchoscdr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eucpcckf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.iojbl.cn/Article/details/gt2wvyqojot.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlsvyile.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2ismvdhkn.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2zorsnxpc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhengqikj.top/Article/details/gt2lalcebxo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gt2bjfuaqji.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gt2wxwokehc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gt2auiyrzvt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gt2yticjftl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxinkj.top/Article/details/gt2vnktylek.html


<!-- 参考信息 -->