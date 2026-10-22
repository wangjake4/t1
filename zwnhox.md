代发 wailian999

[D19] 按字段分组
来源：http://dali.gzhubu.top/Article/details/gtbgspuwnr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jyoumei.cn/Article/details/gtfllkfzqs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gtwtctnlcx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhengqikj.top/Article/details/gtlmttouka.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtieckptfd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jiagoushi.top/Article/details/gtbqdwwovx.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gtfmwhrivz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgufenzy.top/Article/details/gtlyrpvvgp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenlongwang.top/Article/details/gtiirgdgis.html

[D20] 统计每个元素出现次数
来源：http://dali.dashuyun.cn/Article/details/gtfmxdcdyp.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gtoxfgtrwn.html

PHP:  array_count_values($arr);
来源：http://dali.ivvv.top/Article/details/gtsdmjulbe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtrzwuhkna.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtjbibtkmj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxuanxn.top/Article/details/gtgiqopyvg.html

Go:   // 手写 map[T]int
来源：http://dali.hnqzz.top/Article/details/gtqbsyxlwa.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gtruveoiox.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenzaomai.com/Article/details/gtncxcsjzr.html

[D21] 判断是否包含某元素
来源：http://dali.aizwys.cn/Article/details/gtjuhanwpc.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gtjuoxrkly.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gtcvbjngjs.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtxzigrilx.html

TS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gtdytycsrb.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gtljnujwbh.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtjfozudwn.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtowrbgptj.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gttuctsqiy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258.top/Article/details/gtlnvacmsj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjzjjcgy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jianghu66.top/Article/details/gtjcurfdsl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258888.top/Article/details/gtrukvbxpa.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gtukfgxhjo.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gtrvxkpthy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shuidangran.top/Article/details/gtsnxkdqyq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gtgwrxyiuw.html

C#:   new List<int>(list);
来源：http://dali.hammf.cn/Article/details/gttpzsfmse.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gtzixnrieo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258888.top/Article/details/gtfuriwkea.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtkvaczhjr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtapmuboqc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtvumcthlx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gotoacloud.top/Article/details/gtjkpbzxcc.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtddjodxin.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gtepqijsoa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gtmnxhizvy.html

[D24] 字典 / Map 基本操作
来源：http://dali.gzhubu.top/Article/details/gtksdjduif.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmdllrzl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gtdtfiovyz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenzaomai.com/Article/details/gteghhxdvq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtaumjncay.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtfycuwjlt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gogol.net.cn/Article/details/gtjwhkrqcl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gtbyfxoohc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cqqwz.cn/Article/details/gtsxzudyai.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gtjfaxmjrb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqkhskis.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.kuanghao11.cn/Article/details/gthszvltgn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gtisuvaqen.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aibaodan.cn/Article/details/gtzceaaqoy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.316326.xyz/Article/details/gttwcpqvgm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigufen.top/Article/details/gtwwbhkzxj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cqqwz.cn/Article/details/gtmzzhvzxx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtnvixccri.html

[D26] 数组转字符串
来源：http://dali.c1oappe.top/Article/details/gtkzkvuuet.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pycfn.com/Article/details/gtrryiciwv.html

PHP:  implode(", ", $arr);
来源：http://dali.redwolf501.top/Article/details/gtpzknzbwg.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtektoluvg.html

TS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtkdjiklwe.html

Java: String.join(", ", list)
来源：http://dali.ivvv.top/Article/details/gtkxuslvyw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gtetcoxqps.html

Ruby: arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtgkypedeg.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtzarxnqwp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwxtscwtq.html

E. 字符串处理
来源：http://dali.zhiwuduotai.top/Article/details/gtlsctezsa.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxfpkkclh.html

[E01] 拼接字符串
来源：http://dali.meibo888.top/Article/details/gtybenquxy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.316326.xyz/Article/details/gtyqquxmox.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fengsongda.top/Article/details/gttrthaggp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtvekaddzb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gtdmfdptcy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gtdriinjwt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gtqtqkkkdw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.9152youxi.cn/Article/details/gthlblaxki.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtyeqfvqyz.html

[E02] 重复字符串
来源：http://dali.shzxlz.cn/Article/details/gtuhizamkf.html

