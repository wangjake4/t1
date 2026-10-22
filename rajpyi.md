代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.redwolf501.top/Article/details/gtjakgeeql.html

Ruby: arr.max;  arr.min
来源：http://dali.shangyingyoupin.top/Article/details/gtzhojyzmz.html

C#:   list.Max();  list.Min()
来源：http://dali.yangfankeji.com/Article/details/gtvkegkaos.html

[D18] 扁平化嵌套数组
来源：http://dali.gzhubu.top/Article/details/gtmwevzkva.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gterkcbrcp.html

PHP:  array_merge(...$nested);
来源：http://dali.snrcjt.cn/Article/details/gtxvmwlnqm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258.top/Article/details/gtqfrhuier.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gtbhnxiuen.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sysykeji.top/Article/details/gtpnvyoojp.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gtsjktroho.html

Ruby: nested.flatten
来源：http://dali.gotoacloud.top/Article/details/gtggriblwq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gtglbbyhmz.html

[D19] 按字段分组
来源：http://dali.gzhubu.top/Article/details/gtpcrtrgvo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuanzhike.top/Article/details/gtmhdupbrf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gtfchvrkpg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gtdeavgoom.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gthoktcjcx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gzhubu.top/Article/details/gtqvheydps.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gtcbiyzwtx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gtwlwfobnz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yangfankeji.com/Article/details/gtygyhfkvr.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gtogjpzkht.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gtfjrmwnkz.html

PHP:  array_count_values($arr);
来源：http://dali.ivvv.top/Article/details/gtagqpaedh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtohmbuarr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtlfqzhgzl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gtpdqkjgmw.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gtvashnmpv.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnbptlei.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dianchejie.cn/Article/details/gthtxqsazr.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gtjioaoely.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gttqqyzodf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gtpwncwhxk.html

JS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtgpcnbaav.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gthxeikzrh.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckusfvao.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtwqfvpmaj.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gtigowtwcc.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtddfwxspl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gtnhzlhxfr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gtbqcfznjc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gtpaanlyoz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sufxvd.cn/Article/details/gtglmgvymg.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gtaqyolfqq.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gtqdfemayf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtqmhryy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cdnleiting.top/Article/details/gtnjaccdfn.html

C#:   new List<int>(list);
来源：http://dali.jiagoushi.top/Article/details/gtnimvazwz.html

[D23] reduce 累积计算
来源：http://dali.nanxinkj.top/Article/details/gtzqasjdjx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xziqi.cn/Article/details/gtwofujrnf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtyuqdrany.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtyknjcuvg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtkmpvloka.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gtmjourxsq.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gtcofnumcg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnqzz.top/Article/details/gthiqkcyty.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guowangkeji.top/Article/details/gtislxytsm.html

[D24] 字典 / Map 基本操作
来源：http://dali.daria6918.cn/Article/details/gtyojqmkmo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtjpvangee.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhixingplan.top/Article/details/gtbdxtafpb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gtqgzqyrbb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtkwecmnqo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfxffoyl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gtahurdiwm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtbscdkdnw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.vqdsnc.cn/Article/details/gtgeamzydx.html

[D25] Set 集合去重与交并差
来源：http://dali.tanke756.top/Article/details/gtnswiccyd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pycfn.com/Article/details/gtcqwnwmoz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.mhx1999.top/Article/details/gtssrxletf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gtycscvfpb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmpiltvu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gtxwerbitp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gtxziolaae.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gtqlzhkhja.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtyokmquus.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gtngguvsnm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gtaxamknsu.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gtnnfqcsor.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtqzxqekzv.html

TS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgkrdydz.html

Java: String.join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtypabpqhn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jiagoushi.top/Article/details/gtbxjyddir.html

Ruby: arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtvgdhnmms.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtvwutdpyb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtbnebvdes.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gtqrudfxth.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtslmvuxox.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxvbedkg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tian-w.cn/Article/details/gthrsenfdn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tian-w.cn/Article/details/gtdlmccppy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gtfcplnlph.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtnwgmkdvg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhoulong.xyz/Article/details/gtabcrzavk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yvedp.cn/Article/details/gtqsjtvaul.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gtuozbzxrz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.316326.xyz/Article/details/gtjudnrymo.html

