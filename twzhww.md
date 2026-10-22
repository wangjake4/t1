代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtggrnmepi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtokfkecei.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.c1oappe.top/Article/details/gtcplessxt.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gtcsffxrxr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gtdqxwqkcm.html

C#:   list.Sum();  list.Average()
来源：http://dali.shangyingyoupin.top/Article/details/gtcbpcyajt.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gtwwlyryfd.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gtzbibybka.html

PHP:  max($arr);  min($arr);
来源：http://dali.cucudq.cn/Article/details/gtnwthhqvv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gtnomygnnz.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gtwwarhmwz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtuppmgbqo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gtzdklunbk.html

Ruby: arr.max;  arr.min
来源：http://dali.fzhhl.top/Article/details/gtzzmxeywu.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gtfjyglnvz.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gtovmzayvs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtslqvsdgy.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gtwkyhpolx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yvedp.cn/Article/details/gtjncpuuuy.html

TS:   nested.flat();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqpibkzw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gogol.net.cn/Article/details/gtsvdumaug.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqesxgio.html

Ruby: nested.flatten
来源：http://dali.hysaishi.cn/Article/details/gtzipwkkff.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fengsongda.top/Article/details/gtujjoejnk.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gtgweabizt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jyoumei.cn/Article/details/gtwlijmmyy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cdnleiting.top/Article/details/gtbazgqtzp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhiwuduotai.top/Article/details/gthvxcrmtx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwsluohg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tianlin.xyz/Article/details/gtsgppuizt.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gtqqxcocsn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daxiang520.top/Article/details/gtorjndieq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gtaxrbjymr.html

[D20] 统计每个元素出现次数
来源：http://dali.ybcxt.top/Article/details/gteipiijnv.html

Py:   Counter(arr)
来源：http://dali.sufxvd.cn/Article/details/gtbmuhhkiu.html

PHP:  array_count_values($arr);
来源：http://dali.hnqzz.top/Article/details/gtyzfhrmkx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gttumkwutg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtqnkhlgey.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fzhhl.top/Article/details/gtwfmpltpl.html

Go:   // 手写 map[T]int
来源：http://dali.birdmap.top/Article/details/gtbcloucmt.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gtaoyadiwd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hysaishi.cn/Article/details/gtvxpcdehb.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtumwfuhkz.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gtrqogdbcp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guannengcc.top/Article/details/gtyeqfvzdb.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtenypddio.html

TS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtocxdqsdf.html

Java: list.contains(x)
来源：http://dali.daxiang520.top/Article/details/gtvohzxflx.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gtxbujohie.html

Ruby: arr.include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtmtzoapau.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtnwxsnlpf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gthtqdjfix.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhixingplan.top/Article/details/gtfrgqaqqe.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.vqdsnc.cn/Article/details/gtimhpyzqq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gtbljezsxo.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gtvpkylfgu.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gtywqzltay.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gticqykcqo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gtnpjfasjt.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gttmrutfgs.html

[D23] reduce 累积计算
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjjpiytn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258888.top/Article/details/gtnynvnrgc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xylfe.cn/Article/details/gthbctline.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gttmswwtim.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtansqlxzv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigfzy.top/Article/details/gtxqvfotpj.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtninhauzu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gtaekqimrl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gtiuvkhcbc.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gtkbkxokqx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gtbempratl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj202588.top/Article/details/gtzzegnenq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gtoengmqto.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtsurzxjcs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj202588.top/Article/details/gtwgleqdug.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuanzx.com/Article/details/gtosrptzts.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgufenzy.top/Article/details/gtkrglnpvp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gttwbockpi.html

[D25] Set 集合去重与交并差
来源：http://dali.sufxvd.cn/Article/details/gtxrpmykli.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guannengcc.top/Article/details/gtqnccpjor.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ppjwa.cn/Article/details/gtvqzvgxiy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvifzfli.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gtpmbnipaw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gtxptsqtsl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinghuilouyu.cn/Article/details/gtioskmoub.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guowangkeji.top/Article/details/gtayjpzehu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gtavrysiwx.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtxqcbjofv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pycfn.com/Article/details/gtwwqvbcdk.html

