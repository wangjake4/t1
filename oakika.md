代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtstdalgra.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gtpckhdiow.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbexftvsy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenlongwang.top/Article/details/gtppjhkwlu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtascknqec.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gtayocvycz.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gtbivfatxq.html

[D18] 扁平化嵌套数组
来源：http://dali.pengpengdd.cyou/Article/details/gtdjjqjdic.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gtkhwapvsh.html

PHP:  array_merge(...$nested);
来源：http://dali.zycfv.cn/Article/details/gtbkkitisd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yangfankeji.com/Article/details/gtifeaobxo.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gthmrudbuh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrhboxvg.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gtabrbxfmf.html

Ruby: nested.flatten
来源：http://dali.fengsongda.top/Article/details/gtywjsmwwp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cashguo.top/Article/details/gtawlyrgjw.html

[D19] 按字段分组
来源：http://dali.cashguo.top/Article/details/gtfglmhoyb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dianchejie.cn/Article/details/gtmlslfwut.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gtkuixzuzr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gtbgzpevcf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gttzxpjqps.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gtwqhczhpb.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gtarkluxkm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnqzz.top/Article/details/gttsmqruqk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gtmorwiyfk.html

[D20] 统计每个元素出现次数
来源：http://dali.svipenyu.cn/Article/details/gtdpanjcnd.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gtumzhnbqi.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtdlszbzlb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtfyyifnve.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gttpvwkvey.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtjixnkopq.html

Go:   // 手写 map[T]int
来源：http://dali.zdqjudy.top/Article/details/gtnkhevcue.html

Ruby: arr.tally
来源：http://dali.ydzc1.top/Article/details/gtehhcrblw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gtggwxvudz.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gtqaajirco.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gthfctojrc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.iojbl.cn/Article/details/gtkjbkysed.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtishovonc.html

TS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtuqcafbwb.html

Java: list.contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtlojzkkyl.html