[E02] 重复字符串
来源：http://dali.sxryk.cn/Article/details/gtxlqctltk.html

Py:   "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gtdgoijblv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gtqjxjpwhi.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtcycbpwnt.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gthxibxxji.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtaenscjac.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jiagoushi.top/Article/details/gtiqdpnvyu.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtrnqmtsog.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.0kj1m.cn/Article/details/gtwjqjoduu.html

[E03] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtfsqoaady.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhengqikj.top/Article/details/gtfklyihxz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gttwlhzzvo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtkcfibinm.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtuetpigqe.html

Java: s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtizhydslx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nwbrower.top/Article/details/gtcmgezseh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gtzvsuhdgu.html

C#:   s.Substring(1, 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkjnizlo.html

[E04] 查找子串位置
来源：http://dali.haohaochexian.top/Article/details/gtrgyflthq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtilpdguqw.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gtyhvrpyud.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gteuiahdui.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gthfnesjpf.html

Java: s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtmwwpexum.html

Go:   strings.Index(s, "x")
来源：http://dali.sysykeji.top/Article/details/gtgjkdmzsa.html

Ruby: s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtlpfqinyq.html

C#:   s.IndexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtymybogid.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhongyouzk.top/Article/details/gtsendmpjp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.haohaochexian.top/Article/details/gtraoumput.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gtomcrszbn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtgoalkajt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gtvnzhihfk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gttwpygepy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gtqixaoley.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gaohongyu789.top/Article/details/gtfruzjhxp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtbnxzbyuu.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtspholaey.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtdtvbsjzm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gtcpqjokdq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlalraplp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gttmuvymbn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkgtajju.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gtqypcqgfj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtqzshyuui.html

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtaahsayaa.html

[E07] 按分隔符拆分
来源：http://dali.zhengqikj.top/Article/details/gtfopidgqu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gtgkffcmpt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtpwqmwbfg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gthrimgzfg.html