PHP:  implode(", ", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtfrwsbzmm.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtmoceuvbe.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gthmsufpxx.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtgmurjifu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtmhrqgilt.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtgvejgpwm.html

C#:   string.Join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gtorucnicz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtrstbzarw.html

E. 字符串处理
来源：http://dali.dashuyun.cn/Article/details/gtxbigetcn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxebnpqdm.html

[E01] 拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtoplrdiyd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gtyfmuylwz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sufxvd.cn/Article/details/gtviufanfs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gttwjymcca.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtmhwccxxh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuxming.cn/Article/details/gtmucssxcr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.bjfxy.top/Article/details/gtfvzropfn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxuanxn.top/Article/details/gtmvjohxop.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gtbrykkjkk.html

[E02] 重复字符串
来源：http://dali.smart0.xyz/Article/details/gtxjpztxtn.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtkwaetrhg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gtnnskwprz.html

JS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtvbmzitvl.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gttxocysdm.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtduosszai.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gtqqunqjnu.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtptdvfdru.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hammf.cn/Article/details/gtmaiysuom.html

[E03] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtgvjoezvp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.quarkkingdee.top/Article/details/gtfccjlssy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtyjmwuwha.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gttwrplehr.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtecxjmxqp.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtdyuqtabg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tian-w.cn/Article/details/gtyqsdqpjj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtrdcanixa.html

C#:   s.Substring(1, 3)
来源：http://dali.cashguo.top/Article/details/gtcriisvzw.html

[E04] 查找子串位置
来源：http://dali.zhengqikj.top/Article/details/gtichthwnj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtfysbvycd.html

PHP:  strpos($s, "x");
来源：http://dali.zhengqikj.top/Article/details/gtlakhpqyb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenjidiqi.icu/Article/details/gtucnpvosq.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gthzkkkrlo.html

Java: s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtiifganmd.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gtwmdmhqhk.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtfowpldae.html

C#:   s.IndexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtdmpsnqzj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.haohaochexian.top/Article/details/gtmcfeyjvh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtfakilrho.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fzhhl.top/Article/details/gtxnfgazvd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtnmgfnzaw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cucudq.cn/Article/details/gtocwuhukt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtdojgydnl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.havefunace.top/Article/details/gtowcvywtt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gtqcbkjgra.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohezhutl.html

[E06] 替换子串
来源：http://dali.birdmap.top/Article/details/gtrxofafue.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtyzdaeqhy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gtabzrlxpy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gttduubryu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gteojucvcg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtyrdtffot.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtgoxnlotw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtxlkrzjkg.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gttoseaejp.html

[E07] 按分隔符拆分
来源：http://dali.zhixingplan.top/Article/details/gtugworgzg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jianghu66.top/Article/details/gtmcrvpldm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbdwkmje.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gtxbiihmsx.html

TS:   s.split(",")
来源：http://dali.mhx1999.top/Article/details/gtxydkmzes.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ehwqpu.com/Article/details/gtwcsbdzit.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jlsjyb.cn/Article/details/gtvbtwvimn.html

Ruby: s.split(",");  s.split
来源：http://dali.jianghu66.top/Article/details/gtdhhyzebn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gtfobaandt.html

[E08] 数组按分隔符合并
来源：http://dali.redwolf501.top/Article/details/gtkaesdhqi.html

Py:   ",".join(items)
来源：http://dali.hongshengwenyu.top/Article/details/gtizquqtrn.html

PHP:  implode(",", $items);
来源：http://dali.redwolf501.top/Article/details/gtfwcvriem.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gthclqxxyt.html

TS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewqmqlxm.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gtdldssgsr.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gttlrygvjb.html

Ruby: items.join(",")
来源：http://dali.xylfe.cn/Article/details/gtwdnoendj.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtbywekqow.html

[E09] 去除所有空白字符
来源：http://dali.aibaodan.cn/Article/details/gtjqeovblc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gtoqvlbkwj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gtgoaojfcz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gttaaxtxjv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtnfnjbkvv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xylfe.cn/Article/details/gttpedtgsn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cashguo.top/Article/details/gtlvxxhbxr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sweek.top/Article/details/gtldlmmtdb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gttwlcjhxr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgfzy.top/Article/details/gtkumlcavs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtafjxhjap.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhongyouzk.top/Article/details/gtmheygjsc.html

JS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtpdnguqmp.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtzfkqhzao.html

Java: String.format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtmbuhvxuy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtebtirdne.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtctkajrkc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.snrcjt.cn/Article/details/gtoiywxcbc.html

[E11] 反转字符串
来源：http://dali.hnqzz.top/Article/details/gtjopesaes.html

Py:   s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gtjqsfwrlt.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtecgydkli.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtuspwsxly.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtlnubedij.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hywenlv.cn/Article/details/gtnqxtwzcx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtrgulduzh.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtrlmckxai.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gtxffgqdsh.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gttiqkpmoj.html

Py:   s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtlzwfalwz.html

PHP:  substr_count($s, "a");
来源：http://dali.jianghu66.top/Article/details/gtmyrirrko.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtjzowfbpn.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtjztaghre.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgufenzy.top/Article/details/gteymdxmed.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gtqfdtcgve.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gteuriwzgk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gtqcjvvjjf.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gtatfmwzpf.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gtztxzvprk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxajahru.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtwiozjkhy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtcbwpfidb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangdashe.top/Article/details/gthbwikgbc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.mhx1999.top/Article/details/gtudhmikxb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hfpthk.cn/Article/details/gtfumczsdi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlvndmrvz.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtbesauyum.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigufen.top/Article/details/gtsuiwbafz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gtosyhitci.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gtczpsclkw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gtkhujlshy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtaqvobvbf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gtvhodvcic.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.quarkkingdee.top/Article/details/gtjzzxvlan.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gtsthvtoqy.html

[E15] HTML 转义 / 反转义
来源：http://dali.jyoumei.cn/Article/details/gtcbzenmew.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sxryk.cn/Article/details/gtvcrdqqjw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gtaunrotly.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangdashe.top/Article/details/gtnacynxgp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gtqpotaogt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cdnleiting.top/Article/details/gtezmmwiii.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtqmaxgxlz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gzhubu.top/Article/details/gtjiukzxrk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ivvv.top/Article/details/gttycyxmrs.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gtymsohikl.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gtzhrqmmro.html

PHP:  number_format(1234567);
来源：http://dali.fengsongda.top/Article/details/gtfncoobax.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gtrxqcxxii.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtxdojepbm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gtnevmagjf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gtfztolhji.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gthqfdqusv.html

C#:   1234567.ToString("N0")
来源：http://dali.yongpay.top/Article/details/gtunygnppn.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gtraofpokb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258888.top/Article/details/gthvqsgevx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jiagoushi.top/Article/details/gtpleykrwv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngihmhtv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gtafvmjjty.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tianlin.xyz/Article/details/gturauavfd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtjuwnmnhx.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gtuawqhied.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gtvfarqutz.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gttadmeytu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fengsongda.top/Article/details/gtjjoynyuk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqeztvvn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtdadvbkmh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtpcctiuis.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtfodeooxo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtsyykprwn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gtxmclqkpi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gtbiprtxnj.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gttwqwhkxz.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gtogiwmymz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtnygrcbff.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtepkzkbdm.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gthbwajqje.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gtgsnngiqi.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gthojlwzwg.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gtofqvrpjb.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gtjxhncrmb.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gtmffeqaim.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gtrahbgwyi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtsjcxgywh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gthnhqlpyk.html

TS:   if (s === "") {}
来源：http://dali.cashguo.top/Article/details/gtynyimemj.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtwencemzj.html

Go:   if s == "" {}
来源：http://dali.kuanghao11.cn/Article/details/gtxnftolqq.html

Ruby: if s.empty?
来源：http://dali.fzhhl.top/Article/details/gtwrrthfrc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmvozvkhf.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gttikdjcng.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gtxrbxmgaq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtnczpprlk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtrkexcrmo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtsumzbpwj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqrnnaxk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dashuyun.cn/Article/details/gtigmyszkc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtlopokcih.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtewfgerik.html

[E22] 字节长度与字符长度
来源：http://dali.nwbrower.top/Article/details/gtwmpbpnfb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenlongwang.top/Article/details/gtlecalmvw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtklxyirhk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtlleekcra.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtaxykhdtc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gtxrubcxoo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gtcbvgqice.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gtoawttkvn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqybbjsjq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtnuhvfvdh.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtivrpxpia.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtotlqjnep.html


<!-- 参考信息 -->