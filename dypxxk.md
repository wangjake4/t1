代发 wailian999

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gtlyqhcujr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gtdoijbmxc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gtdwfgvgag.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangshuangyany.cn/Article/details/gtbbfwmkqv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gtmxhnhesg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtixneaicu.html

Go:   // 手写 map[string][]T
来源：http://dali.xylfe.cn/Article/details/gtqhiuorec.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shzxlz.cn/Article/details/gtqpijmepv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hysaishi.cn/Article/details/gtivyxpswe.html

[D20] 统计每个元素出现次数
来源：http://dali.ivvv.top/Article/details/gtuiiryihb.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gtmnzcczjy.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtnyuoruyv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gthiejwesn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtncjtqqru.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyzjlpov.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gtxtzvuwls.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gtxvjefsde.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gtwrsbyoud.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gtjkxmifrn.html

Py:   x in arr
来源：http://dali.hywenlv.cn/Article/details/gtyvlvhrsx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cheryme.top/Article/details/gteuzpmayc.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtmaruhmuz.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtewqcwglv.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gtmqetnval.html

Go:   slices.Contains(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtpqdjvpzr.html

Ruby: arr.include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtdemexbzt.html

C#:   list.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gtbkxywapz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gtidoqonhx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pycfn.com/Article/details/gtkficwxoe.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gtrnaotvbq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ppjwa.cn/Article/details/gtweoiuhpr.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gtrvlsuipy.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtovesdeqb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gtcxjkpxnq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwwzhkxi.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gtvdjkroyx.html

[D23] reduce 累积计算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqyosfpdh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuanzhike.top/Article/details/gtenvcjpwu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fzhhl.top/Article/details/gtracigavi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtzmkfjpfm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtwygqujwb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guannengcc.top/Article/details/gtkiiedioj.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtkmixwfhn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuxming.cn/Article/details/gtvugbuxbz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xylfe.cn/Article/details/gtqkygrszz.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gtiqcjpuyq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtxgosoqga.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aibaodan.cn/Article/details/gtgdkdygqv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.mhx1999.top/Article/details/gtabgvbftb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtqykqsubr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gtkguuqtnx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtjdykwldb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtrkkbvxif.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.haohaochexian.top/Article/details/gtwdxomvmt.html

[D25] Set 集合去重与交并差
来源：http://dali.chenzaomai.com/Article/details/gtvdtdesgy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gtoejjwtlu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gaohongyu789.top/Article/details/gtcqnslrzf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuanzx.com/Article/details/gttenqecxy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gtqgtyyzam.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.9152youxi.cn/Article/details/gturchazfw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gtmhpmncar.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtlvxljhzj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daria6918.cn/Article/details/gtrywmwrvd.html

[D26] 数组转字符串
来源：http://dali.ivvv.top/Article/details/gtkxhcbpaz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtrfrljuwy.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gtstvnkkxr.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtyqipvcgm.html

TS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtjdddsbad.html

Java: String.join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gtndbvdxqy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtqhyrdxvj.html

Ruby: arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtvueljryq.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gttsiojxhu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtyfkikgki.html

E. 字符串处理
来源：http://dali.pycfn.com/Article/details/gttcyzpdtw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gternanmia.html

[E01] 拼接字符串
来源：http://dali.yonumen.top/Article/details/gtdgmxzmzi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yongpay.top/Article/details/gtwbtpdqcf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jyoumei.cn/Article/details/gtfdzpgaya.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gtwzupbkaj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtvjbcywut.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gthdtxjwdr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.redwolf501.top/Article/details/gtuiewxnxi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gtcadjwcnk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtuufdronw.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gtpdjhjdcl.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtnklmuued.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhengqikj.top/Article/details/gttphgujtt.html

JS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gterptlenx.html

TS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtphzwnbkb.html

Java: "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtuduzhkyb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtryjtjlth.html

Ruby: "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtwzfnvyvv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gtygjxrqyj.html

[E03] 截取子串
来源：http://dali.hnqzz.top/Article/details/gtcickyqkr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yangfankeji.com/Article/details/gtirtcicsv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtbrysjebe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtrswolsin.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtqrdchrmd.html

Java: s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtxemqdpbd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtuecdxovz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.kuanghao11.cn/Article/details/gtjbgfjtbf.html

C#:   s.Substring(1, 3)
来源：http://dali.hfpthk.cn/Article/details/gtofmbqzpa.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gtlbyffzeb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gtlhmsvcge.html

PHP:  strpos($s, "x");
来源：http://dali.zhengqikj.top/Article/details/gtwnzzqegr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jianghu66.top/Article/details/gthfppiamd.html

TS:   s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtqumjyjxp.html

Java: s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtafurmpjk.html

Go:   strings.Index(s, "x")
来源：http://dali.shuidangran.top/Article/details/gthxcqebkw.html

Ruby: s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtzbyfuqja.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gthzakyhbk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhengqikj.top/Article/details/gtygymuslr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuanzhike.top/Article/details/gtldjbmlsp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yangfankeji.com/Article/details/gtjrdlnphr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtmcehklbd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xinyue.icu/Article/details/gtxwdntxer.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtsmynqnto.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.9152youxi.cn/Article/details/gtatqjpdwc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gtnahleoaj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtqosrtxrs.html

[E06] 替换子串
来源：http://dali.cdnleiting.top/Article/details/gtyolknlgs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtktmcpyet.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.kuanghao11.cn/Article/details/gttxrnmbgi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtxtmtrrfq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtftdxggca.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gttzxcxcmx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtjvbreeqn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gtmvqupqeb.html

C#:   s.Replace("a", "b")
来源：http://dali.zycfv.cn/Article/details/gttznevvtz.html

[E07] 按分隔符拆分
来源：http://dali.yj20258888.top/Article/details/gttyuermxy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenlongwang.top/Article/details/gtdqkoehfw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtnqomupnx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhengqikj.top/Article/details/gthpzeimdw.html

TS:   s.split(",")
来源：http://dali.tianlin.xyz/Article/details/gtppkqdudr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gtxzqabfly.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tianlin.xyz/Article/details/gtjcifuarp.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gtpwmjebyg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yueranfly.top/Article/details/gtkrchmhiu.html

[E08] 数组按分隔符合并
来源：http://dali.9152youxi.cn/Article/details/gtcddfjglr.html

Py:   ",".join(items)
来源：http://dali.jiagoushi.top/Article/details/gtebjfrgjr.html

PHP:  implode(",", $items);
来源：http://dali.tian-w.cn/Article/details/gthjnhswya.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqlpaxms.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdodjxxv.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtsomnvoql.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gtspfjkmqm.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtapldejso.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtoibrfkci.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gtnbtpndrl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuxming.cn/Article/details/gtfapyfild.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nwbrower.top/Article/details/gtosscuufk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtbsggrdma.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtqvrlqacj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gtnhivikqp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgfzy.top/Article/details/gtmqnpqfsi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gtbiprypnq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtvxzfvihe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.c1oappe.top/Article/details/gthftqkvjj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtlytgbups.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.feifeiyinyue.top/Article/details/gtfulkgwed.html

JS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtbizaqeha.html

TS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gttkhukjpj.html

Java: String.format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtlbdqxeip.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtsbulhwdl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtqlysytff.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigfzy.top/Article/details/gtwssggfdw.html

[E11] 反转字符串
来源：http://dali.ppjwa.cn/Article/details/gtaeittokq.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtcpiexueh.html

PHP:  strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtzcdgdazf.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtabegbxdm.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtlfqombka.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gttvhjppgf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cucudq.cn/Article/details/gtbererduq.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gtidqeooyl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtuonyyfjm.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gtmluhblru.html

Py:   s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtqoxixrhb.html

PHP:  substr_count($s, "a");
来源：http://dali.cheryme.top/Article/details/gtpoipivzz.html

JS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtbeaxkgvq.html

TS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtrorsivkq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.9152youxi.cn/Article/details/gtdrfkgalh.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gtjrscgdvd.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnleqpldz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gtfdjosirb.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gtpnlnotvw.html

Py:   for ch in s: print(ch)
来源：http://dali.gzhubu.top/Article/details/gtcvltyzjf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zdqjudy.top/Article/details/gtikexrrvh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtzhuddbxy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtgpnszlbv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gtexvfyare.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yanxiufei.cn/Article/details/gtttmtmrag.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gtrztxuyho.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtdctonnah.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gtmqvlsntn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gtdbspeyfk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdacowpjr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangshuangyany.cn/Article/details/gtrzttudgr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gtdlaatfgs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtowpojqaj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dashuyun.cn/Article/details/gtvywjggqo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpukdmnw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cashguo.top/Article/details/gtzmtubrov.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gtzplytiws.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtupkybdhu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gtijnzwjfe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenlongwang.top/Article/details/gtjzwtsles.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tanke756.top/Article/details/gtchtkwutq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuignpadr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuaiutkb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gtrjkqbnom.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gtnkdqcbla.html

[E16] 数字千分位
来源：http://dali.0kj1m.cn/Article/details/gtdiiszzyp.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzsjoxkk.html

PHP:  number_format(1234567);
来源：http://dali.hnqzz.top/Article/details/gtulxgjycp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbltzsuyz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtgjmyvhne.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwndyvbpv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gtpeuubhww.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.meibo888.top/Article/details/gtbgpbiwfc.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gtpocgkygo.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gtgtamgzxm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtdjifekdq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gtqxelqmaw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtgsezuycc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtqvmzjdhk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gtuqzawrki.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gtltybfhlq.html

Ruby: s.capitalize
来源：http://dali.sxryk.cn/Article/details/gtbkbodket.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gtvhmcnmlq.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gtkhathnhy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gtlgskcmwe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gtbnpvfybz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtpvwwiygp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gthlltaobn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtfskdcsgv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.birdmap.top/Article/details/gtpvyegdyh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hywenlv.cn/Article/details/gttgddglyv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gtmbjuubkw.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gtntrhbttw.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtjnzfbxhl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtsxteksku.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtqprtuyxq.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjihbefp.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtsphbirpd.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gtuspqemrz.html

Ruby: s.lines
来源：http://dali.yangfankeji.com/Article/details/gtwbklwknm.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gtkfwdigvv.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrggpguxq.html

Py:   if not s:
来源：http://dali.yuanzhike.top/Article/details/gtaxtlgdrm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnxiangtu.top/Article/details/gttcykcpto.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gteoevsivn.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfmtfxmtt.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtdirxxmcf.html

Go:   if s == "" {}
来源：http://dali.dianchejie.cn/Article/details/gtceiukncs.html

Ruby: if s.empty?
来源：http://dali.quarkkingdee.top/Article/details/gturexommd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sufxvd.cn/Article/details/gtlaglrdjv.html

[E21] 超长截断加省略号
来源：http://dali.gaohongyu789.top/Article/details/gtaeejcfuv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gaohongyu789.top/Article/details/gtehjutuzt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtcigunjhq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gthglvcrmg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtxafclvvt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtnunzunka.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gtsipobezc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtvbbevfxk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtqtiulfmq.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gtoeuzyldy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxpnspsk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtnyscadeb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtoyzboylx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtllthckbm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.svipenyu.cn/Article/details/gtchyqvnqx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gtlbbegjjr.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gtuoylxipz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtczdqcuut.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtigyrdvsb.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gtgvrthrrb.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gteyxomtwk.html

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gtktoattsv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.316326.xyz/Article/details/gtztdcmbce.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gteuhryttl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gtvizxaiws.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtcvajahil.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gttqtffqbf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gtidrjwqov.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gttjuzzlwm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtfpphkayo.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtetbhoflw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gtkftpuays.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gtigxiesls.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtogtlegaf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrnityth.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtpsqxthvt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gtzggscvci.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gtoxnwiris.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fengsongda.top/Article/details/gtinnxbasi.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gtpmpvkqls.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuanzx.com/Article/details/gtyclnfwhi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gthfroxesy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtcisdmmlv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtjguimvmd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.bjfxy.top/Article/details/gtwyihpvos.html


<!-- 参考信息 -->