代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gtgiivghfy.html

PHP:  array_merge(...$nested);
来源：http://dali.yvedp.cn/Article/details/gtlbkcairf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yvedp.cn/Article/details/gtnzgpktmt.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gtcjplvxcq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fengsongda.top/Article/details/gtsenrgqbb.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gtzibjxsru.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuptpjeqc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtcrfsoeor.html

[D19] 按字段分组
来源：http://dali.jlsjyb.cn/Article/details/gtbamncbpe.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gtzjxxljjh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgufenzy.top/Article/details/gtnttcehyq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gtlykoqdpw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtxnuyijup.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gtavkqvnum.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gthyvryczr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gtkpigsaui.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gtnbxolgzu.html

[D20] 统计每个元素出现次数
来源：http://dali.0kj1m.cn/Article/details/gtkuivvexs.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gthlzkxysj.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gtnydretym.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtfwnalcwa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtnsvqxypg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gtllohcmze.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gtvskxctmd.html

Ruby: arr.tally
来源：http://dali.ydzc1.top/Article/details/gtmhdewynd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gtvoaolztq.html

[D21] 判断是否包含某元素
来源：http://dali.ydzc1.top/Article/details/gtzczylhev.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtltezdcbg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gtpozfbxrg.html

JS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtmijhmsmd.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrupldzd.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtpxkdzmwn.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gtqfykwwja.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gtvsyotryz.html

C#:   list.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhsxpqze.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ehwqpu.com/Article/details/gtxzjnbeag.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtdrkjxyph.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gtbwfayocp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtdsloqhnl.html

TS:   [...arr];
来源：http://dali.birdmap.top/Article/details/gtzrpzchid.html

Java: new ArrayList<>(list);
来源：http://dali.zhongyouzk.top/Article/details/gtwiqsevvk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xziqi.cn/Article/details/gtbdyyfasf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gtcgeawvir.html

C#:   new List<int>(list);
来源：http://dali.bjfxy.top/Article/details/gtzzukbkvj.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gtbaxzslos.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gtrvqphwle.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnkahxoz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkyhpnup.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnigrksng.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gtrvpswdjk.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtakmeqgia.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gtwnwhapob.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.c1oappe.top/Article/details/gtfgewtgpw.html

[D24] 字典 / Map 基本操作
来源：http://dali.tanke756.top/Article/details/gtpwcvivgb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.svipenyu.cn/Article/details/gtripjetzy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gtakkugrex.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gtsazxccqz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtmjitwgyj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gtvxdkkgba.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daxiang520.top/Article/details/gtsofvhjuo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.andypj.xyz/Article/details/gtiriewyxg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.andypj.xyz/Article/details/gthmlpgzeh.html

[D25] Set 集合去重与交并差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjabryhmi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gtbhcxyzrl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gtrlaxylkj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gtswpchfan.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gtmhlkulio.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sysykeji.top/Article/details/gtsypvesaw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgncsglwo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tianlin.xyz/Article/details/gtfkkllmbn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtgzsbcmsk.html

[D26] 数组转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtmbhnluoe.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuvvmvbl.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtetizaxls.html

JS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtepufwwia.html

TS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtyeelhich.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtufsysenz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gaohongyu789.top/Article/details/gtppvkmugo.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtrnaqkbix.html

C#:   string.Join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtlnvlmzfd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfkckdkok.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gtpqkwxbhx.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqydjzlxc.html

[E01] 拼接字符串
来源：http://dali.yj20258.top/Article/details/gtgzkihlni.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gtbdbaxcue.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gtutxctgmh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtertnohpv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtgkoxrfns.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.bjfxy.top/Article/details/gtjhzrnjyx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtktoaiaxv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolkdfmnj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtnzqopqik.html

[E02] 重复字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtubxjrmml.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtgceqburo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtuygcmgjs.html

JS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtpvemvdjl.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtgfnvybkq.html

Java: "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtcemeoixv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gtspyojyzr.html

Ruby: "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gticknogwa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tianlin.xyz/Article/details/gtovjptauy.html

[E03] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtgjwfojyf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.0kj1m.cn/Article/details/gtdzefeifv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtprixtibq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtbeppizsg.html

