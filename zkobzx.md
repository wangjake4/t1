代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gttfgwyoku.html

PHP:  array_merge(...$nested);
来源：http://dali.xziqi.cn/Article/details/gtfutzisre.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.c1oappe.top/Article/details/gtyfdzqtwc.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gtlrobmqjf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gtdcrsuaxk.html

Go:   // 手写双层循环
来源：http://dali.hfpthk.cn/Article/details/gtyichgevf.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gtgfhpkhbw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gtzzjdlzop.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gtzvuiqtqt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hammf.cn/Article/details/gtcfgriamr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dianchejie.cn/Article/details/gtttaqesad.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gtxmjzvycv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtohblwouo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gtbmlqhknd.html

Go:   // 手写 map[string][]T
来源：http://dali.xuanzx.com/Article/details/gtiffqovgk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnshuljgv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangshuangyany.cn/Article/details/gtzqgzixjc.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gtckrrarjz.html

Py:   Counter(arr)
来源：http://dali.fzhhl.top/Article/details/gttjherhgy.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258888.top/Article/details/gtyvoivqcy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtwkmadobm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gtuncnvgth.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtokunhohu.html

Go:   // 手写 map[T]int
来源：http://dali.guannengcc.top/Article/details/gtkwwixnii.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gtrbavtcjb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gtkgprhffa.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrpckgdb.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtmfiewbfc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteptvncxc.html

JS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtflijmhlk.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtdpahwlyx.html

Java: list.contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtbixqipqw.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtqzqgntzx.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gtwwbynsbo.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtbunwzvvt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gtfemzsczv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gtnmtmvhcr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhiwuduotai.top/Article/details/gtcznqaxct.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sufxvd.cn/Article/details/gtzpxwkveg.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gtmjitekyp.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gtkkawzcil.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gtimtfglft.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhoulong.xyz/Article/details/gtfcrbyzbc.html

C#:   new List<int>(list);
来源：http://dali.smart0.xyz/Article/details/gtefmtwsxl.html

[D23] reduce 累积计算
来源：http://dali.daria6918.cn/Article/details/gtmiwmhywd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtgwpirpue.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jyoumei.cn/Article/details/gtdyvivldv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gtndrhystb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtlwrwegzp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gtzgljlfvu.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtxycznajh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenjidiqi.icu/Article/details/gtrbydnmnr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.svipenyu.cn/Article/details/gtmxfjrwne.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gtgkmkdzsq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtokqturkh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gtfongfnzm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gtjqiphtij.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtkncdvxai.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.0kj1m.cn/Article/details/gtmlniarmi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gtglzwlgnq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gttckxsdto.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yueranfly.top/Article/details/gtrubazqmb.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gtryxhkrcv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zdqjudy.top/Article/details/gtbzvwefbr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gtyitwgyop.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gtxmpirtgx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.haohaochexian.top/Article/details/gtizcckpmy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gtjymafivq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtiixjupfg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sxryk.cn/Article/details/gttytnurvw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gttxainsfk.html

[D26] 数组转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmvpveti.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gtbfklfjog.html

PHP:  implode(", ", $arr);
来源：http://dali.daria6918.cn/Article/details/gtdcltajeu.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gttbazmdvg.html

TS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtbiwpdeub.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtgksxyyys.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sxryk.cn/Article/details/gtvqrviybt.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gterwgfocr.html

C#:   string.Join(", ", list)
来源：http://dali.meibo888.top/Article/details/gthqkcmxfn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gthvlwkdde.html

E. 字符串处理
来源：http://dali.fengsongda.top/Article/details/gtrsqvdcxz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtpmcxchqt.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbkivxrc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jyoumei.cn/Article/details/gtqrprkuoz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj202588.top/Article/details/gtynhcxdpc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtcrtrmucx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gthdotvnts.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gtkcjyrxyb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gttcsnbksm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gtbefsoegz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtterkrvij.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gtvcplyoit.html

Py:   "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtdevymrvk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gtuuvjgous.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtqvddkynt.html

TS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gteqxfkdlo.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gttnqafkaf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gtwnmmazvp.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtekgstqor.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.quarkkingdee.top/Article/details/gtwjoaadne.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gtagwxkpkm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gtlhriuynh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gttihbmqvk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtkpgcznnz.html

