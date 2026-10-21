代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtjajrzugs.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gtqeyuenzm.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gtispyllnn.html

[D18] 扁平化嵌套数组
来源：http://dali.hywenlv.cn/Article/details/gtuowifsia.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gtexismxfj.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gtqrtzafaa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gtrojmpcgc.html

TS:   nested.flat();
来源：http://dali.ydzc1.top/Article/details/gtttgbgxyw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtxtmjjtqs.html

Go:   // 手写双层循环
来源：http://dali.sxryk.cn/Article/details/gtdmzzzfyk.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gtkaomoqqh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtvaxjkjry.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gtgcslhrgi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gteqzgodbc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xinyue.icu/Article/details/gtssuzjdvo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gtfpqvvmuq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gtbudibhkj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nwbrower.top/Article/details/gtxakyycea.html

Go:   // 手写 map[string][]T
来源：http://dali.zhoulong.xyz/Article/details/gtyyxnwsit.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ppjwa.cn/Article/details/gtaxybivjv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gtnspfljij.html

[D20] 统计每个元素出现次数
来源：http://dali.meibo888.top/Article/details/gtmxroacsg.html

Py:   Counter(arr)
来源：http://dali.bjfxy.top/Article/details/gtcteyjuiw.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gtrutyevuk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtcmukuijo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtuxlqujil.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj202588.top/Article/details/gtuitttchd.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gtldwizztk.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gtrhdazkjb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gtjuaqajwb.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gtzrgvndfm.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gthokobvpf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.andypj.xyz/Article/details/gtcmffkjlr.html

JS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtnzuvxype.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtmkovbrch.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gtodkogtrr.html

