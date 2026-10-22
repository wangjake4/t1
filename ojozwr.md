代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtuhntkscu.html

Go:   // 手写双层循环
来源：http://dali.tanke756.top/Article/details/gtgjzfxclb.html

Ruby: nested.flatten
来源：http://dali.dashuyun.cn/Article/details/gtcxfmshgn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fzhhl.top/Article/details/gtgonbhxxd.html

[D19] 按字段分组
来源：http://dali.sweek.top/Article/details/gtyguefogd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gtplflcdgc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jlsjyb.cn/Article/details/gtojxljhsn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.redwolf501.top/Article/details/gtfghikqua.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtjtkzkgyl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gtbddagoue.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gtaoarwzyx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtkrppzqdt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gtyqlqnyye.html

[D20] 统计每个元素出现次数
来源：http://dali.hysaishi.cn/Article/details/gtnpocfsog.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gtvqoqnpoc.html

PHP:  array_count_values($arr);
来源：http://dali.ppjwa.cn/Article/details/gtkzfvgxoi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gtwquxwrjb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtrposjjcc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenjidiqi.icu/Article/details/gtcyyxfqma.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gtffzcywvw.html

Ruby: arr.tally
来源：http://dali.sysykeji.top/Article/details/gtkpkklvzy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gtcxywpxph.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gtndllyubq.html

Py:   x in arr
来源：http://dali.hnqzz.top/Article/details/gttwndesox.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gtcymvbefm.html

JS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtflsxavpu.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtrgosyxhh.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtffkrymkx.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtgahwohxx.html

Ruby: arr.include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gtyjqqnill.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtaclwvnlp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gtzqhnuwga.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gtefgsseix.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.mhx1999.top/Article/details/gtmtksfmra.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtdkbrjukr.html

TS:   [...arr];
来源：http://dali.nwbrower.top/Article/details/gtgfisactf.html

Java: new ArrayList<>(list);
来源：http://dali.xylfe.cn/Article/details/gtegeruenu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtpcdgwnkf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gtiabxijcp.html

C#:   new List<int>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gthinmncfh.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgfuklou.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gtdazagfgr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwrwuttc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtwzfvmase.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtsqbyllfp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gtsrveznqk.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtggqceqtd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ppjwa.cn/Article/details/gtebdqxkcv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigufen.top/Article/details/gtklbnuvwl.html

[D24] 字典 / Map 基本操作
来源：http://dali.yonumen.top/Article/details/gtycvescjn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gtzmvjensn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gtlpcachhq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gtenuibomg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtnbciaikv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gthzozmhec.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gtoqblaluj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gtdqlkbvih.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuxming.cn/Article/details/gtwbfkbqyy.html

[D25] Set 集合去重与交并差
来源：http://dali.sxryk.cn/Article/details/gtacjtctzf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gtzhtbgmls.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.birdmap.top/Article/details/gtgsmtpvjp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gtqzrhtcdk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yonumen.top/Article/details/gtoealcxte.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gtckgivpna.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gtoadiubak.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjeawikgs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fengsongda.top/Article/details/gtvrmaxqaw.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gthobnxrfn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gtcfjqtpfe.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtjymeqdag.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtagjohmri.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtqounfxli.html

Java: String.join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gttgrpunpj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sxryk.cn/Article/details/gtqulznfyu.html

Ruby: arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtzxwymaot.html

C#:   string.Join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gtpmayyhrc.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtxlurtwxu.html

E. 字符串处理
来源：http://dali.zhengqikj.top/Article/details/gtzizvlyzi.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvhafxcyb.html

[E01] 拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtjsskzyzu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gthavazhei.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxinkj.top/Article/details/gtykuddavg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtzhyyzwah.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtfxusoxzc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gtkhplfymf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gtcardndlu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ivvv.top/Article/details/gtixicrxsg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gtnbteryhn.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gtjzvzfrzm.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtajoutdbk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gtutgjqkmf.html

JS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtoyurrovq.html

TS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtegyhuucl.html

