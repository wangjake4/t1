代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtfxzrsocb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pycfn.com/Article/details/gtfmolgwkp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gtvervbhvk.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gtaucxurul.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtzjolfovi.html

[D16] 求和与平均值
来源：http://dali.yj20258.top/Article/details/gtjdgnnfot.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtfbyvurqz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtcqawmpke.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gtkhovrxhm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtcgenfhoy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhoulong.xyz/Article/details/gtkycgwvnw.html

Go:   // 手写循环累加
来源：http://dali.daxiang520.top/Article/details/gtlnwwmyqh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guannengcc.top/Article/details/gtysazlkkx.html

C#:   list.Sum();  list.Average()
来源：http://dali.yanxiufei.cn/Article/details/gthwhoozwt.html

[D17] 最大值与最小值
来源：http://dali.ppjwa.cn/Article/details/gtnumbkgdn.html

Py:   max(arr);  min(arr)
来源：http://dali.hammf.cn/Article/details/gtvwbbkarg.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtaafpbzqt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gttpbkqcnb.html

TS:   Math.max(...arr);
来源：http://dali.nanxinkj.top/Article/details/gtfbapdltk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxinkj.top/Article/details/gtptskigeq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbopujtbe.html

Ruby: arr.max;  arr.min
来源：http://dali.tianlin.xyz/Article/details/gtzdirnyye.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtlfxseaqg.html

[D18] 扁平化嵌套数组
来源：http://dali.ybcxt.top/Article/details/gtzxiiohqg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gtpwqmmzop.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gtteheoyoy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.kuanghao11.cn/Article/details/gtbhrimogy.html

TS:   nested.flat();
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbdxvzqt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gtcnjnhkdd.html

Go:   // 手写双层循环
来源：http://dali.ppjwa.cn/Article/details/gtlwcnebbr.html

Ruby: nested.flatten
来源：http://dali.birdmap.top/Article/details/gtjxluwmol.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtmefrdwnh.html

[D19] 按字段分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqkbghky.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gtejepghzj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gtpxvnfzqx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznsrsksg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtzsaeurbt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj202588.top/Article/details/gtfrjqpdsj.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptjijgob.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jyoumei.cn/Article/details/gtwrahvsyw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gtwksfyrbi.html

[D20] 统计每个元素出现次数
来源：http://dali.jianghu66.top/Article/details/gtgcimuuvu.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gtfbjlahbz.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtouurwozo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtdhmuzmmo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gthvvjsiso.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hywenlv.cn/Article/details/gtgdzoqhdo.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gthmbksqhf.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gtlvyiakoq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gtioprbsyz.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gtnkjqedyl.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gtoxsczbki.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gtpjhfwlfr.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gttqinurck.html

TS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtxiynomae.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrmnvkbt.html