Go:   slices.Contains(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtxwpwpxvk.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gtnyfymvfr.html

C#:   list.Contains(x)
来源：http://dali.birdmap.top/Article/details/gtkpfoukau.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shuidangran.top/Article/details/gtaftkxely.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gtwusyhvum.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gtfpebciyg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gtbjyyqrsy.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gtncmhazpi.html

Java: new ArrayList<>(list);
来源：http://dali.gogol.net.cn/Article/details/gtmpilkuha.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yueranfly.top/Article/details/gtjtqhnokd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dashuyun.cn/Article/details/gtnkglgvch.html

C#:   new List<int>(list);
来源：http://dali.nwbrower.top/Article/details/gtgqkdhlwd.html

[D23] reduce 累积计算
来源：http://dali.hammf.cn/Article/details/gtwftrqdsv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gtcdvvyajs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtcrpsfcav.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gtlgdtxsww.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gtmefuncgt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jyoumei.cn/Article/details/gtgqhnwwix.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gtwnjhktad.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gtdqallflc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hfpthk.cn/Article/details/gtpmapkjdt.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gtsdopuhpm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yanxiufei.cn/Article/details/gtnzalkxva.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gtqaitbnnx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gtqwjskziu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtmnuivqeg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gtcpvkeoob.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhongyouzk.top/Article/details/gtbapqamaj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jiagoushi.top/Article/details/gtpnkqxgzi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shuidangran.top/Article/details/gtdpfrlqej.html

[D25] Set 集合去重与交并差
来源：http://dali.dashuyun.cn/Article/details/gtprlkrkip.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.andypj.xyz/Article/details/gtdasdhkyr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.9152youxi.cn/Article/details/gtncyjfatv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gtruoagsrl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gtdjkpysgo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtziatqzfx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhkktgvo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gtvrmsmwzj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtuvqtobgf.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gthuxnzfqa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gtgofcsbqt.html

PHP:  implode(", ", $arr);
来源：http://dali.smart0.xyz/Article/details/gtspfseapl.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtehgmnzjm.html

TS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtxxcyrbpt.html

Java: String.join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtomvsigxl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangdashe.top/Article/details/gterftxjro.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtszqvhcnf.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtpcjbzsqs.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtldysehzk.html

E. 字符串处理
来源：http://dali.nanxinkj.top/Article/details/gtwztpskge.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtanjkvzop.html

[E01] 拼接字符串
来源：http://dali.meibo888.top/Article/details/gtstvlivke.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gtyrbxrqyo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwdbsjar.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtehpdndid.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtvxjflyjs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zycfv.cn/Article/details/gtartmjcpr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yonumen.top/Article/details/gtukewjxje.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gtetetukfc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqksjxjyr.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gtakuvttgp.html

Py:   "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtxcscvihv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.c1oappe.top/Article/details/gtyjjpealj.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsevhobfd.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtflvwzjdp.html

Java: "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtbkljcpjl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gtpdjnwvvd.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gttpijpljv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dianchejie.cn/Article/details/gtvduhmqwn.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtgeibrcgc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.iojbl.cn/Article/details/gtfppidoin.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtqganisaz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtlyuscsca.html

TS:   s.slice(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtqjzgsdlb.html

Java: s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtjpgagdtn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tanke756.top/Article/details/gtjrekxssj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gtkdizyngq.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtpifaufoa.html

[E04] 查找子串位置
来源：http://dali.daxiang520.top/Article/details/gtfzgqhxeq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtkgxbluoc.html

PHP:  strpos($s, "x");
来源：http://dali.birdmap.top/Article/details/gtaqcdnchn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ivvv.top/Article/details/gtnofxmsyy.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtakayjmnm.html

Java: s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtsusbagwc.html

Go:   strings.Index(s, "x")
来源：http://dali.jlsjyb.cn/Article/details/gtdtedbyjh.html

Ruby: s.index("x")
来源：http://dali.c1oappe.top/Article/details/gtiemxtmea.html

C#:   s.IndexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtiqyzutah.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gtteuzjafy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuxming.cn/Article/details/gtopzrjxtc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gtwxzpobul.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtycubyqwj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gtxbqbiswh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtafskmoim.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gtqlxvpfnw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gtuwzrbzpa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtztlvdcey.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gtpdzoffon.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtqezukwzb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gtknqiehlv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtampotemt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtavrhofrn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyppvqof.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtcezhogay.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtbtqmbweb.html

C#:   s.Replace("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtjfwhrdty.html

[E07] 按分隔符拆分
来源：http://dali.gogol.net.cn/Article/details/gtisrlvwzm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tian-w.cn/Article/details/gtlllzqtgc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtojxioghn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuxming.cn/Article/details/gtwyyoyaho.html

TS:   s.split(",")
来源：http://dali.hysaishi.cn/Article/details/gtxlnohell.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.316326.xyz/Article/details/gtcoirnexq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tian-w.cn/Article/details/gticlkkjnh.html

Ruby: s.split(",");  s.split
来源：http://dali.bjfxy.top/Article/details/gtfuajlbzd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gzhubu.top/Article/details/gtxxpgeqrh.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gtnoexdkya.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gtjguvzcgg.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gtcboaahkw.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtknreftle.html

TS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtnoagjefq.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtkfgbrhko.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gtvjjegqkt.html

Ruby: items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtmzlqchjv.html

C#:   string.Join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gttqjjkydh.html

[E09] 去除所有空白字符
来源：http://dali.jinqigfzy.top/Article/details/gtgyldbhcn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gtuqjdjwfe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgfzy.top/Article/details/gtbgtjugib.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtranbhims.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtjigejccd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gtkiwjmnuu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hywenlv.cn/Article/details/gtirhzqknw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.c1oappe.top/Article/details/gtdzsucvai.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrfonqby.html

[E10] 左侧补零 / 定长填充
来源：http://dali.bjfxy.top/Article/details/gtkeyozabg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttviwyahf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gtiwtknopi.html

JS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtsinlhonk.html

TS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtcxnyogna.html

Java: String.format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtpcjesrsd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtudvecqjt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtjncylmwu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gtxcqashrv.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gtdblbpxag.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtundjoleg.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtsixfabfh.html

JS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtftibatiu.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtimkidjxv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgmpalct.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtwwfxilqm.html

Ruby: s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtioapblhg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gticiqcbly.html

[E12] 统计某字符出现次数
来源：http://dali.aibaodan.cn/Article/details/gttnnqgylr.html

Py:   s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtscrfrtuu.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtvaqyilqt.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gthvbobxdf.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtlxvcsxwe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gzhubu.top/Article/details/gtcpcvrsfp.html

Go:   strings.Count(s, "a")
来源：http://dali.daxiang520.top/Article/details/gtwhrkpqtb.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfijvyjcn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gtneovijef.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gtuyplbtsg.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlrqkoey.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrizobuhd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtjbonttaj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtssobfjeu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gtmozeowfa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gtijizskrq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gttkzwazap.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlmexihsd.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gtatbpwcaf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuanzx.com/Article/details/gtzooqpqmq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtpnhknmhg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtngnnxuuk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daxiang520.top/Article/details/gtjfmemznw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gtjufdwdfq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gtkbwciyfk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gtjlojbusi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuanzx.com/Article/details/gtacfsqegh.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gtrnocpyfy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gtkngxyete.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.meibo888.top/Article/details/gthnjitaqg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigufen.top/Article/details/gtmlouqexm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gtnknalswk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hysaishi.cn/Article/details/gtblsfmppx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gthltxiveu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gtddkjvjyp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtsuclpdgk.html

[E16] 数字千分位
来源：http://dali.gzhubu.top/Article/details/gtojouwvui.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gtajzhjpjq.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gttliyrhjr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtkzaapeiu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gtopuulziy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gtegzynkqh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gtzumzdvew.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hammf.cn/Article/details/gtpqyjmwou.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gtqhvjgjig.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gtiwxabski.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gthqdrfmdv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shzxlz.cn/Article/details/gtcdrgynje.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtsrxjmwjz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtvhjxxhyv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvoovkwlv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtrljrosic.html

Ruby: s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gtvzzyaqgl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpheauyn.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gtpfjmtdyd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gtwyjueywl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxuanxn.top/Article/details/gthojrhtxs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtywyhdrsn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtfhmxxnmx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtbaggnikt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtmvtipxig.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtdnvxbzim.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gtqxigvzgl.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gtjeyvtzjl.html

Py:   s.splitlines()
来源：http://dali.andypj.xyz/Article/details/gtqqeclwhj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtzaldqbtk.html

JS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gttvqwvunv.html

TS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttykcmgey.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtfhmkbelm.html

Go:   strings.Split(s, "\n")
来源：http://dali.hammf.cn/Article/details/gtbnboyene.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gtdjzuvjht.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxggesub.html

[E20] 判断字符串是否为空
来源：http://dali.zhixingplan.top/Article/details/gteuakvayk.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gtnbfnkmho.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtpzpscfeo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtlqtqffxg.html

TS:   if (s === "") {}
来源：http://dali.yangfankeji.com/Article/details/gtpqnruqwp.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtgjmruttr.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gtyjhjckwv.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrybhoqbu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gtfcjovjhi.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gttegfobeb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hfpthk.cn/Article/details/gtwsmtamjz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtpmfanqdh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gttqwbghtd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gttbdizjax.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtgqqcmpwu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gtelskorhu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtddoisnve.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtkhwklphy.html

[E22] 字节长度与字符长度
来源：http://dali.havefunace.top/Article/details/gtfafffqhf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pycfn.com/Article/details/gtltjxudgz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gteoocexfa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtxylkaoke.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtswzhmftk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtccvtsmzp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgfzy.top/Article/details/gtlktxlkns.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gtsabsqeyl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtfetnwsyo.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjvjxkwbz.html

F. 文件与目录
来源：http://dali.ybcxt.top/Article/details/gtpilcytdx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtzreddpyz.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gtlqzzxbli.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gtwudqdbfv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtisylrnuq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.c1oappe.top/Article/details/gtruiaympm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtchtrdrbn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmyrjabn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlphsuuk.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtvqewgbpn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gtcmuckbjr.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gtsuypepjb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jlsjyb.cn/Article/details/gtnjpsdlfv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ydzc1.top/Article/details/gthvbjapbk.html


<!-- 参考信息 -->