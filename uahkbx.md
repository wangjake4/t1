代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtvuywegad.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxinkj.top/Article/details/gtsssbwmfh.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gtwgjwkogs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gtpfymikcs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gthllajrmu.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gtftuhjxau.html

Py:   Counter(arr)
来源：http://dali.ppjwa.cn/Article/details/gttoidlftr.html

PHP:  array_count_values($arr);
来源：http://dali.316326.xyz/Article/details/gtahosskqf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtwfaysjuo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gthpdymcqx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.snrcjt.cn/Article/details/gtauyxpxio.html

Go:   // 手写 map[T]int
来源：http://dali.wangdashe.top/Article/details/gtzltwxgff.html

Ruby: arr.tally
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzporcten.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ppjwa.cn/Article/details/gtnueqcpxj.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gtkashaxvh.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gtvrgxcalh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuxming.cn/Article/details/gtesosxdxk.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtqwmkmbtn.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gthpncjlki.html

Java: list.contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkiuhnuq.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gtxgczlhru.html

Ruby: arr.include?(x)
来源：http://dali.gzhubu.top/Article/details/gtrckubpys.html

C#:   list.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtlmjifdrb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.redwolf501.top/Article/details/gtxqjjiioz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gtycwnlfcd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ehwqpu.com/Article/details/gtkkmsczgo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gtlesrmfqh.html

TS:   [...arr];
来源：http://dali.guowangkeji.top/Article/details/gtucclqaei.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gtdogexrqn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gtwmpzjjyp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwewqdeis.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgpoveui.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gtxlagqmir.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.iojbl.cn/Article/details/gtwiiqaihk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gtswevtnrd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gtgevjisdp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtyxobormx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumooaigg.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtpvdctgiz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gtqltsamvv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sxryk.cn/Article/details/gtnjkveyml.html

[D24] 字典 / Map 基本操作
来源：http://dali.svipenyu.cn/Article/details/gtyzcdxctj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gogol.net.cn/Article/details/gtbybqikwr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtkfixrhbh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gthzrbgjiq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtjphxxngc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daria6918.cn/Article/details/gtgyjuzguw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xylfe.cn/Article/details/gtahchwhly.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gthmpmbgbw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gaohongyu789.top/Article/details/gtqzbmnzfb.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gtusdbkhbz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xziqi.cn/Article/details/gtszjjrpwq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gogol.net.cn/Article/details/gtwaqbijsa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenzaomai.com/Article/details/gtizecgyng.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aibaodan.cn/Article/details/gttqfmavld.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtdwkfspbl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxinkj.top/Article/details/gtiyzoylfw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tianlin.xyz/Article/details/gtppgpuxri.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangdashe.top/Article/details/gtnxmxmbgf.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtftkahhul.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzetwkpyv.html

