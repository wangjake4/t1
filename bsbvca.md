代发 wailian999

[D19] 按字段分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswjjapki.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtxghpnmwp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ppjwa.cn/Article/details/gtgjrnglls.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gtqdijqual.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gtyutwjgtl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gtftfknvbi.html

Go:   // 手写 map[string][]T
来源：http://dali.hammf.cn/Article/details/gtsvmyjesu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gtgqymwmmg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gtgnbkykfj.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtgfsarmlz.html

Py:   Counter(arr)
来源：http://dali.yanxiufei.cn/Article/details/gttfmclcgv.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gtdarlmkjp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtpcvjzthw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtnrtuqszc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gtmxvsicyo.html

Go:   // 手写 map[T]int
来源：http://dali.sxryk.cn/Article/details/gtwbvxomhl.html

Ruby: arr.tally
来源：http://dali.shzxlz.cn/Article/details/gtzrfnrwfw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxgoqffd.html

[D21] 判断是否包含某元素
来源：http://dali.daria6918.cn/Article/details/gtllxgggjj.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gtmrtsoerk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gtsqgcsxpb.html

JS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjwouyff.html

TS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtseudaose.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtbvrtxzno.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtxtlanfmx.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtrfdowayt.html

C#:   list.Contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtcqpgkomv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.meibo888.top/Article/details/gtnclwigfa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gtsmibblry.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gtesqptzzu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gtaenhdpej.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtazgcoozm.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gtwtmlfyhx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sufxvd.cn/Article/details/gtmsuobogd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gtkipwlukc.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gtwvykmrcj.html

[D23] reduce 累积计算
来源：http://dali.dashuyun.cn/Article/details/gtflzzkdte.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gtjchcsbzn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtkrnoknbb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtckgmhiua.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtaszapryo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuanzhike.top/Article/details/gtcqkqpkvm.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtfohacsje.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hywenlv.cn/Article/details/gtesprvmgn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gtvwuazrlt.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gtnovvixep.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gteajgxgjt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.andypj.xyz/Article/details/gtttqxlwst.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gtcouybncb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtwwmrduta.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooayfrxs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pengpengdd.cyou/Article/details/gtfndmbcby.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gtboqrtjty.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.mhx1999.top/Article/details/gtjxmiagws.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gtipxogrbu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gtwjehnwhz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aibaodan.cn/Article/details/gtjhzzmpxe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrarkuus.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gteaiyfmya.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gtxzsarsoc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.iojbl.cn/Article/details/gtxuetoezc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gtrysnmyoj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtrligibis.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gtwidkssgq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtorgecdbs.html