Java: "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtnkmmdbcm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gtkrtlyfnj.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtryxkhcuj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtdrlsvwyk.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtkjdevjtg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jianghu66.top/Article/details/gtfpjqimpp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtfzcbbuba.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtkgncqhxf.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtejajgzni.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtqniwffrv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zycfv.cn/Article/details/gtzjogspxa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gtvilyyxmc.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzuilsqx.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gtesbechsx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtvxzgteyd.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gtszjsznwg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jyoumei.cn/Article/details/gtvsnuhfzb.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtdnwgxgsp.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtdvrihkvt.html

Go:   strings.Index(s, "x")
来源：http://dali.shangyingyoupin.top/Article/details/gtyadruysc.html

Ruby: s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtkegkabwm.html

C#:   s.IndexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtjqrnmctu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangshuangyany.cn/Article/details/gtpeafaplh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ybcxt.top/Article/details/gtpalyhjcu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.316326.xyz/Article/details/gtsmflboxc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gtaatefkok.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxinkj.top/Article/details/gthttvhslg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtgxachjbi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gtsqjnowqr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgfzy.top/Article/details/gtewpuawnz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtrvgfibkt.html

[E06] 替换子串
来源：http://dali.hysaishi.cn/Article/details/gtayhyyiyv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltwjfnjo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenzaomai.com/Article/details/gtusowjwmn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtwpmriisi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtrklbfaug.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtbygehevc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtshvfupnh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yonumen.top/Article/details/gtszbneill.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gthpmixgof.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gtawfrkfeg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj202588.top/Article/details/gtontdrsaq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtuugvcyqm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.snrcjt.cn/Article/details/gtdkmimwpb.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gtphemwwep.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuetiantiany.cn/Article/details/gtunfxsrfm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tanke756.top/Article/details/gtpugncfkq.html

Ruby: s.split(",");  s.split
来源：http://dali.yongpay.top/Article/details/gtzndsgyfp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gtkecezmqs.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gtqvhqisji.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gtwesrtcrh.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gtsobazvww.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtmfkfoapw.html

TS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtespivndy.html

Java: String.join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtmchxtxkg.html

Go:   strings.Join(items, ",")
来源：http://dali.yonumen.top/Article/details/gtufznmvyi.html

Ruby: items.join(",")
来源：http://dali.xinyue.icu/Article/details/gthjukhlkx.html

C#:   string.Join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtggrqqahb.html

[E09] 去除所有空白字符
来源：http://dali.zhixingplan.top/Article/details/gtiigsaefy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daria6918.cn/Article/details/gtitrxfnmd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aibaodan.cn/Article/details/gtdulvghtq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtizmifxmp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtaqqugbtp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtuutylcek.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gzhubu.top/Article/details/gtzhnjhlnn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gtktklmelt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yvedp.cn/Article/details/gtgbyzosgl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aizwys.cn/Article/details/gtjchzkyme.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtvwhnrznk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hysaishi.cn/Article/details/gtioanxglj.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtekoulvez.html

TS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtwsteuafo.html

Java: String.format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtijjipibk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtcbzyhukn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtyifyjylg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gtbhmwkfrx.html

[E11] 反转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioomvvnp.html

Py:   s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtmaemprmy.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtjlooayhs.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtqkddatww.html