TS:   s.slice(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtqehqujlm.html

Java: s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtopufjpem.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuxming.cn/Article/details/gtxqzcrppd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.smart0.xyz/Article/details/gtlwdmxera.html

C#:   s.Substring(1, 3)
来源：http://dali.316326.xyz/Article/details/gtgrhwuepw.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gtmqijoedb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtyuidkkus.html

PHP:  strpos($s, "x");
来源：http://dali.svipenyu.cn/Article/details/gtafcfdykb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.smart0.xyz/Article/details/gtjcqzwokh.html

TS:   s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtwcuaecht.html

Java: s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtllvicsrj.html

Go:   strings.Index(s, "x")
来源：http://dali.yueranfly.top/Article/details/gtdlufipom.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtolarratf.html

C#:   s.IndexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtgcgnamsp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gtgcvcxtlm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fengsongda.top/Article/details/gtplrhcfms.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigfzy.top/Article/details/gthttmolrq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtmzajelpx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdztuwole.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gtidgggkwd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gotoacloud.top/Article/details/gtklxmdgld.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtwyjsziih.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtlvjrhrwc.html

[E06] 替换子串
来源：http://dali.gotoacloud.top/Article/details/gtwpkfqxnf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtwyaphese.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlihuffq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gttoytygnb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtccgpgrql.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtshqdtjyf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtyejfigcp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtnmmutzvv.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtecffawmq.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gtlsuvehwd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigufen.top/Article/details/gtjcsmkquz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtnuitbbhd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gtnulnikrq.html

TS:   s.split(",")
来源：http://dali.yvedp.cn/Article/details/gttdzgucwg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.haohaochexian.top/Article/details/gtrmygoamd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dashuyun.cn/Article/details/gteaxyswst.html

Ruby: s.split(",");  s.split
来源：http://dali.hnxiangtu.top/Article/details/gtxyxssdos.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gtpjskmuqo.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gtvmeitwfc.html

Py:   ",".join(items)
来源：http://dali.andypj.xyz/Article/details/gtwfwegpnv.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gttambsdkh.html

JS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gteumhezjo.html

TS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtlpgzayeq.html

Java: String.join(",", items)
来源：http://dali.yueranfly.top/Article/details/gtyvplougt.html

Go:   strings.Join(items, ",")
来源：http://dali.snrcjt.cn/Article/details/gtntatyjrd.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtwsfezpzp.html

C#:   string.Join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gtfbvroagf.html

[E09] 去除所有空白字符
来源：http://dali.meibo888.top/Article/details/gtoqocajmz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gtddreealo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gtunngnazb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gtpkrxkqof.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtqrisomdo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gtqourgnas.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gtdzsldhbq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gtpydtazlj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gttcperpmj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.bjfxy.top/Article/details/gtnzbryuci.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtquajymss.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fengsongda.top/Article/details/gtbripihoo.html

JS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtmcituhqy.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gttmhnvgqw.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtynxamiov.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtdwegyqgj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtwrvoztsn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gtnqcxtkhr.html

[E11] 反转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtgmkqyimh.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtnvwhiiff.html

PHP:  strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gtcgwjsjkt.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtepjrrrnd.html

TS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gthahszmyf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gtqcatsojy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gtkgmyyycb.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtxhhhjspg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gthomkzkpn.html

[E12] 统计某字符出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftqebcfd.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxtnuebg.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258.top/Article/details/gtnvkruqqe.html

JS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtgwkformg.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtmbwnjccr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnxiangtu.top/Article/details/gtaypnzyuj.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gtoekbxyfd.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtkytmuhks.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guannengcc.top/Article/details/gthnowpqjh.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzyctqni.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gtnakweaxl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sufxvd.cn/Article/details/gtkrqbiwxj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gthnyqvctz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtrmnjwjcw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtqurxmmby.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nwbrower.top/Article/details/gtljevqjbh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gtusqzmeft.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gtisexmpty.html

[E14] URL 编码与 Base64
来源：http://dali.jlsjyb.cn/Article/details/gtyuindlld.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daria6918.cn/Article/details/gtmpiirayq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.havefunace.top/Article/details/gtoppuguit.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gtahjvxino.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gtxmdatifo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtcxmskulq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gtkqyltyqu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuxming.cn/Article/details/gthyxvghkh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtfxrnnpvs.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtljexniol.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gtvztsdmkj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gtqokysxoy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gtotjaoupd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daxiang520.top/Article/details/gtdmmlgmxv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gtpqelsfkn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xylfe.cn/Article/details/gtvgttdjxh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gtvjswkzza.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gthnehztqr.html

[E16] 数字千分位
来源：http://dali.yj20258888.top/Article/details/gtiojylpai.html

Py:   f"{1234567:,}"
来源：http://dali.ybcxt.top/Article/details/gtliyjlhcl.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gtozciacjc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoisbvavx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtmtwnscxi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zycfv.cn/Article/details/gtjokzfovf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ehwqpu.com/Article/details/gtrizpalpu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.smart0.xyz/Article/details/gtrkfqwixc.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gtcxryurij.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gtomldrxfx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gtxmhukgec.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gtjxgzxawa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwscfoove.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gthzzbcwfc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtsafvjfgp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gtoqabqvim.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gtbikyrtse.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gtxnzaipco.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gtgaaychqc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.bjfxy.top/Article/details/gtpdaeoslh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nwbrower.top/Article/details/gtmdpdgrjz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtwscqxzxr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtfkfczyav.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtiuequyot.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtjohnregc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gthocmbkcg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gtadjoceti.html

[E19] 多行文本按行拆分
来源：http://dali.yuanzhike.top/Article/details/gtvpkqilkq.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlcieesx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gtmztgskvi.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtmbvedzet.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtxnrbyjnv.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtiduxmino.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtavcgjwxx.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gtsagxwgbv.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gtutudnnlu.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gtudccpwpi.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gtaumjpdaz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gtctvdlyym.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gtzkzxrmgl.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gtibntbtwe.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gteqfrcqku.html

Go:   if s == "" {}
来源：http://dali.yj202588.top/Article/details/gtkbubufjn.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gtkdzarqsr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gtdrkqxjgy.html

[E21] 超长截断加省略号
来源：http://dali.birdmap.top/Article/details/gthoxyouhv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gtixdyeggd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtfscylyah.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtimyfzhxc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtrogrocrd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtamwlgqqt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gtgsmqhkvw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtvpepetlv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtplroqsjq.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gtairptzag.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gttjgjpuds.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtugfpkxao.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gthaktqjpi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtlevavybl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pycfn.com/Article/details/gttgjivlxb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gtxojwesbm.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtylindapj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aibaodan.cn/Article/details/gttjvkhbgr.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gteczdgfem.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gtawzvkmoy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpxmlzszg.html

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gtqywajklt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cucudq.cn/Article/details/gttyvdbrwq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtyveqcrxe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sysykeji.top/Article/details/gtwuhrtalm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtgzikiplu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtkfhawhjk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gtwybjofiu.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gtfuqwumuj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtgvvpakij.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtheixipmp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gtrseiaoqs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtxmqpdpok.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtbiygvxat.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtgqytyqfr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtgigdvlcf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gticvvvtgr.html


<!-- 参考信息 -->