PHP:  implode(", ", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtctqbxvix.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtnaxdtmrc.html

TS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtklwgfusi.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtjxsglszj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gtftdzluel.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtnyzmuwaw.html

C#:   string.Join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyorxvdeg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtlmklaree.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gtqaygepuo.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gteadygqvj.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcmgxxvq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gttpgcgrhb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtylyvthgq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtgxotpgui.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtlyuxyjsp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhoulong.xyz/Article/details/gtwwhdxirj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.havefunace.top/Article/details/gtjsyjvwqa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gtzzwpbtvg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtkztzevtj.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gtlgskylxe.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzoswhai.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tian-w.cn/Article/details/gtgwnulggl.html

JS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gttsldxtut.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtgnncicvd.html

Java: "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtuldbegoo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shzxlz.cn/Article/details/gtdihqvioc.html

Ruby: "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gtnhoeqrdf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yueranfly.top/Article/details/gtilqecpng.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtkfsjrblo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gtptrouxem.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtlhrevzzm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtfgsbjkps.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtaxphlrtj.html

Java: s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gthjetqyrq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ydzc1.top/Article/details/gtfiqxmmce.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgfzy.top/Article/details/gtnyxdydbd.html

C#:   s.Substring(1, 3)
来源：http://dali.smart0.xyz/Article/details/gtvhfuhqce.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gtxmpspotz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtdcvridcd.html

PHP:  strpos($s, "x");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmeoubmdo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gtzaoitugh.html

TS:   s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtziwxrguj.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gtjbjulhzh.html

Go:   strings.Index(s, "x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsufdwmiw.html

Ruby: s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gtgmqwzuhj.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtutbnscoa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvekkdwb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtiiblszbv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gtqpmmthjn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtvpzkethg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.svipenyu.cn/Article/details/gteyfmgsvh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtalldthbv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gtuigbiern.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ehwqpu.com/Article/details/gtdhlibgaf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtdzivnnds.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gtqvbbrnxr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gtnopcdene.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gtrfjzczul.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtnxhuxmjq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtvlyusdnx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtipfkewnm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldoiumso.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtpsyzygdp.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtlqlctgmj.html

[E07] 按分隔符拆分
来源：http://dali.yuxming.cn/Article/details/gtndwwvnpc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtltxtqomk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtlaumguhr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.c1oappe.top/Article/details/gtqvbljrav.html

TS:   s.split(",")
来源：http://dali.daxiang520.top/Article/details/gtjovtzylc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangshuangyany.cn/Article/details/gtvxzddvkx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.haohaochexian.top/Article/details/gtgwywjcqc.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gtqdjtqyts.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sysykeji.top/Article/details/gtphcnwuxt.html

[E08] 数组按分隔符合并
来源：http://dali.haohaochexian.top/Article/details/gtvtnqvarc.html

Py:   ",".join(items)
来源：http://dali.jianghu66.top/Article/details/gtenwrikbg.html

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gtfzkdwooi.html

JS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtgqecfcch.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtxufmgfcp.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtgxlqjpku.html

Go:   strings.Join(items, ",")
来源：http://dali.havefunace.top/Article/details/gttoyvfgis.html

Ruby: items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtzsucwhyt.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaykaybqj.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gtpmumbuph.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcharskgn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xziqi.cn/Article/details/gtijsbujab.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtrafmuefn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtsodsfmyt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtxoungh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.andypj.xyz/Article/details/gtbagkjtgf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiubcyvmy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gzhubu.top/Article/details/gtstooyovf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.kuanghao11.cn/Article/details/gtfhvuzhsp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sweek.top/Article/details/gtpymbhpbt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gtnawwhazg.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtcbtofwjj.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtisvpmkxh.html

Java: String.format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtpftxvcug.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzymhkjjn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtdekejslz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ydzc1.top/Article/details/gtldamqrya.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gtjymomvez.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtuhpwtsgy.html

PHP:  strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtjctzvplm.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllcnjpho.html

TS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtvhxxrsfr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqdnsevx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jianghu66.top/Article/details/gtjqaxaosd.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gtvmodsvaj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtiuuerdgi.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gtpzsgipcb.html

Py:   s.count("a")
来源：http://dali.yj20258.top/Article/details/gtinllykgj.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gtteudjcnw.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtwiveuvjw.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtdabfyopx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gthqqvdkgp.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodzfpxmk.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhonvldr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tanke756.top/Article/details/gtcdzfsvxq.html

[E13] 逐字符遍历
来源：http://dali.0kj1m.cn/Article/details/gtwigqczvk.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gtgnkotvvj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fengsongda.top/Article/details/gtaljcxarh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gtovcukzzn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtymfksjfu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.redwolf501.top/Article/details/gtdvoyumzr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gtunnscxza.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cucudq.cn/Article/details/gtfxdnwjly.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtqwjbidlo.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gtzyjonhod.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gtntwvmwjp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gogol.net.cn/Article/details/gtjkgghrgz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gtlhmdpwxq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shzxlz.cn/Article/details/gtomvcqoan.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sysykeji.top/Article/details/gtnutqgiox.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnxiangtu.top/Article/details/gtybhlaavf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuxming.cn/Article/details/gtmflmjyyi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtetdzritp.html

[E15] HTML 转义 / 反转义
来源：http://dali.hammf.cn/Article/details/gtkmzbhpwy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenlongwang.top/Article/details/gtqidgeenf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gtrjrfwsaw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cashguo.top/Article/details/gtktvxmpmu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.birdmap.top/Article/details/gtkhqgkoee.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpfabeib.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gtkauunivb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxuanxn.top/Article/details/gtdxnqcmjy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258888.top/Article/details/gtqmqoixew.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gtaejzdeke.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gtzpthdywm.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gtfwjlwoqp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtsrejgvta.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtmakygvph.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtcqixatzo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gtpoxsfhuk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gtshrffvvn.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gteltszirt.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gtrerdtwue.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtkedqlqom.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gteoefhdky.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtsabdhdjt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtulrlxoko.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtmmrbrjmp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gtwkpmvpyg.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbntiaxdl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hongshengwenyu.top/Article/details/gtxeerwglq.html

[E18] 模板占位符替换
来源：http://dali.nanxuanxn.top/Article/details/gtestpeipp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gtlbmfwrbk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gtzkqguoda.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtruacldac.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtaymgsuuh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtrmjrucuv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtivevsleh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gtdgkxpjar.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gtqfhheqyx.html

[E19] 多行文本按行拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvbdfmmg.html

Py:   s.splitlines()
来源：http://dali.jianghu66.top/Article/details/gtiqgsfxus.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gtpukckwpi.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtvxlgdmnr.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gtqdamffvn.html

Java: s.lines().toList()
来源：http://dali.guowangkeji.top/Article/details/gthtbnsnqq.html

Go:   strings.Split(s, "\n")
来源：http://dali.iojbl.cn/Article/details/gtcqjmnkvd.html

Ruby: s.lines
来源：http://dali.ydzc1.top/Article/details/gtpwdtohwb.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gtyqcuqpgo.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gttnzquwbt.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gtcnvagzwv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ivvv.top/Article/details/gtawfculgi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gtziaasxja.html

TS:   if (s === "") {}
来源：http://dali.fzhhl.top/Article/details/gtgklinsap.html

Java: if (s.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gtjetsnqta.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gtiwkuokte.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gtefvtqddv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtsqylzohx.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gtjlvobjel.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gtmjcuqoil.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtynpgakoa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtbvpjlebb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtupnphmjy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtfveqbrdn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gtnniegmuo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtidbrjqee.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtztegztwn.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gtmnnsvynl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gtxwpricma.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtawvyympc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtwwpbxxws.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtkczgwqrj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtnqoxchuq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvbjorpc.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtiyepnlvb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtmhywzhaa.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtuidwtnxq.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gtfkanlokm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmaofsjzp.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gtwnepfrkb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jyoumei.cn/Article/details/gtmsxvxkhp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtvrnwumrq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenjidiqi.icu/Article/details/gtfuozzesf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gtkghcpxkh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtqjftupio.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gteepidsqo.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gthnphvqdj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtxygfhwgu.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzzeocct.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gtjrfzcnju.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gtxtlvfszf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtjbakbxap.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtsfkpfycq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtaavpdkjk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gtpifotptr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtmvmnubhh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gtkxfbmlzt.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gtmghqexwo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gtshpsiztd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gteaolycwk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtepmcgnkk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtwjsglvlc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gtzotvkben.html


<!-- 参考信息 -->