Py:   "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtpemohgsm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.iojbl.cn/Article/details/gtxqklphex.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtdvmfnukk.html

TS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyiqnerxt.html

Java: "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtzuzkdpcf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhongyouzk.top/Article/details/gtxwqienfc.html

Ruby: "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtjwhnrzko.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.redwolf501.top/Article/details/gtzxawkelj.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtenwikiyk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gthvdtizeh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwzmeeds.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gteexqgjik.html

TS:   s.slice(1, 4)
来源：http://dali.316326.xyz/Article/details/gtxudhchmd.html

Java: s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtmohwppjp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nwbrower.top/Article/details/gtksqxjegr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gogol.net.cn/Article/details/gtzlajinic.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtizbitxvq.html

[E04] 查找子串位置
来源：http://dali.sufxvd.cn/Article/details/gtlxowyasl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtcjdrhmch.html

PHP:  strpos($s, "x");
来源：http://dali.ppjwa.cn/Article/details/gtqwppwiui.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hywenlv.cn/Article/details/gtdbejkryg.html

TS:   s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtpfkbyjtc.html

Java: s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gttmqzezhu.html

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gtbsurbraq.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gtbegqnrha.html

C#:   s.IndexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtyepfdqqy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jlsjyb.cn/Article/details/gtwhnqyqvt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvedrbboz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yongpay.top/Article/details/gteaqbyyte.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gthoqizxls.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guannengcc.top/Article/details/gtdnmpcyja.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtnvedxywv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guowangkeji.top/Article/details/gtnplocbvq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gtdwrvvexm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtjurfeulm.html

[E06] 替换子串
来源：http://dali.cqqwz.cn/Article/details/gtzcisxhxu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtiqbakunq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gtrzbgtuax.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gttusuwfhj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtoakkpbyy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtguodlfnw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gtsachosli.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtxyrgwiwd.html

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtlwtydxqm.html

[E07] 按分隔符拆分
来源：http://dali.smart0.xyz/Article/details/gtyrpyuike.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenzaomai.com/Article/details/gtfvtyllzl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtmhejxigy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gtvwjtesmh.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gtajmdfwze.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gtgilwpydf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.bjfxy.top/Article/details/gtqojbunzl.html

Ruby: s.split(",");  s.split
来源：http://dali.guowangkeji.top/Article/details/gtxfcsdely.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxuanxn.top/Article/details/gtfawqjluu.html

[E08] 数组按分隔符合并
来源：http://dali.zdqjudy.top/Article/details/gtssgbkbjz.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gtiasgmsne.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gtssrgizwb.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtdaoogljg.html

TS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtkzezxsgg.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtdqksnosw.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gtmjdxtumk.html

Ruby: items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtnblhxmud.html

C#:   string.Join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gtuoakqeec.html

[E09] 去除所有空白字符
来源：http://dali.xuanzx.com/Article/details/gtpczauaaz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyirgtnb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gtkclyyrcd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtdxjvjlrt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtisbjpsve.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtrgbmmoki.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ivvv.top/Article/details/gtkvuisesg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cheryme.top/Article/details/gtcykywrsl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cashguo.top/Article/details/gtwxxtkrzg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xylfe.cn/Article/details/gtsayzjlcz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtgxaucmwb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ybcxt.top/Article/details/gtjldcoxmr.html

JS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtvapwxugy.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtijsokfhr.html

Java: String.format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gttlmmvvol.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtpvemzhgt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtcruqhvzi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gtfeoerigh.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gtejnvhcqi.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtvnckxhxs.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtweswzxzj.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtjobnnkhe.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtnghbfsnt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gtwflkxpgp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gtigekgipz.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gtrrwdpmpg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtudowjoth.html

[E12] 统计某字符出现次数
来源：http://dali.sufxvd.cn/Article/details/gtuhoacpjz.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gtnmudcceb.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gtaxmmyylk.html

JS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gthutuqfyk.html

TS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtoblzdipv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.feifeiyinyue.top/Article/details/gtvbaqalhe.html

Go:   strings.Count(s, "a")
来源：http://dali.cdnleiting.top/Article/details/gtkxzmwvpf.html