TS:   s.slice(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtvnpbycnw.html

Java: s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtslfknkbu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258888.top/Article/details/gtlnapsloe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.bjfxy.top/Article/details/gtpdvxfiwp.html

C#:   s.Substring(1, 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtfziunhvi.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gtoksbeegt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtykcdeezg.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gtdrbsisny.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gtyjftocdq.html

TS:   s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtzrwpnffc.html

Java: s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtyaxynmfx.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gtdwzbnzaj.html

Ruby: s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtkchbralp.html

C#:   s.IndexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtoimwzyuu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gtgzjjfpqy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtwgeznlqj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gtclwieexd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtbgobynvj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gaohongyu789.top/Article/details/gtsagtdtlw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtnbjzcasv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gtzbgnfkos.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sweek.top/Article/details/gtucgcdzpx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtukeoydwf.html

[E06] 替换子串
来源：http://dali.chenlongwang.top/Article/details/gtoncnzulp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gtaoqjqvap.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yonumen.top/Article/details/gttqkvpxbc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtrnvcoxjh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtdcuyuvwx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtpfkfvvxo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtcrlkmsia.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtfpxgezmp.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtukzqojlq.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gtsytsiypb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtzkpunmuz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.meibo888.top/Article/details/gtspufljfn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gtjsbypfpw.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gtveryxfpj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aizwys.cn/Article/details/gtsqmqffrm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gtyxbxkcqf.html

Ruby: s.split(",");  s.split
来源：http://dali.xinyue.icu/Article/details/gtphlxdpxi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gttslvkfoe.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gtqhraeasu.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gtagmqridm.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gttpvvkawm.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtjexeabdo.html

TS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtimykhffc.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtjidpmvnw.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gtgmqkhepw.html

Ruby: items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtbhdiywhc.html

C#:   string.Join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gteqbwfiwd.html

[E09] 去除所有空白字符
来源：http://dali.zhongyouzk.top/Article/details/gtjhjugxas.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gtujkegihk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtscujwxbf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtejejhsfr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gtgbvttdmh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuepjhali.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtajytpece.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gttmfgdzid.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtshtfedan.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gttalmpxec.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcxgdhdg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gttqfeukcn.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtalqvkvrt.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtrbaoibpc.html

Java: String.format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtaiegztqu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtgaswojcy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtjyldpgni.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.snrcjt.cn/Article/details/gtmhacjnty.html

[E11] 反转字符串
来源：http://dali.zycfv.cn/Article/details/gtsvifsrzs.html

Py:   s[::-1]
来源：http://dali.zycfv.cn/Article/details/gtqjzhbwte.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gtkwvkofre.html

JS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtfncnkdih.html

TS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtsqguwvsc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gtsjtnkwkx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtrvpjdchr.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtfqaulkcd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gttlxswolh.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmktumzqy.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtrgjefihd.html

PHP:  substr_count($s, "a");
来源：http://dali.guannengcc.top/Article/details/gtxdiwuwmx.html

JS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gtciwwyiky.html

TS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtvcaojncy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dashuyun.cn/Article/details/gtmrpciarh.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gtcqtwjxgw.html

Ruby: s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtcshwstyr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj202588.top/Article/details/gtbdyvtcuv.html

[E13] 逐字符遍历
来源：http://dali.nanxinkj.top/Article/details/gteypznqxl.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyxbjdar.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gtmtbuldib.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtbglgjapo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gterfbzoax.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtsgxvngch.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtfvccyzct.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gtpeoumvaf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daxiang520.top/Article/details/gtcijmglch.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gttkmbcxea.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzajxnnj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gtxeakjopm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gticwtwcef.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgufenzy.top/Article/details/gtpvgcxvgy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gtcvsgpbdh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gtejrkxkaa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gtrefilepy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtfoyjodac.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gtwuxuuiuv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gtdrxjasvo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtpecckzcm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgkjqlxr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.316326.xyz/Article/details/gtpnozpjwf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guowangkeji.top/Article/details/gtzqmtajsx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtvoflqjcz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gttobmuhpo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fzhhl.top/Article/details/gtbhydzcoy.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gtzsihudwo.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gtffosyxtf.html

PHP:  number_format(1234567);
来源：http://dali.yuanzhike.top/Article/details/gttzftwxcd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gtvvttpnqo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gthcylvqrj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gtabkmbues.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gaohongyu789.top/Article/details/gtgotapbss.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gtcoypikxj.html

C#:   1234567.ToString("N0")
来源：http://dali.ehwqpu.com/Article/details/gtabqkjigp.html

[E17] 首字母大写
来源：http://dali.iojbl.cn/Article/details/gtccrookul.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258.top/Article/details/gtajsncvnu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gtmdkpwcbp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtazetwxok.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gthfqmvjow.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gtibdyxnei.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtreuaadmr.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtxwzrkpxf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkdfuucz.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gtqgqkefzl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gtupwhaqjc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daria6918.cn/Article/details/gtkejoyszw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtazbtdvsg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtwshrpcxg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtpudgdfrw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtirpebebo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gtmnmzphoh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtwluwasgl.html

[E19] 多行文本按行拆分
来源：http://dali.yongpay.top/Article/details/gtjqnfmaks.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gtqxxqbrux.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtxxjedkvp.html

JS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtklmooumi.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyyfxhtc.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gtuqxixwmt.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gtndpjomut.html

Ruby: s.lines
来源：http://dali.jqgfzy.top/Article/details/gtmyytbxpx.html

C#:   s.Split('\n')
来源：http://dali.yj202588.top/Article/details/gtgoflkjxw.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gtepuscanf.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gtexcaifpx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gtpvwmhktm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zycfv.cn/Article/details/gtcxoaqfmd.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gtqrbvcnmj.html

Java: if (s.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtpcuosyic.html

Go:   if s == "" {}
来源：http://dali.smart0.xyz/Article/details/gtbqyibyfs.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gtzjognghd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtpgxbnabi.html

[E21] 超长截断加省略号
来源：http://dali.zhoulong.xyz/Article/details/gtqjeabtjy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gtcgeaccwv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtfmrmtifj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtnaoxgwku.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtjsywfbfw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtalsoguww.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gtrptoxgoc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtsjwqgmpv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtknixgigl.html

[E22] 字节长度与字符长度
来源：http://dali.andypj.xyz/Article/details/gthbmlegly.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gtdaeiolzu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtxlvfci.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtmlkxpqvb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtypjuzcdo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtsridluum.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gtbzlsilzc.html

Ruby: s.bytesize;  s.length
来源：http://dali.fengsongda.top/Article/details/gtdesdcwug.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtkrdqfxsf.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtveemelnr.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gtrmaddekk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqqdumczv.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gtrctbawvq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gtsswlnlio.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtcajpvwfk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gtkajylgrt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtyqexzzok.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtahoekvlj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgnuilyl.html

Ruby: File.read("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtmqyzslvf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtatalearz.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gtkojyheze.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ybcxt.top/Article/details/gtsuysvtia.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gtmnazdemd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtqbctxxlk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtrmpwjxui.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtkplmwrxe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jyoumei.cn/Article/details/gtbrmrdygj.html


<!-- 参考信息 -->