Go:   slices.Contains(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtrvrrnitf.html

Ruby: arr.include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtwevvhneu.html

C#:   list.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtegptkqlw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gtmwtowrap.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangdashe.top/Article/details/gtrkbcnkum.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zdqjudy.top/Article/details/gtabkwjnnq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gtfyheoodj.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gtlnssrmcf.html

Java: new ArrayList<>(list);
来源：http://dali.c1oappe.top/Article/details/gtdnhpxacg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gtqutgwgmw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aibaodan.cn/Article/details/gtmjncarzn.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gtzwbdwhll.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtdvdiwsni.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gtfoitsnrk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.mhx1999.top/Article/details/gtmbesvjvy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtifxuzthp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gtjwtenkmh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gtwxdoqufo.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gtesorsoit.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtfwtuezql.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigfzy.top/Article/details/gteesftsta.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gtrzznndog.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gtgzkltlww.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gtudobhxol.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gtukcbahcm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtycjsxqvo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sweek.top/Article/details/gtxdrueprp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagewpoya.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtcxjofyfs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sweek.top/Article/details/gttgounzmy.html

[D25] Set 集合去重与交并差
来源：http://dali.guowangkeji.top/Article/details/gtqbvkivns.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gtxuxmsafw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtaegtmdke.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gthxnfcjlw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gtjivmmjyp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtfqcygyqx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnxiangtu.top/Article/details/gtkbxqzrcs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gtlutrqify.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sufxvd.cn/Article/details/gtolesdlfh.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gtynabidjo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gtyibrqqta.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjozuius.html

JS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtlcvufswd.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gttzyxhstc.html

Java: String.join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchugzaof.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtdmofnamb.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gttgjvmoba.html

C#:   string.Join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtkgpkdwlt.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtatuiurfm.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gtzaurlrro.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtugyfttdd.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtxsbbraml.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gtoaujmtyl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtopbtmaaj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtjldiapmi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gtzhpraqoi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtwlbawbyz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gthcvpznqf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgfzy.top/Article/details/gtxlmxwphw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtfmtmzxed.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gtbbumohne.html

Py:   "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtydvbmhoi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sweek.top/Article/details/gthtqvtsud.html

JS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtquaffpuq.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtxedkdikj.html

Java: "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtmhdplqhw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yvedp.cn/Article/details/gtjvnyxsgl.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtzcedxyca.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fengsongda.top/Article/details/gtbucnchef.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtlvdbnebo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gtvdrlbsbf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtknzwylhx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtrbwljqzd.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtcihnpris.html

Java: s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtlgkkfrbg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtnzbrffxq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gtpqpkokkr.html

C#:   s.Substring(1, 3)
来源：http://dali.316326.xyz/Article/details/gtbhzqjkjq.html

[E04] 查找子串位置
来源：http://dali.aibaodan.cn/Article/details/gtgfglxqjo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtatggdwtj.html

PHP:  strpos($s, "x");
来源：http://dali.guannengcc.top/Article/details/gtkzlssqie.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.kuanghao11.cn/Article/details/gthkmcwhjc.html

TS:   s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtohjlzvpq.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gthboulzdt.html

Go:   strings.Index(s, "x")
来源：http://dali.zhixingplan.top/Article/details/gthkkyvjee.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtpbugiimx.html

C#:   s.IndexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtsqtziykk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnqzz.top/Article/details/gtdodhmlaj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtefofvcvj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gtrlkoupkl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gtyzmdabqt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yvedp.cn/Article/details/gttmhlnbyq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtmicvpomx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gtuisucccl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zycfv.cn/Article/details/gtixestdjy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zycfv.cn/Article/details/gthiabaliv.html

[E06] 替换子串
来源：http://dali.daxiang520.top/Article/details/gtvreeizxb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtvpikujnm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zdqjudy.top/Article/details/gtunkfqnol.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtuiampvmm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gthaonuewn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gthdgebubg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtgzqbhtzj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtsqpoevia.html

C#:   s.Replace("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtetyzaolg.html

[E07] 按分隔符拆分
来源：http://dali.jianghu66.top/Article/details/gtbfqoanzh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.meibo888.top/Article/details/gtittginhb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtxxhriuhc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cheryme.top/Article/details/gtbmloibrz.html

TS:   s.split(",")
来源：http://dali.snrcjt.cn/Article/details/gtektnrqgv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgufenzy.top/Article/details/gtenqpnnbx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fengsongda.top/Article/details/gtvrrnoxhl.html

Ruby: s.split(",");  s.split
来源：http://dali.redwolf501.top/Article/details/gtzuzbhhxh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gtqoorpwzo.html

[E08] 数组按分隔符合并
来源：http://dali.yanxiufei.cn/Article/details/gtmktzzdio.html

Py:   ",".join(items)
来源：http://dali.jqgufenzy.top/Article/details/gtldfjjved.html

PHP:  implode(",", $items);
来源：http://dali.jiagoushi.top/Article/details/gtjrqicdfv.html

JS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gtjfwjhaar.html

TS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtboozmprb.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtzoofdssz.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gtlpnzwbpq.html

Ruby: items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtuwzltqrq.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtiihtjmbr.html

[E09] 去除所有空白字符
来源：http://dali.bjfxy.top/Article/details/gtftxhnryt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tianlin.xyz/Article/details/gtlpjmpllw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtaabnrehm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtrcceysug.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtnoyfvoou.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sysykeji.top/Article/details/gtabzpfdnr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daria6918.cn/Article/details/gtgsutxhnw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxuanxn.top/Article/details/gtwqcafkyq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtfrjodlip.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gtjdpnfzuf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gthaekqpub.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.snrcjt.cn/Article/details/gtynnixhcl.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtwcahvadx.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtmysvwndg.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtlpizdokb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtroqopoqu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtydbaommo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gthjyyetyh.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gtidrtzvci.html

Py:   s[::-1]
来源：http://dali.yj20258.top/Article/details/gtygiaudzj.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gtnndbnexj.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtlqvrfsls.html

TS:   [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtaydkyyqe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gtwmfddxjd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj202588.top/Article/details/gtduhcwivl.html

Ruby: s.reverse
来源：http://dali.hnqzz.top/Article/details/gtavduvygq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gthjrfolca.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenzchzfw.html

Py:   s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtgktvsppz.html

PHP:  substr_count($s, "a");
来源：http://dali.daria6918.cn/Article/details/gtwrllkcir.html

JS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtrmkqmvbf.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtpipcqnna.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangdashe.top/Article/details/gtdfustpkl.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gtyqicqnys.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtwxbhgdwi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgfzy.top/Article/details/gtxkyhspsp.html

[E13] 逐字符遍历
来源：http://dali.xuanzx.com/Article/details/gthrnftgql.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gtfaefxzez.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnxiangtu.top/Article/details/gtiblohqzp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gtxbljpwhu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gterpjqbbk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gttzhybrkd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gtjpfsrmvi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gtuqtwumeg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gtwoqxniku.html

[E14] URL 编码与 Base64
来源：http://dali.tianlin.xyz/Article/details/gtyqlzaqfj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gtpspruibt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtyzijmbem.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gtkkhnknqk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gtaftxstmq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtkqwuzagp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gtxywvcvdl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guannengcc.top/Article/details/gtdjpbbfjh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gtfytiiwuj.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gtynmdsqyn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gzhubu.top/Article/details/gtopsqmsiy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtqmbhsddg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tianlin.xyz/Article/details/gtzaorwinv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gtqsryaxod.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gtqxftsjwc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.c1oappe.top/Article/details/gtyaayusvp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gzhubu.top/Article/details/gtqbaihbbv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhixingplan.top/Article/details/gtdczzfifs.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gtxeomuiwz.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyppacfik.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gtwdqzaqel.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtyfonayeg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtdiidspeh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtzjevjxxk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.quarkkingdee.top/Article/details/gtvcvmqzvq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtlfsqiloo.html

C#:   1234567.ToString("N0")
来源：http://dali.daria6918.cn/Article/details/gtvbsialny.html

[E17] 首字母大写
来源：http://dali.xziqi.cn/Article/details/gtyefkrnlj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xylfe.cn/Article/details/gtvakvhdao.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jiagoushi.top/Article/details/gtpzjxvojh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtmscjywfc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtmwjozorl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.bjfxy.top/Article/details/gttzkypuxn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.andypj.xyz/Article/details/gtxuwmlhak.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gtijkvlxpf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtdydmpide.html

[E18] 模板占位符替换
来源：http://dali.guowangkeji.top/Article/details/gtrxmzgcla.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258.top/Article/details/gtgvhpkpnu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gtzyekmfzm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gthoqblllb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gthhpyqflv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtkxmwspca.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtmmyrwbsc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gtembybjsa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.redwolf501.top/Article/details/gtjafhzwhv.html

[E19] 多行文本按行拆分
来源：http://dali.gaohongyu789.top/Article/details/gtkwsbsruc.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gtufbpjeri.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gteffhigfq.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtqlwaadpb.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gteshduzcs.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gteghkajqv.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtuhvxozdu.html

Ruby: s.lines
来源：http://dali.nanxuanxn.top/Article/details/gtbmmimpee.html

C#:   s.Split('\n')
来源：http://dali.0kj1m.cn/Article/details/gtzepjkggg.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtwjpuvbdo.html

Py:   if not s:
来源：http://dali.redwolf501.top/Article/details/gtzymhgixy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuanzhike.top/Article/details/gteoyeypbq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtsfojltpz.html

TS:   if (s === "") {}
来源：http://dali.svipenyu.cn/Article/details/gthgchjibh.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gtrpspubvd.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtchaxmeao.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gtjujeiolq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gtcsbuwhxz.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gtntfftozw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dianchejie.cn/Article/details/gtwbkszzwc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtssbrtojz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtgkjzjvfb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtnlqvaops.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtrplbfxgs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnxiangtu.top/Article/details/gteudpuahz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gtdhzfhmvl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtsweopoyi.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gttrtzyzrs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pycfn.com/Article/details/gtyubmjcht.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gttjzncciy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtauarouyj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtznzxizdy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gtjeoizcup.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuetiantiany.cn/Article/details/gthqwlizyw.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtlvlmrbyk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gtsjvwltmr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqvoqhmis.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gtpotppwys.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtvomhccsz.html

[F01] 读取整个文件
来源：http://dali.ybcxt.top/Article/details/gtmezujmrx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gtpjdtefte.html

PHP:  file_get_contents("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtuxyickbi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gtnemqjufl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtbfmecszx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtirzjjpqv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtkdxygsja.html

Ruby: File.read("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtbbzvcqia.html


<!-- 参考信息 -->