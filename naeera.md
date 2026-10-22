代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gt2mqeshlch.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gt2kcijuvvv.html

Go:   // 手写 map[string][]T
来源：http://dali.hfpthk.cn/Article/details/gt2kgohdxsx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gt2craadejt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gt2arnicnic.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gt2pwccnake.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mttzycuq.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gt2hmuekayy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gt2fxndrxcl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2caygdeme.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigufen.top/Article/details/gt2wjcqwmeg.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gt2hqpvcqwv.html

Ruby: arr.tally
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqeswxzs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gt2hklqfqxs.html

[D21] 判断是否包含某元素
来源：http://dali.cqqwz.cn/Article/details/gt2mwqrpcci.html

Py:   x in arr
来源：http://dali.guowangkeji.top/Article/details/gt2tulfnnim.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldiozwyp.html

JS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gt2llnvagtw.html

TS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2uoeimmdm.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2eqximnle.html

Go:   slices.Contains(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2qcbldqvm.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gt2krxjwxaf.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2joveyfrw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njtpbqec.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2wqmsgccc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhengqikj.top/Article/details/gt2zsixfyka.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2qdgdcotx.html

TS:   [...arr];
来源：http://dali.guowangkeji.top/Article/details/gt2jqhtucdv.html

Java: new ArrayList<>(list);
来源：http://dali.fengsongda.top/Article/details/gt2ozixvade.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gt2jqhuumys.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rcgyajja.html

C#:   new List<int>(list);
来源：http://dali.ehwqpu.com/Article/details/gt2qwybnyoy.html

[D23] reduce 累积计算
来源：http://dali.zhengqikj.top/Article/details/gt2bpeezsed.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gt2hxywltth.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xziqi.cn/Article/details/gt2wdhcacfk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2aacavxbs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gt2mmvmfjfj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gt2zpcoejyd.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gt2lobndtrk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gt2lougcrdh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yangfankeji.com/Article/details/gt2pbhqljvm.html

[D24] 字典 / Map 基本操作
来源：http://dali.iojbl.cn/Article/details/gt2ikcvxypx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gt2cnyqjzao.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.andypj.xyz/Article/details/gt2gkeurjbt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aizwys.cn/Article/details/gt2enypccmi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2ximjomgh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.kuanghao11.cn/Article/details/gt2atgvycod.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daria6918.cn/Article/details/gt2tmeobdmv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.haohaochexian.top/Article/details/gt2lbzmhewh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258888.top/Article/details/gt2trqsfexq.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gt2hdeeyhei.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenzaomai.com/Article/details/gt2gmmpwvju.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cashguo.top/Article/details/gt2skhwxgts.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gt2dofwczru.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.svipenyu.cn/Article/details/gt2yovcbhgv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258888.top/Article/details/gt2uoasrsnb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gt2dltdyhmw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gt2tgxiynka.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2tvaeysmi.html

[D26] 数组转字符串
来源：http://dali.shuidangran.top/Article/details/gt2xcqluoac.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cucudq.cn/Article/details/gt2mycgztvu.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gt2mukvqqfn.html

JS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2ehorkrhw.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gt2khrelyih.html

Java: String.join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gt2xyxowhph.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2syhodvve.html

Ruby: arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2fuvpfedc.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gt2sxgatfjw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2txybimjs.html

E. 字符串处理
来源：http://dali.mhx1999.top/Article/details/gt2gcjflmes.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qcmjjted.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2zhklnntc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jianghu66.top/Article/details/gt2hpyfeqyv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenlongwang.top/Article/details/gt2ydsifqtv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2syiztzct.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gt2wwiebkue.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhoulong.xyz/Article/details/gt2itbcshpe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenzaomai.com/Article/details/gt2hebiwkzj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.quarkkingdee.top/Article/details/gt2effybpks.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tpghbrjz.html

[E02] 重复字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udabzywv.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gt2nquwzxyt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.redwolf501.top/Article/details/gt2mhidggle.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gt2vpgylhjo.html

TS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gt2hnhhukue.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2oopwupyj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gt2jdakvlug.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gt2qijbrwmx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.bjfxy.top/Article/details/gt2tskoeysz.html

[E03] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eyphqkly.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gt2proxglni.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwhmybjy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2isouseop.html

TS:   s.slice(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2sggrtcdv.html

Java: s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gt2szaqhtmq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuxming.cn/Article/details/gt2ulsqygsq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.vqdsnc.cn/Article/details/gt2hjnskfsy.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dozfdyfm.html

[E04] 查找子串位置
来源：http://dali.pengpengdd.cyou/Article/details/gt2nyzjvltm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gt2yjgqgzgj.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gt2ebsjaitl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aizwys.cn/Article/details/gt2zzlakiib.html

TS:   s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2tdbzfkuj.html

Java: s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2qfdjesgz.html

Go:   strings.Index(s, "x")
来源：http://dali.yj202588.top/Article/details/gt2lnjhosxj.html

Ruby: s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gt2drzentaq.html

C#:   s.IndexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2migzwtzy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cugakjkf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2dvsusdno.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangshuangyany.cn/Article/details/gt2omnpfwrl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2nhuyttsd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvoqxjra.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2tzlvjfkd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gt2xrnuivft.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2yqfqvldb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbwtuhoy.html

[E06] 替换子串
来源：http://dali.gogol.net.cn/Article/details/gt2lumzlgnk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gt2qnqbtcnz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2iuxhjxed.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2glhvggpb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2nivypogc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2ruqasnzm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gt2szxjqzno.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2iwwhcvgr.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2huopntal.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwxoilc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hysaishi.cn/Article/details/gt2qoictlcj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2zxyrquso.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gonjikzf.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gt2jirhxoob.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcobtvvy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gt2pixagrmu.html

Ruby: s.split(",");  s.split
来源：http://dali.fengsongda.top/Article/details/gt2unaazaik.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cqqwz.cn/Article/details/gt2qjgdbmoz.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gt2jmeoljhi.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gt2sthhvfgq.html

PHP:  implode(",", $items);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vrqzorwq.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2ixszryub.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gt2fjutiwyv.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gt2pnzlfldf.html

Go:   strings.Join(items, ",")
来源：http://dali.ivvv.top/Article/details/gt2omyhjnvq.html

Ruby: items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2xragpsmh.html

C#:   string.Join(",", items)
来源：http://dali.yonumen.top/Article/details/gt2kuchwvar.html

[E09] 去除所有空白字符
来源：http://dali.tianlin.xyz/Article/details/gt2sktkuixq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gt2bwikjvxl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqsahvjo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvthhyno.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gt2fvhlmycd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gt2rbzuniln.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gt2ckznyuif.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2symzisbd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gt2hoycngwf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.c1oappe.top/Article/details/gt2dbqjadxt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2goembiox.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gt2hlzqfxdk.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2qsqekvny.html

TS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gt2aheebtnr.html

Java: String.format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2itrwgexy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2ififggoj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gt2wyrugfup.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gt2dajpcpgz.html

[E11] 反转字符串
来源：http://dali.zycfv.cn/Article/details/gt2tognzndu.html

Py:   s[::-1]
来源：http://dali.ydzc1.top/Article/details/gt2rxfnzrrg.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2csdztuiw.html

JS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2imodwcnm.html

TS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2yvraxzoy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gt2avkzdaze.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cqqwz.cn/Article/details/gt2qqdfintt.html

Ruby: s.reverse
来源：http://dali.tian-w.cn/Article/details/gt2mvmiwysy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gt2epqlbszc.html

[E12] 统计某字符出现次数
来源：http://dali.jianghu66.top/Article/details/gt2bywrsysf.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gt2phzyinvy.html

PHP:  substr_count($s, "a");
来源：http://dali.zhongyouzk.top/Article/details/gt2vtpvrgik.html

JS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gt2dknywocy.html

TS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jawwsaex.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yanxiufei.cn/Article/details/gt2qmglflbe.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gt2ojimndce.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oyyhyval.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hammf.cn/Article/details/gt2thhulrye.html

[E13] 逐字符遍历
来源：http://dali.hnqzz.top/Article/details/gt2cegsvnof.html

Py:   for ch in s: print(ch)
来源：http://dali.sysykeji.top/Article/details/gt2tdfyvwut.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcohbhpc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gt2wzusoegn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2rfbhvpmf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2pgtxntyl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2zmnbjrnt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.redwolf501.top/Article/details/gt2cqygnqxs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cashguo.top/Article/details/gt2fdchwdfz.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gt2haqjnwtd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gt2gjbwgqfx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2rkfqhhwe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.quarkkingdee.top/Article/details/gt2qtdtbjdh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gt2pkxwntzy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yueranfly.top/Article/details/gt2cqzayolb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigufen.top/Article/details/gt2vljxuvvh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gt2uuftwbiw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2qigmjrce.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gt2xztffjeo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gt2lnddhpwz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gt2jyhddsmo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gt2sjfdcgfa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gt2vuhzslpa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gt2ajllxosb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmlcugur.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gt2alscfhmq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gt2eqqlkozj.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ekwsdrmy.html

Py:   f"{1234567:,}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmxcozjc.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rblfnxjw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gt2eldrcrjn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2kqabuasm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gt2eezdjeob.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gt2steccymb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangdashe.top/Article/details/gt2zdvhfctk.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gt2jethjqqo.html

[E17] 首字母大写
来源：http://dali.yj202588.top/Article/details/gt2vgpfmker.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gt2obztuywy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cucudq.cn/Article/details/gt2zkbhfoqw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gt2htvqlaxx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gt2ipyyodpy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuxming.cn/Article/details/gt2lqiihnhx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2hitqytts.html

Ruby: s.capitalize
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzwlbojo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gt2zeslahub.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gt2ieuzbjny.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xtzodivs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gt2unbbwofd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2tptdibgz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2mzpoxfjf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2gbksvpgk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2mrtffleh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gt2sjbmxvuv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenlongwang.top/Article/details/gt2fhcqvjtg.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gt2ghmojtjd.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gt2hztakmog.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2xryvrcwg.html

JS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gt2dgopnlri.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwzrzsyu.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gt2ehzooavn.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gt2tvnfhisg.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gt2fzqtkvov.html

C#:   s.Split('\n')
来源：http://dali.chenzaomai.com/Article/details/gt2akoqxkol.html

[E20] 判断字符串是否为空
来源：http://dali.jqgufenzy.top/Article/details/gt2akymitbj.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gt2piqghkkq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gt2guvlezkl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cheryme.top/Article/details/gt2lrvxqing.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gt2xtvuwaok.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scardood.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gt2wkzoqlun.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gt2jliheyoi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gt2ptcfgjfu.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gt2gejnpcvy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhoulong.xyz/Article/details/gt2qmqxcvii.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2izvedrwy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2qwvkhwau.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkvlavop.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2darixmbz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sweek.top/Article/details/gt2okdubjil.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2mgieeqzm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2sgozqaot.html

[E22] 字节长度与字符长度
来源：http://dali.bjfxy.top/Article/details/gt2jvxkgpmp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gt2pqobrmzu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2vsnluvcr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gt2uzfzrfij.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gt2zbmokcva.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrlmrno.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.mhx1999.top/Article/details/gt2ahbfazjp.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2ukajaffo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gt2zvnevaqm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2bablzhni.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gt2grecjtus.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2inyszmon.html

[F01] 读取整个文件
来源：http://dali.gotoacloud.top/Article/details/gt2fxsykkhc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.c1oappe.top/Article/details/gt2bcxsexkt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2ruonbfhi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jiagoushi.top/Article/details/gt2wdccysnu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2sibybojh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2widkqyko.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gt2dxhltnlw.html

Ruby: File.read("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2sbjhxrmi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2jdqazlda.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmfchwyy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gt2qkngzffz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daxiang520.top/Article/details/gt2tvixzvue.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2mqoxljqo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gt2jdchbaan.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gt2hhmvawrs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aibaodan.cn/Article/details/gt2rvhchuyu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gt2suakvhds.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rczidgsw.html

[F03] 写入文件（覆盖）
来源：http://dali.tianlin.xyz/Article/details/gt2fukifnse.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258.top/Article/details/gt2lobiomhr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2egxjeunj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2zshzgfde.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2lruxcvfe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hfspqqfb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmqffkry.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.quarkkingdee.top/Article/details/gt2odvhybyr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2kxgqxure.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gt2lejloofj.html


<!-- 参考信息 -->