TS:   s.split(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtcidyipyx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwhzjhcg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258.top/Article/details/gtloyacfsz.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gtwaglyywf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjvrbfva.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gttgwmqprd.html

Py:   ",".join(items)
来源：http://dali.wangdashe.top/Article/details/gtvzemdgfq.html

PHP:  implode(",", $items);
来源：http://dali.yvedp.cn/Article/details/gtdbovbrxa.html

JS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtnqaefkpa.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtcjaqbcol.html

Java: String.join(",", items)
来源：http://dali.hnqzz.top/Article/details/gtaegvuyjf.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gtiijmmaki.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtkafeyeee.html

C#:   string.Join(",", items)
来源：http://dali.yongpay.top/Article/details/gtorxjhdfn.html

[E09] 去除所有空白字符
来源：http://dali.ybcxt.top/Article/details/gtznqtgtrv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yueranfly.top/Article/details/gtpgsdlkjm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gtoeigghav.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gtztvcekrf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtijximvoh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtiroqpkzt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtfftnqd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhoulong.xyz/Article/details/gttwxxdtls.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtkulpnwir.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaumguien.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtqhmdaokc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pycfn.com/Article/details/gtyibiyphr.html

JS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gttqrrbemt.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtpbdigxmh.html

Java: String.format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtyqptdugl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtpfhxjhvw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtblegmhto.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pycfn.com/Article/details/gtaadxrydg.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gtwpungfos.html

Py:   s[::-1]
来源：http://dali.fengsongda.top/Article/details/gtgllgiqkr.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gtxpqzlqtk.html

JS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtumfhueag.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtphwbjqvn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtvxzjisxl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtelgdyhtw.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtvcjyzjya.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtmdqngxlz.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtmivwovjg.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtozanklkh.html

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gttryagglw.html

JS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gtxnhykzxr.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtfjssqgmv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258.top/Article/details/gtkscrqkkg.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gtlzuqjyob.html

Ruby: s.count("a")
来源：http://dali.ivvv.top/Article/details/gtbrgquqbw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.mhx1999.top/Article/details/gtymmdqjaz.html

[E13] 逐字符遍历
来源：http://dali.ehwqpu.com/Article/details/gteluiosmd.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gtnzoigglr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhengqikj.top/Article/details/gtlnubayni.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtzluykoje.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtouggkvtm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtsuofsapa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gtduzevrms.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenzaomai.com/Article/details/gtqaxhzabx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gtyfgjywgw.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtagwjzdlm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guowangkeji.top/Article/details/gtkgdngxcj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cheryme.top/Article/details/gtvsjqgeqx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gtejtmnpde.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gtgvgdpjng.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtrusqyobm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yongpay.top/Article/details/gtpabizlog.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbiwuecu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.mhx1999.top/Article/details/gtrtyxuxnp.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlowedisa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gttapmxvkg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gtjkloanzb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gtoobbrujx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhongyouzk.top/Article/details/gtfzpclazi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gtqvzxgibv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gtuhjhubio.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gttoawtjdn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gttgdefvdx.html

[E16] 数字千分位
来源：http://dali.guannengcc.top/Article/details/gtxylrfvls.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gtgkjlmzti.html

PHP:  number_format(1234567);
来源：http://dali.kuanghao11.cn/Article/details/gtdgwzztga.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtiyhogpyv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtxpsxlckg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yvedp.cn/Article/details/gtjthjwqji.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgfzy.top/Article/details/gtjeeryvoo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.redwolf501.top/Article/details/gtumtummyx.html

C#:   1234567.ToString("N0")
来源：http://dali.cqqwz.cn/Article/details/gtgwrhgaxe.html

[E17] 首字母大写
来源：http://dali.cucudq.cn/Article/details/gtrfsgkkxx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtdxzunhkl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gtggfjdalg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtrqovovps.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gtlhmpewxi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hfpthk.cn/Article/details/gtzroyinbj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cqqwz.cn/Article/details/gtechsclbn.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gtrfvermkx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.quarkkingdee.top/Article/details/gtwhnfoyox.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gtctswmndi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gtpwdgwyis.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgfzy.top/Article/details/gtzrthajwa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtbfqbjtrz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtdltqmbzj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gteqtkqlvt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtvciczsne.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuanzx.com/Article/details/gtpngmykpt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gthzhlcooc.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gtxtcmmyks.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gtcqvftdfv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sxryk.cn/Article/details/gtxbbeidzd.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtjkbzhtcp.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtcfikhobw.html

Java: s.lines().toList()
来源：http://dali.hywenlv.cn/Article/details/gtqpkedrap.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtdcxgheop.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gtmnruodrq.html

C#:   s.Split('\n')
来源：http://dali.havefunace.top/Article/details/gtkeoiffvq.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlwibmrc.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gtscgzomjw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yueranfly.top/Article/details/gtyotnheae.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258.top/Article/details/gtsrtzkbvw.html

TS:   if (s === "") {}
来源：http://dali.sweek.top/Article/details/gtfudtuqxd.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtzeemiuve.html

Go:   if s == "" {}
来源：http://dali.feifeiyinyue.top/Article/details/gtuwmxkwxx.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplevkuzq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtwgarsiok.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gtdshbpuwt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenzaomai.com/Article/details/gtqbpblouw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtjupzighr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtuxgsuszk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtzdtyydtq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtidooyooq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gttygrarba.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtehwmxyxf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtdsvqfirw.html

[E22] 字节长度与字符长度
来源：http://dali.tian-w.cn/Article/details/gtaypbdsek.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gtagtbcmji.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtmvjhnevf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtadvopicn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljypanqq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gttyrplcbz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhengqikj.top/Article/details/gtlaennlvt.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gtnwmgyrok.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgfzy.top/Article/details/gtmcbdugri.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpxswjxkl.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gtqscnrrqb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gttgzmfwra.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtytrxmxuk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shangyingyoupin.top/Article/details/gtjqpgncxj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.316326.xyz/Article/details/gtlurmuhjj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gttuxyliny.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtzrpythnx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtouoisymb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gtxnttqynw.html

Ruby: File.read("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtotcalaur.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtxfjkjgrm.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gtmdjqlqnc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gtfsgrroku.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gthevtwqgo.html


<!-- 参考信息 -->