PHP:  implode(", ", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwtfacno.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtwwhqlyif.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtbxsquyix.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtqeywvfzo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yonumen.top/Article/details/gtnltgbakx.html

Ruby: arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtgwxufcoe.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtsivxmnmq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtatxmvayx.html

E. 字符串处理
来源：http://dali.meibo888.top/Article/details/gtaumchtpn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtkdhshylh.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtuvrwaxnn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gtmlbnlgmk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtdegdzlyf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtrtbasdir.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtdhfkupuq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ybcxt.top/Article/details/gtetihjsec.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gtiaqvfnoz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.feifeiyinyue.top/Article/details/gtkuejedzx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtixgztges.html

[E02] 重复字符串
来源：http://dali.xziqi.cn/Article/details/gtttbcyiga.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtpjzforso.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gthwhcbdhw.html

JS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtnqqmzgvq.html

TS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtdfcjcocx.html

Java: "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtzvrbloaf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shzxlz.cn/Article/details/gttxajhecl.html

Ruby: "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gtqtfnmaog.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtxhostzda.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtsebmgrgr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.havefunace.top/Article/details/gteumtbfrl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtysflevxc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtqzgsgpap.html

TS:   s.slice(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtzdjxaksx.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtohhgkdzn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtrsynoyjb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gtujpuisku.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gtnevtaldj.html

[E04] 查找子串位置
来源：http://dali.nanxinkj.top/Article/details/gtweqowdkf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtpxpirjwo.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbdmzftl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhixingplan.top/Article/details/gtvuqarxkd.html

TS:   s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtswbbkkqq.html

Java: s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtnzttxeyg.html

Go:   strings.Index(s, "x")
来源：http://dali.hysaishi.cn/Article/details/gtajqaxnfe.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtwdojvcbj.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrpxhycr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gtsvheydri.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gtpwppbtlz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gtllkqoxpv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtstvnpadd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gtuicudhmi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtcqedfvhi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhoulong.xyz/Article/details/gtesysfhqc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jiagoushi.top/Article/details/gtyytcqemd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.316326.xyz/Article/details/gtdllhamdx.html

[E06] 替换子串
来源：http://dali.zhoulong.xyz/Article/details/gtbfquysre.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gtutmhjdwh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuanzhike.top/Article/details/gtggdikvlb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtgjrkuuso.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtakndadyj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtvvfwwfhk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtxoefqfdh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtclpikgua.html

C#:   s.Replace("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtezefoegz.html

[E07] 按分隔符拆分
来源：http://dali.hnqzz.top/Article/details/gtrwjlwakm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ybcxt.top/Article/details/gtpumwlvcx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cheryme.top/Article/details/gtblsnppzp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtawqwgdjy.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gtipagxqfv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gtbgqjpwne.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxcnhjsnv.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gtlxvipnjw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hfpthk.cn/Article/details/gtqjdsdipp.html

[E08] 数组按分隔符合并
来源：http://dali.shuidangran.top/Article/details/gtihzmqmht.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gtdiecmwjn.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gtfedaxhtw.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtqrjgyqaq.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtquinvnqw.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtartucukb.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxuanxn.top/Article/details/gtfzmwanju.html

Ruby: items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtdickmxsm.html

C#:   string.Join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gtckdsvdce.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgzynbxj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gtatfcybym.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtfdzjlnel.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gterztnopq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtfzrncnid.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtmneemgwd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shangyingyoupin.top/Article/details/gtsfbzejwk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daxiang520.top/Article/details/gtnprdpzjf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daxiang520.top/Article/details/gtqjtzvwpu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnqzz.top/Article/details/gtciojwool.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gthutyiabe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hongshengwenyu.top/Article/details/gtxqhyevod.html

JS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtmnfdxltq.html

TS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtmcqxzqhf.html

Java: String.format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtyzcketrk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtancizrew.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtdknzcizy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtmjamsocb.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzfxshml.html

Py:   s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtmhhsahbk.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gtdevhltae.html

JS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtxuqhukpx.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtzvjdazky.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangdashe.top/Article/details/gtylndnlzd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xylfe.cn/Article/details/gtgsnecfad.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtghyhozwy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtspusxvmy.html

[E12] 统计某字符出现次数
来源：http://dali.cucudq.cn/Article/details/gtevepdevc.html

Py:   s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gtctrvnifd.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtrpdiuyte.html

JS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gtfqxbqsrw.html

TS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtdzftpzpl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gtcizvhhtd.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gtrnkeeswi.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtitergmit.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfjfmbwp.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gtsxyvpktq.html

Py:   for ch in s: print(ch)
来源：http://dali.yanxiufei.cn/Article/details/gtywpdtekx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cucudq.cn/Article/details/gtskopzhxt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtqiomgmwq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtmfmjguyq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gtffiqnumn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gtdkqeqmjw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gtmuabmiqy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtyhzuqpol.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtnlvgzbga.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.redwolf501.top/Article/details/gtcjejftow.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gthznotsxf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hfpthk.cn/Article/details/gtkmjcciah.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gtkfolnmyf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtxggfljwi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gtqhumgsuh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gtygyatudy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtpmczhlen.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gtrrlchanq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gtvoetgnmm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gthtndqxag.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gtxhkvtssf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gtordxubhp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gtayipmcyc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtyafegdyv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnawakjuz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtdfjuufzt.html

[E16] 数字千分位
来源：http://dali.zycfv.cn/Article/details/gtfwcwkvkx.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gtvvzzbdks.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gtpjxgtsef.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtuheutnrb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtqqycgalk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtzgvoyxbm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gtsqnzxxkh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtdnfowmeu.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gtifizrpao.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gtkhquzbsm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hysaishi.cn/Article/details/gtgtytpxfx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yvedp.cn/Article/details/gtxubpnrfn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gthzekengc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gtjuwvgqvu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hammf.cn/Article/details/gtwdxvlpiz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gtmtmxydkp.html

Ruby: s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gtxbwjkkfl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gtplrkeatt.html

[E18] 模板占位符替换
来源：http://dali.yongpay.top/Article/details/gtxvhuuixe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gtrtfizzyi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gthzfmtxrh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtmayvkvzl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gttcpoohrj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtdjmjmsie.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gthdqkjnun.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtvsrpogzn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sxryk.cn/Article/details/gtlijwgctm.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtdpxvao.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gtbxsuqunq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtgffmqxnz.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtgfgjvkyw.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gtckgfyiwy.html

Java: s.lines().toList()
来源：http://dali.zhengqikj.top/Article/details/gtzyijzaqh.html

Go:   strings.Split(s, "\n")
来源：http://dali.jiagoushi.top/Article/details/gtyojdwuhy.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gtntnbqueu.html

C#:   s.Split('\n')
来源：http://dali.0kj1m.cn/Article/details/gtxcdnnvge.html

[E20] 判断字符串是否为空
来源：http://dali.yangfankeji.com/Article/details/gtrdaqdcxe.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyrgyhru.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hongshengwenyu.top/Article/details/gtncbytepy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zdqjudy.top/Article/details/gtjxjotaio.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gtuqdxcied.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gtsvqjddum.html

Go:   if s == "" {}
来源：http://dali.cheryme.top/Article/details/gtliwuagwr.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gttgvkgjrs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gtacrvjlpq.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gtxjjoezly.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxesgdir.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gthzdwqexu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtqrmhqmdi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtrvupkrbs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtglmmwnlx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gzhubu.top/Article/details/gtxbwlmzal.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtbhzhkkeq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtiwozbyqn.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gtseiltnaq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtjpygpatx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtywchwpmy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtspyzembx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtrxrnsufz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtjpivoxhn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cashguo.top/Article/details/gtyaeeqtka.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtugkgphne.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtbrtnfeji.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpffmeswd.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtamwulvuv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwvtwdiad.html

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gtwkcpmiej.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtbiqvhmym.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtebgvlthx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gtoumqcged.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtplaskime.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtyffhgudm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gtnsjgvbac.html

Ruby: File.read("a.txt")
来源：http://dali.ivvv.top/Article/details/gturkkuxxz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtwtimnfss.html

[F02] 逐行读取文件
来源：http://dali.sysykeji.top/Article/details/gtwkesfgeb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gtfuezmvbh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gtsxqxomxi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtjcowoirm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtjzdhcppc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gthcqyclks.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenjidiqi.icu/Article/details/gtgedgrkiw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gtuxixlgyb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqodqprs.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gtukcgtykq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gtwqvvjraa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtlkhcygmv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtlwwnxtou.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtavwihyke.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtjfmexdzh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtxvwkocsa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtpdtevugp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtwgzsnvbt.html

[F04] 追加写入文件
来源：http://dali.gaohongyu789.top/Article/details/gtuuucoreh.html


<!-- 参考信息 -->