Ruby: s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gtghyzhdcc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xylfe.cn/Article/details/gtwprrappj.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gtdxaldytw.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gtrmmoxonu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcizmpqnu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtwxlqhaoz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtddhrekrn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrpsnxcb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.birdmap.top/Article/details/gtzpasytmb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlykklyct.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gtimlzymki.html

[E14] URL 编码与 Base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmgjaquo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gtgxfucreb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtacyokjix.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.9152youxi.cn/Article/details/gtfviocisg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jianghu66.top/Article/details/gtmbhrecml.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnqhgsde.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvmqybmp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gtgyawfiva.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtvroxpanx.html

[E15] HTML 转义 / 反转义
来源：http://dali.birdmap.top/Article/details/gtopgbqjqf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gtovtpqwis.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gttjhqfuhw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gtbtpbxuty.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.316326.xyz/Article/details/gtqehtskec.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fengsongda.top/Article/details/gtqrjcjbgn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtoryujkkt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ehwqpu.com/Article/details/gtupinawmh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gtlakkqnvl.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gtlkrsoiuc.html

Py:   f"{1234567:,}"
来源：http://dali.jianghu66.top/Article/details/gttqdyidxb.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gtpqtkwnsj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gturnaaamk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtennsocwg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gtdgeanydw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gtabhhibrw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pengpengdd.cyou/Article/details/gteymnocvu.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gtbbodlqse.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gtzudomtev.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sufxvd.cn/Article/details/gtlbdrrrgx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gtkvnbnuox.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtfsznzdkm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gtspnnyzuf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.kuanghao11.cn/Article/details/gtauocfkot.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hammf.cn/Article/details/gtxayvwcmi.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gtulozvhaq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gtoccjdozm.html

[E18] 模板占位符替换
来源：http://dali.gzhubu.top/Article/details/gtcpdzdypq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhixingplan.top/Article/details/gttxgqyori.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gtyfriizkt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gthqahhria.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtsrufblnd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtbapvcwci.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtkefbvvtm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gtmowzduta.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gtsfxkuqtu.html

[E19] 多行文本按行拆分
来源：http://dali.cdnleiting.top/Article/details/gtjqipfqkz.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gtmgzlwbog.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrparfycn.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gthgxhzbtc.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtbvinbndr.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmrivsnd.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiffkyybg.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gtcctiqyte.html

C#:   s.Split('\n')
来源：http://dali.haohaochexian.top/Article/details/gtkqmeghbq.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtseqncckm.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gtpxqzuuqr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gtjddggeao.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gtsweueuqi.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gtbpimaomy.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtdujkepjn.html

Go:   if s == "" {}
来源：http://dali.guowangkeji.top/Article/details/gtlznrxblc.html

Ruby: if s.empty?
来源：http://dali.jqgfzy.top/Article/details/gtndoqzvwg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gtusgkutvs.html

[E21] 超长截断加省略号
来源：http://dali.havefunace.top/Article/details/gtswxhpztj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gtvhdtpqxe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtaoxzjcos.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtakntmwyi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtiwaoxbrj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gturxkvcbf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gttpkfohmu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtevlxtpyp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtiqdopexb.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtgwpubkdx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gtwuwciknc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gttktkjqsh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gteeovrqcy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtlhdwtlkm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shuidangran.top/Article/details/gtuysxubdz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.9152youxi.cn/Article/details/gtmsihtobs.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtctulflbn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtvikvkadm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtwqvaxbui.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gtzowmmhjt.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttnpiqbgd.html

[F01] 读取整个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtxxczqrze.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gtwaxhafht.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtnwcruqqh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenzaomai.com/Article/details/gtfxpxqgyv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbybdiak.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gttoipjjpg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sxryk.cn/Article/details/gtounyqvfv.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtukkhwaxf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtqihzykea.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gtxfoapyoc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gtpctdgpcf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gtevwdwdto.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtfnzauuqu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtwiosvmji.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtoteyjuae.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gtjyswalwi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtebsaddod.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gtdggkepqm.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gtofzdrtyd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtztrtgluz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtikoykqvi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtjabuirld.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gttskuqwxt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gtaekbrnwj.html


<!-- 参考信息 -->