Go:   slices.Contains(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtkironmfa.html

Ruby: arr.include?(x)
来源：http://dali.sweek.top/Article/details/gtuzrworsl.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtzmatnzny.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gtcvubnjms.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gtvbkvsmzk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gtnwvuyshg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gtylwfejiz.html

TS:   [...arr];
来源：http://dali.cdnleiting.top/Article/details/gtsbmvsrqx.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gtgjgfosdy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.quarkkingdee.top/Article/details/gtmxnieawi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gtbgkvlbnh.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gtcfckymgx.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gtcpbkhwlv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.meibo888.top/Article/details/gtzppqqwdj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gtxymqfrfw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtgvpsblda.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtmshfjfxy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuanzhike.top/Article/details/gtdrknxivl.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtqnqkphzx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnxiangtu.top/Article/details/gtjvyljcde.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqprswuem.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gtpslfqije.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gtnjssvzif.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.quarkkingdee.top/Article/details/gtczhdrotv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gtufpihvul.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtujyqxjpe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gtqnhtwihd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yvedp.cn/Article/details/gtgzycyyjx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gtydzagofn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.quarkkingdee.top/Article/details/gtppwohwqn.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gttpwapzfc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsnjxlnz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sufxvd.cn/Article/details/gthhvtygyo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tianlin.xyz/Article/details/gtglytlbql.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cheryme.top/Article/details/gtnvxrnphw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yongpay.top/Article/details/gtretslngs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gotoacloud.top/Article/details/gtfohqakrr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuanzx.com/Article/details/gteknzzine.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpbdzwgr.html

[D26] 数组转字符串
来源：http://dali.hnqzz.top/Article/details/gtfhdrkhdd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gtgtjldohg.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtrnfjuyij.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsszgiyp.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtqiabimqq.html

Java: String.join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtwmuzjwsc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtlpqsjjeg.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtcqsrvmld.html

C#:   string.Join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjccsjhra.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwtxqnfnx.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gttwvniged.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtfkubcklo.html

[E01] 拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtttpefgor.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gtmnwupfob.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cqqwz.cn/Article/details/gttizzkqqj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtqmzbvopw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gtowppfyoc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zdqjudy.top/Article/details/gtokanmnpv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yueranfly.top/Article/details/gtikeupynx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhixingplan.top/Article/details/gtbimnvnhr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtncdepalf.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gtlhufdksh.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtrzfmtpqg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hammf.cn/Article/details/gtpifcrfia.html

JS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtujkhnjqw.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtlpuxvdpf.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gttsgrbyzd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtkzbydcca.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gthtwuzzcg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gtlyuzbqkp.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtqxmmihtv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gtmftwzpfh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtoapixkcy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtkmyhuunk.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtnfstatlu.html

Java: s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtkqngdnfy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258888.top/Article/details/gtzntrezsj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gtauamcnjm.html

C#:   s.Substring(1, 3)
来源：http://dali.nwbrower.top/Article/details/gtewxbewyn.html

[E04] 查找子串位置
来源：http://dali.svipenyu.cn/Article/details/gttgjftnik.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtwhkipprh.html

PHP:  strpos($s, "x");
来源：http://dali.birdmap.top/Article/details/gtxzllffjf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhixingplan.top/Article/details/gtieirgvhs.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrifwxper.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtnzvnefug.html

Go:   strings.Index(s, "x")
来源：http://dali.guannengcc.top/Article/details/gtlpjzvicc.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gtnsybdcav.html

C#:   s.IndexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtiqfjarmc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pengpengdd.cyou/Article/details/gtitvmpyoo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gtxttlvpwd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yueranfly.top/Article/details/gtnobcwalv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtguvqtmkx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gtpkldwhvl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtdbidgdsh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.birdmap.top/Article/details/gtxlgdwlrx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgcaxqlt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqntiues.html

[E06] 替换子串
来源：http://dali.zhengqikj.top/Article/details/gtfzqzorzd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtlriaqmxr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.vqdsnc.cn/Article/details/gtxgmtwemj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqpdtxbh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtiqqmyzdp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtvpmkzjsh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtkjrruyga.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtxvbtwsos.html

C#:   s.Replace("a", "b")
来源：http://dali.xinyue.icu/Article/details/gthixwguzy.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gtrjzdzjqm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxezelxdi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtjsyfcnqo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwgvkwfv.html

TS:   s.split(",")
来源：http://dali.guowangkeji.top/Article/details/gtsasimyea.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sufxvd.cn/Article/details/gtldonuohe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gtgavyobbk.html

Ruby: s.split(",");  s.split
来源：http://dali.gaohongyu789.top/Article/details/gtbymmucxf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gogol.net.cn/Article/details/gtvofmexgk.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gtueeukbfm.html

Py:   ",".join(items)
来源：http://dali.ydzc1.top/Article/details/gtgossnvwl.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gtgijhrbti.html

JS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtknqdwtfe.html

TS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtifhsasfy.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtgvyryxze.html

Go:   strings.Join(items, ",")
来源：http://dali.ppjwa.cn/Article/details/gtxplpvypi.html

Ruby: items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtvmchnmcf.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gtzlgjspff.html

[E09] 去除所有空白字符
来源：http://dali.meibo888.top/Article/details/gtwlubnaaz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xziqi.cn/Article/details/gtmjwxintp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gtdfhqvdvy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtdogdnggu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtoitdcuuc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtiqvuxpuu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gtaousplps.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuxming.cn/Article/details/gtolxkxokv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfolvotr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tian-w.cn/Article/details/gtdmvhydjo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtdiiizvib.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj202588.top/Article/details/gtjoysrwhz.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtufzxhmtb.html

TS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtsozbcmrb.html

Java: String.format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtybujqgnv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzyldyxs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtgobceanl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.mhx1999.top/Article/details/gtwagwmosz.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gtskgogxzw.html

Py:   s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtzwackjwu.html

PHP:  strrev($s);
来源：http://dali.yonumen.top/Article/details/gtvbudktbj.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucxajpzz.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtlsgyrymo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gtcbkldqci.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gtvalomhxj.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gtcnzhgpzj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gtuckzmoem.html

[E12] 统计某字符出现次数
来源：http://dali.jyoumei.cn/Article/details/gtfugcorcp.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gtyrkogvnm.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gtsyosqyqt.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gttpzkvjiq.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtdkkphfzn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gtyazxqjzw.html

Go:   strings.Count(s, "a")
来源：http://dali.cheryme.top/Article/details/gtifyvusdw.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtkpupbjvt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gthgrscpuu.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gttnvrfqef.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gtcgfjczao.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhongyouzk.top/Article/details/gtmecreskz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gtkqtjfdby.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtmyndtagn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cashguo.top/Article/details/gtegwmyjce.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gtywlmbpyu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gtpqypwhhh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtkahmmblp.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gtjivqictz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtiufpszsv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daria6918.cn/Article/details/gtatdfuhjg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gtbjhkjzif.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gtvdpypnvt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gtbjrgueop.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.iojbl.cn/Article/details/gtfmhsndtd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ppjwa.cn/Article/details/gtmkihalvp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtscmyuxjg.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigfzy.top/Article/details/gtzrfqkwja.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gtodguumnw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yueranfly.top/Article/details/gttmbihede.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gtmtrkzitn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hfpthk.cn/Article/details/gtnullmyaf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gtaaqzvrof.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ppjwa.cn/Article/details/gtcixlwzac.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxzpzqztk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gteercaowx.html

[E16] 数字千分位
来源：http://dali.guannengcc.top/Article/details/gtxsrcgcow.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gtobzldtpd.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gtkwlotdsm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtwgewdrzv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtbeuruxlr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gtxqpinsmy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gtdypdbrcq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gtlgolmhjw.html

C#:   1234567.ToString("N0")
来源：http://dali.wangshuangyany.cn/Article/details/gtjefryhfg.html

[E17] 首字母大写
来源：http://dali.andypj.xyz/Article/details/gtxuaftxhc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gtnstdrhzq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigfzy.top/Article/details/gtugflmbbw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtmepssnws.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gthrcvvikv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.c1oappe.top/Article/details/gtgcnvgcri.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtaejtmrcw.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtingslinr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gtqmzrjlgv.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gthkvxyyll.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gtpyuerinq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gtdddpzjim.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtpqcxcylu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtlyrsmuyw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtynvsnbti.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtaokunirp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shangyingyoupin.top/Article/details/gtepuyycsi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gotoacloud.top/Article/details/gtrrkfemqm.html

[E19] 多行文本按行拆分
来源：http://dali.0kj1m.cn/Article/details/gtdzfmwpfx.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtnsbqdeid.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtezjibson.html

JS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gttfozbdia.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gtkswjqiif.html

Java: s.lines().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtxcmiojcx.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gtvkogilwb.html

Ruby: s.lines
来源：http://dali.shzxlz.cn/Article/details/gtvarpsbwk.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gtgfqqbqxz.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtogyntymw.html

Py:   if not s:
来源：http://dali.haohaochexian.top/Article/details/gtyugamqpn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sxryk.cn/Article/details/gtczicitjs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gthwzhhyin.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gthnaaxrhx.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtkjucejlc.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gtdgpuxezh.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtvubdlnzz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gtisytziap.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gtisdjshvj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gtkxoyurgr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtmzctmwbj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gttdizdwqa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtpzopplpp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtcmanfjnh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gtdssbhtvp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtcfmptmkj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtaqizmkzh.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gtwsmnnell.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gtqhmbzlvj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtqgxkdyaa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gthczlokjq.html


<!-- 参考信息 -->