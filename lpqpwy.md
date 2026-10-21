代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtzdjjvzrb.html

Ruby: arr.max;  arr.min
来源：http://dali.sysykeji.top/Article/details/gtfdduigcw.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gthoidvtvz.html

[D18] 扁平化嵌套数组
来源：http://dali.sxryk.cn/Article/details/gtflffmgrg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gtcifweedn.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gtlmoxryit.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yongpay.top/Article/details/gtvfmljeab.html

TS:   nested.flat();
来源：http://dali.0kj1m.cn/Article/details/gtpfyvefnu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpctwbsi.html

Go:   // 手写双层循环
来源：http://dali.pengpengdd.cyou/Article/details/gttnbjxwrf.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gtthhzqeqz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtskikkclz.html

[D19] 按字段分组
来源：http://dali.quarkkingdee.top/Article/details/gtfogobhqa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gtkwwcrjno.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.0kj1m.cn/Article/details/gtcdcvwtkd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yongpay.top/Article/details/gtycgaqbri.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gtywgwifjs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jyoumei.cn/Article/details/gtzvzmrafn.html

Go:   // 手写 map[string][]T
来源：http://dali.birdmap.top/Article/details/gtoxvhfjpu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gtnwmzdosg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xinyue.icu/Article/details/gtacisswvd.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gtleotvexz.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gtlszaaerc.html