TS:   [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtpvxkwkxx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbebmgfk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtcznitbyx.html

Ruby: s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtmdufyfrh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtwxogzrsd.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gtegemszvv.html

Py:   s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtvgsmrppo.html

PHP:  substr_count($s, "a");
来源：http://dali.hfpthk.cn/Article/details/gtnvomygdp.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtpfsynazu.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gthwigopso.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gtuqercnrf.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzxxkizo.html

Ruby: s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtnoqvooca.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gtpfzfhcdm.html

[E13] 逐字符遍历
来源：http://dali.sufxvd.cn/Article/details/gtwqtbtbzk.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gtifgmyisn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtvfjpecxk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtvapgjmmw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtxhjbihbc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtwpnbeqtg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yonumen.top/Article/details/gtltmrexjp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gtmaibcmsh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gtmtwnvpkh.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gtncgwcpov.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.redwolf501.top/Article/details/gtomopqnxz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gtnqkxwvne.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gttiafgzba.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhixingplan.top/Article/details/gtjwwuxuqe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gtutpleijh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.redwolf501.top/Article/details/gtlmxbbaiw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sxryk.cn/Article/details/gtnoubksvf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gtvwpphvdc.html

[E15] HTML 转义 / 反转义
来源：http://dali.hammf.cn/Article/details/gtoesbckgl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.kuanghao11.cn/Article/details/gtfpqqpfnw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenlongwang.top/Article/details/gtqxhxaxgw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gtmmptenfx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tian-w.cn/Article/details/gtbdadnjvl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yvedp.cn/Article/details/gtbblogtxc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtfqfrfvow.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jlsjyb.cn/Article/details/gtgwitmqbh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngkktbfj.html

[E16] 数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gttofkbomm.html

Py:   f"{1234567:,}"
来源：http://dali.dashuyun.cn/Article/details/gtbhbqmefj.html

PHP:  number_format(1234567);
来源：http://dali.xuanzx.com/Article/details/gtikovhttc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gtlapanxzi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtytohqtkl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gtqnkuyusb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gtwhgrremf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gtmvydpehb.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gtvxugaivb.html

[E17] 首字母大写
来源：http://dali.yangfankeji.com/Article/details/gtmnwfkwnd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gtlbdmrlhr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ybcxt.top/Article/details/gtlsfggzjj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtndqkefeq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtvvycoifx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zycfv.cn/Article/details/gtqxxxitsb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xylfe.cn/Article/details/gtdxlygcgs.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gtycbevsyp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.c1oappe.top/Article/details/gtsxrdayea.html

[E18] 模板占位符替换
来源：http://dali.9152youxi.cn/Article/details/gtmtpthssr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gtibjikrbr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgfzy.top/Article/details/gtsvcvlgxs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtmblinoiy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtwnyxnewz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtpkdxehgl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtrgcwhene.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ppjwa.cn/Article/details/gtfpegcwhp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtymetvtch.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gtdnoxyipp.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtzpuddxov.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcpowvvs.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtgjxyxehx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtficovhne.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gtdeajhhmt.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfckuzohu.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gtrtvcdoef.html

C#:   s.Split('\n')
来源：http://dali.smart0.xyz/Article/details/gtzlamrjdg.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gtsduwggta.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gtkqoknxro.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yanxiufei.cn/Article/details/gtfwbhnioi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gtuxorhbfi.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gtxiwmdujp.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gtlqpdjomx.html

Go:   if s == "" {}
来源：http://dali.shangyingyoupin.top/Article/details/gtyqzlaxho.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gtxatxbxzz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gtjwuxmilr.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gtybgjlifj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.feifeiyinyue.top/Article/details/gtbtlxgqcs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtxduieecd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtdzpqexoq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtxzxvjmig.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtbrpwuthj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gtfjdatmax.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtltaizecy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtttvbkkrp.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gtpapwczqf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenlongwang.top/Article/details/gtciqskfay.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtbcmfixcl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtvbwlyhen.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gttljnxiga.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtquyvmavr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gtoppcskot.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gtoivgftwm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gthvrgiimg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtswvsgtuc.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipkasyoz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtobktjnwc.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtaujqkigs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gtrgiwggeb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtqzfqgktj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gtbrmqgtlo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtuevetuzq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtkyzozuxw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yvedp.cn/Article/details/gtmbjgwcma.html

Ruby: File.read("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtltjzmgnq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gthwswdxlf.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gtxfziwzga.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gtgyhwoppi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdctfghfs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtrsoteqlu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtjncwysnr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtzvwxrjiy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtlzexpmcu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtztnoujqn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gtnohgqstn.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gtpytreopt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gaohongyu789.top/Article/details/gtvxcwddva.html


<!-- 参考信息 -->