PHP:  array_count_values($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtouvncznf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtbevbawpq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtwuthhkdd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigufen.top/Article/details/gttbykjkjz.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gtkykcfglm.html

Ruby: arr.tally
来源：http://dali.9152youxi.cn/Article/details/gtlejwjiby.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gtzqurqnuq.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtaadnnrwd.html

Py:   x in arr
来源：http://dali.chenzaomai.com/Article/details/gtrjsxpxbk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pycfn.com/Article/details/gtdpzugdfo.html

JS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gtkfxmvfsk.html

TS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtkodwfsid.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtmeknoagw.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtadbyvped.html

Ruby: arr.include?(x)
来源：http://dali.bjfxy.top/Article/details/gtkaxdgvut.html

C#:   list.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtvgdeivwq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cashguo.top/Article/details/gthgxkzlny.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtbrhvnynp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqajsuorx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtyehhnutl.html

TS:   [...arr];
来源：http://dali.hnqzz.top/Article/details/gtsehdwxah.html

Java: new ArrayList<>(list);
来源：http://dali.hnxiangtu.top/Article/details/gttgkbqysy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtpbzowfjh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gtqsrdqbnr.html

C#:   new List<int>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtyuwdxmbr.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmgbuxoo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqvgvxam.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pycfn.com/Article/details/gtksvtzwtc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtkmkzwccy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtawurgrsj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gtyvuuwwkn.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gtrwausiqu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sxryk.cn/Article/details/gttfxmozzn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gtkeucjwbd.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gtnuatwwzh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gtbasomjyw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gtklngqqgj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.andypj.xyz/Article/details/gtpzdpvtba.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtuetlumae.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnqzz.top/Article/details/gtrlhyfqpm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gtlzmofbla.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jiagoushi.top/Article/details/gtzerlbvfs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daxiang520.top/Article/details/gtwcocpzgr.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gtboznqwsd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gteeijgkpl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gtdleljixk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwmwdlwg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ivvv.top/Article/details/gtqwzoyjyd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258.top/Article/details/gtsrerzbcv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gtdmjjxmlz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pycfn.com/Article/details/gtbewhbhvm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sxryk.cn/Article/details/gtijpltcby.html

[D26] 数组转字符串
来源：http://dali.yj20258888.top/Article/details/gtskixblvg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gtejanbbqs.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtpzsretxi.html

JS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtbhisduvv.html

TS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtxmerejuu.html

Java: String.join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtakowfohc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtlcydroed.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtyhyzjuad.html

C#:   string.Join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtqgxhwuea.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtzqvkjoir.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gtorcdttlq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtenifknvj.html

[E01] 拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtvwfcgohs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gtagworizh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzwpvqpl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtbeslirjq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gtyzlponkl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gtysknvuxi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dashuyun.cn/Article/details/gtytlvsclr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tian-w.cn/Article/details/gtidsfbfrc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtehdwwvdt.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gtcuaqkfdn.html

Py:   "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotmlcjtm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yueranfly.top/Article/details/gtieujilvi.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtszlnsljy.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtddjhfpvm.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtqacvdapd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gtydchbogf.html

Ruby: "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtkgwkbkfe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuanzx.com/Article/details/gtglncwbnf.html

[E03] 截取子串
来源：http://dali.yonumen.top/Article/details/gtnmbveanw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gaohongyu789.top/Article/details/gtzlbtljxf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtmddszdvc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtgejptmkk.html

TS:   s.slice(1, 4)
来源：http://dali.cheryme.top/Article/details/gtebbzplwe.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtgxnggzde.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtjzfetlfj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fzhhl.top/Article/details/gtdgahbggn.html

C#:   s.Substring(1, 3)
来源：http://dali.shzxlz.cn/Article/details/gtzyndwupk.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gtvilsyeac.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtxhibyqre.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gtqcatdxpv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuetiantiany.cn/Article/details/gtqpgtntni.html

TS:   s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtxudkrhcq.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtujbsxjpl.html

Go:   strings.Index(s, "x")
来源：http://dali.ivvv.top/Article/details/gtqbvrktpm.html

Ruby: s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtngjofbxe.html

C#:   s.IndexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtrnopqczi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ivvv.top/Article/details/gtwjpxjkmc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtciwrbbtq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gtcouqwuau.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtweckbavf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hywenlv.cn/Article/details/gtnkufbxcu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtnqmtdgja.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenlongwang.top/Article/details/gtejkdyucs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shangyingyoupin.top/Article/details/gttlbiceos.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtszzefwtf.html

[E06] 替换子串
来源：http://dali.redwolf501.top/Article/details/gtnshdlzzm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtrqgybrlo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guannengcc.top/Article/details/gtqdzzbfbm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwofjshrg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtxuhwdkiy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtggygwuik.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtqzdxtvro.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtyyaivdit.html

C#:   s.Replace("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtmuedpstq.html

[E07] 按分隔符拆分
来源：http://dali.yj20258888.top/Article/details/gtdnhoibes.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.c1oappe.top/Article/details/gtnsvobowd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtnqykosnw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gtxtcvjllb.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gtrpxvqqrd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenzaomai.com/Article/details/gtlvccgjaw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fengsongda.top/Article/details/gtiogthfru.html

Ruby: s.split(",");  s.split
来源：http://dali.jinghuilouyu.cn/Article/details/gthsqaczgi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuetiantiany.cn/Article/details/gtnnwmxpuc.html

[E08] 数组按分隔符合并
来源：http://dali.nwbrower.top/Article/details/gtnipspwjn.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gtdrhcmcnf.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gtndgljpjs.html

JS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtwwzqpmth.html

TS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtoyhqluvu.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtiwglpqbf.html

Go:   strings.Join(items, ",")
来源：http://dali.jianghu66.top/Article/details/gtrzhfumqa.html

Ruby: items.join(",")
来源：http://dali.yj202588.top/Article/details/gtcruofpoe.html

C#:   string.Join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtljxmpshg.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gtlorhgqhn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sxryk.cn/Article/details/gtkrsoqzmc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yueranfly.top/Article/details/gtypybabrm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtmskjukju.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtntujiuxo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gtbvizrqqw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gtrvftmfff.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gttdclpusi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtqiwxurwx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gtrqxhkgfy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtuyxrhjrs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gtbvsaiqbk.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtqnmsgpag.html

TS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtqbdgppdx.html

Java: String.format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtfzrkejax.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtysgxkmuy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gttrtsflsz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gtsycheyft.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtmktqoevg.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwmbineu.html

PHP:  strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtckcsxfbf.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtnwctptzc.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtktmeunez.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtpfikrfvq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gtpomirsma.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtjowwwbya.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtfokxnacn.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gtvbzegrxt.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyqztcrq.html

PHP:  substr_count($s, "a");
来源：http://dali.ehwqpu.com/Article/details/gtjbsgdiet.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtmezzafao.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtvksvltbm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gtlbnpxbja.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtltbtkzua.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtviosuxej.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gtiablcjmz.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gtiqifkjyp.html

Py:   for ch in s: print(ch)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxjwoxan.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yongpay.top/Article/details/gtsokraqmt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtljhhyvfz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgujlbzcj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gtiqfrkfmq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gtosohahmv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxmibtht.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gteahkbykm.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gtavhltdck.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guowangkeji.top/Article/details/gtrtnqydus.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gtxqwiuxwn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fzhhl.top/Article/details/gtdazzuueb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guowangkeji.top/Article/details/gtsjyuaaxa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtkpphfslm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbcjeico.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gtfuwaaouh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtkwtbpsqu.html

[E15] HTML 转义 / 反转义
来源：http://dali.smart0.xyz/Article/details/gtbyyhaglm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gtkxcdgmpy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtdtdfprvv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gtzeddtmuz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gtgofeyltg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gtqzadhacr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gtmagxxkpx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gtxcwznbjc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.mhx1999.top/Article/details/gtynygsivu.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gtuakngxmu.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtbpvtjjqs.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gtikingydf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtonoseoys.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtusveevvb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gtxfaixfpw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nwbrower.top/Article/details/gtrkjirlby.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gtehdzjvmc.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gteizwqyas.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gtgqtopmre.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gttwaiefwh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtamiqkqna.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtfzztximd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtlpfuactx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenzaomai.com/Article/details/gtaewxijon.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgufenzy.top/Article/details/gteztchmrf.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtxhgtoors.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.kuanghao11.cn/Article/details/gtbskfmnom.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gtvpbqoepp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gtotzlsuaw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gtdkzgpnxj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtkskbveah.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtfomrcgih.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcrljhnl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtjfzlppjy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenjidiqi.icu/Article/details/gtewirrvvs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jiagoushi.top/Article/details/gtnmssgcex.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gtjpcvjmnx.html

Py:   s.splitlines()
来源：http://dali.gzhubu.top/Article/details/gtmiaozmha.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gtfmatysmx.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtyhamdzew.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnkgmulh.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtqsffjzxj.html

Go:   strings.Split(s, "\n")
来源：http://dali.xylfe.cn/Article/details/gtxxybsuxq.html

Ruby: s.lines
来源：http://dali.hammf.cn/Article/details/gtmolkdvbs.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gtmhgmpkpa.html

[E20] 判断字符串是否为空
来源：http://dali.xinyue.icu/Article/details/gtzjznlrzt.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gtjiiutyae.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.mhx1999.top/Article/details/gtapgsdknb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sxryk.cn/Article/details/gtagxyruoq.html

TS:   if (s === "") {}
来源：http://dali.yuanzhike.top/Article/details/gtmeedqaqx.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtennyarfx.html

Go:   if s == "" {}
来源：http://dali.hfpthk.cn/Article/details/gtimbbpyol.html

Ruby: if s.empty?
来源：http://dali.quarkkingdee.top/Article/details/gthimrlhax.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gtincjbgvb.html

[E21] 超长截断加省略号
来源：http://dali.zhongyouzk.top/Article/details/gtbnmqzmea.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gtxrhyebnv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtvdrhraog.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gttvhnhteg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtrzmgjirr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtsreashov.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghzxvorg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtgmrarnwb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtfbnbygjk.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gttzzpcalk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gtfqaylyvc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtvvjtmgns.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtsqzmvgpo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtstfccmnk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.meibo888.top/Article/details/gtkwybuoqy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zycfv.cn/Article/details/gtpggoiroa.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gtveoegxkd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gtxpmlzwes.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtckxepnhj.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtxppwjpnu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzzitabot.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtawjydkhm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtkbvczlyz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtwhlsyzot.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gtirrnkwow.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pycfn.com/Article/details/gturgjsjfo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqsmlahc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gtloaabkuu.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtfkayzdhz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtsmawaoec.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gtmmlnjefs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbekdgls.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gtvyquseqp.html


<!-- 参考信息 -->