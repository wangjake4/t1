代发 wailian999

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gtrauovmuz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpguibypu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuedvbydm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gtzsrywyrl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gtnsafyboh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtxvlberkt.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gtgesznpto.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgaucwvw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gtjeglndhx.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtkieagksj.html

Py:   Counter(arr)
来源：http://dali.yvedp.cn/Article/details/gtevlclues.html

PHP:  array_count_values($arr);
来源：http://dali.gzhubu.top/Article/details/gtokbxpahl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gtsjreldma.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtgeiooecc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.andypj.xyz/Article/details/gteemskmjv.html

Go:   // 手写 map[T]int
来源：http://dali.pengpengdd.cyou/Article/details/gtlnpxzwqn.html

Ruby: arr.tally
来源：http://dali.zhiwuduotai.top/Article/details/gtsidqscvc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj202588.top/Article/details/gtqqrxymhh.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gtjfohsiqu.html

Py:   x in arr
来源：http://dali.yj20258.top/Article/details/gtoprfrhud.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gtelcjaere.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtaofldlfa.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtwnokwgpm.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gtalcaesjz.html

Go:   slices.Contains(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtnhwlbscr.html

Ruby: arr.include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtzjzxisyi.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gttlqgxple.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyanihdz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtfftelwbl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gtuvufxgpa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrekaogh.html

TS:   [...arr];
来源：http://dali.hfpthk.cn/Article/details/gtarvkcvsy.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gtiqhrafyx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sysykeji.top/Article/details/gtkpjcxfal.html

Ruby: arr.dup;  arr.clone
来源：http://dali.andypj.xyz/Article/details/gtljnfirxf.html

C#:   new List<int>(list);
来源：http://dali.haohaochexian.top/Article/details/gtwxqwxwdm.html

[D23] reduce 累积计算
来源：http://dali.yanxiufei.cn/Article/details/gtbkomxmno.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gtcefsgshn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jlsjyb.cn/Article/details/gttukevauy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtchrwtfug.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gtegbwcelj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gturbqfrrt.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gtdzseoyse.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtzwpzkltk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gtqwjmwdco.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gtbwlkkamk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gtvgffzkld.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tanke756.top/Article/details/gtwyebisuc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sweek.top/Article/details/gtywmmrgkm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtqsjcjvhp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gtjgkvvknm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzhxynnt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtvgofprnu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtqrqxlahn.html

[D25] Set 集合去重与交并差
来源：http://dali.0kj1m.cn/Article/details/gtmwdwizet.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gtgckoasdt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.quarkkingdee.top/Article/details/gtljxupswh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gtqugwcbtd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gtofjrzniu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gtbeevppve.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hongshengwenyu.top/Article/details/gtdhqupnak.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gotoacloud.top/Article/details/gthjzwtqlo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gtpayaqcvl.html

[D26] 数组转字符串
来源：http://dali.jyoumei.cn/Article/details/gtmvhcaohh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gtpvzbeyrc.html

PHP:  implode(", ", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtfcnffcch.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtqohoqjdo.html

TS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtfismoepf.html

Java: String.join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gtzpydchdj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ydzc1.top/Article/details/gteevosybc.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtxjwrsvot.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtgzrtbpgc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtcxkiizwh.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gtftgbvjan.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfxvgojlk.html

[E01] 拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtsmanbdns.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tian-w.cn/Article/details/gtmnamsddg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenlongwang.top/Article/details/gtxnqnrfrb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtchwevvrw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtkzlpchbx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fengsongda.top/Article/details/gtgcvbnmju.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shuidangran.top/Article/details/gtiebdxvqa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gtxellfbhj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtnsectjtt.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gtpclzkiqv.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtpokwzdfd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnqzz.top/Article/details/gtliummedt.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtyidbpdxo.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtuchtcgyb.html

Java: "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtizhbzsya.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shuidangran.top/Article/details/gtpqjlgsnc.html

Ruby: "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtuawogesg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gtyqghanjz.html

[E03] 截取子串
来源：http://dali.meibo888.top/Article/details/gtqjuwfyeo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jianghu66.top/Article/details/gtzocgexde.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtqhdjpsnh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtupurjfaa.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtqcbfhoqh.html

Java: s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtryvhrccb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnqzz.top/Article/details/gtzmofatsw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cqqwz.cn/Article/details/gtvrqgzxzy.html

C#:   s.Substring(1, 3)
来源：http://dali.sxryk.cn/Article/details/gtxmcawknh.html

[E04] 查找子串位置
来源：http://dali.svipenyu.cn/Article/details/gtnockwphn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtskfnwdbm.html

PHP:  strpos($s, "x");
来源：http://dali.yangfankeji.com/Article/details/gtklneyiib.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sufxvd.cn/Article/details/gtcodybfyx.html

TS:   s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtzgmuiahl.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtcotqckgs.html

Go:   strings.Index(s, "x")
来源：http://dali.aibaodan.cn/Article/details/gtlyexjvkt.html

Ruby: s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtjcvlpgex.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtsfmhjfbt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yonumen.top/Article/details/gtvxbwiynv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.snrcjt.cn/Article/details/gttlhtklev.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ppjwa.cn/Article/details/gtogmfppjd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtabqbvhmg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gtxgxwepsg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gtyikovyxr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gtjggvaxih.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhongyouzk.top/Article/details/gtktpmxzpy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtmfnefnlg.html

[E06] 替换子串
来源：http://dali.hysaishi.cn/Article/details/gtdplnegxt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtzahmzvzl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sweek.top/Article/details/gtymrvhrwp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtphpvquua.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtohzhzslh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtpldvubea.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtbhhaqyno.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtscmsjwpz.html

C#:   s.Replace("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtadewugua.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gtixauoplh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dianchejie.cn/Article/details/gthltwynqo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nwbrower.top/Article/details/gtipacdvtf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gtjfehzzip.html

TS:   s.split(",")
来源：http://dali.yonumen.top/Article/details/gtmtdbwcsf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gtfsmllddq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dashuyun.cn/Article/details/gtgkpcjgvk.html

Ruby: s.split(",");  s.split
来源：http://dali.sweek.top/Article/details/gtmlhpvjxd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gtxdsfkwbt.html

[E08] 数组按分隔符合并
来源：http://dali.zdqjudy.top/Article/details/gtwjemizxk.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gtwfhqutfd.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gtojjqznlv.html

JS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gtrzsvxekj.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtzlvtyyrk.html

Java: String.join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gtbjndkdhn.html

Go:   strings.Join(items, ",")
来源：http://dali.dianchejie.cn/Article/details/gtbngholai.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gttnwpvdzh.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqfnaztq.html

[E09] 去除所有空白字符
来源：http://dali.xuetiantiany.cn/Article/details/gtlsycqppm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgngnowxh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtehcwqdse.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtnikldpor.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmeclivoq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gthblcbeky.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gtbxeytihl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gtzbuylcyz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gtxkwtkrji.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gtdgnbitre.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtxdpvxyyu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shangyingyoupin.top/Article/details/gtrfjahbpd.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtqyaanqya.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gttcyqxwxv.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtjmtrumcf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtkjgjtpaa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtmhtkricm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gtosgipshf.html

[E11] 反转字符串
来源：http://dali.ppjwa.cn/Article/details/gtrdyrcfcb.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gtsdfrzbkl.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gtpulkcjyd.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtmsrpzjrf.html

TS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtqcfnprha.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.havefunace.top/Article/details/gtlbvtcigb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtlomebgqx.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gtwjdsfavz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gttmjxtuca.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gtwxeyoqmi.html

Py:   s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtlfsdgvdh.html

PHP:  substr_count($s, "a");
来源：http://dali.hywenlv.cn/Article/details/gtjqrfctmb.html

JS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtznifwliu.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtsjlpmcra.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gttcynwtql.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gtzlegmpnb.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gtpkancxcg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgfzy.top/Article/details/gtvhcofzjn.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gtrtqhjotf.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gtpcktsllj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtbkohvdtf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtqvaiezck.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtokwtfkff.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fengsongda.top/Article/details/gtxubydzxs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daria6918.cn/Article/details/gtxulsaawz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dianchejie.cn/Article/details/gtmkswooop.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gtktermnxu.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtopgtwwkj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.smart0.xyz/Article/details/gtocqhaiph.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gtqughhjfw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxuanxn.top/Article/details/gtxhjmxmeu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangdashe.top/Article/details/gttgywyoni.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gtytpxoubz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gtwsejzfbf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpsvzagd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gthueahpzq.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gtjcabtrci.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zycfv.cn/Article/details/gtrrlqemxo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gzhubu.top/Article/details/gtgldewlfi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtvvegzmdp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gtfrtwznir.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gtletmksmf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzsvrqqa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pycfn.com/Article/details/gtqknowrvf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jiagoushi.top/Article/details/gtklpiiuya.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtlpugdmwc.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258.top/Article/details/gtuqxrlrnk.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gtoewnwfob.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtqwrokmng.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtvtfomgxv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gtzhyxdgvd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gtcmrdwhlc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtmwejrelg.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gtrdwflebj.html

[E17] 首字母大写
来源：http://dali.sweek.top/Article/details/gtoayevnft.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gtwqjyvvem.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gtxeaudzjf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtcyjmmexg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtaikcmlpt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yueranfly.top/Article/details/gtnzrbvhtk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtxmsmsgod.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gtppridruq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gttbhibshj.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gtbltldpyc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sufxvd.cn/Article/details/gtlknlkofc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gtzivhikwd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtfiortfjl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtthfvzlob.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtjcgeuenc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtllekssrf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gtkmhqmqax.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shangyingyoupin.top/Article/details/gtdbmodaft.html

[E19] 多行文本按行拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjiujsgz.html

Py:   s.splitlines()
来源：http://dali.ivvv.top/Article/details/gtbsxzlofk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yueranfly.top/Article/details/gthzyqzmac.html

JS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtizaimygc.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtprwzodga.html

Java: s.lines().toList()
来源：http://dali.yuanzhike.top/Article/details/gtmbejhagh.html

Go:   strings.Split(s, "\n")
来源：http://dali.xziqi.cn/Article/details/gtujphygtf.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvexdhin.html

C#:   s.Split('\n')
来源：http://dali.jinqigfzy.top/Article/details/gtvfxdieqg.html

[E20] 判断字符串是否为空
来源：http://dali.ydzc1.top/Article/details/gtouqwzzha.html

Py:   if not s:
来源：http://dali.xinyue.icu/Article/details/gtqvdnznon.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gtoqnirpms.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsravaskq.html

TS:   if (s === "") {}
来源：http://dali.aizwys.cn/Article/details/gtobpqdgzz.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtceecypwg.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gtxndptklt.html

Ruby: if s.empty?
来源：http://dali.jinqigufen.top/Article/details/gtufskpqlr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gtlxkqjqxp.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gtsvvefttg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigfzy.top/Article/details/gtyynsajic.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtfoadmrri.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtimlxhwof.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gteimmawdi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtxahpytuf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gtgkggyexs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gthozviqfn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtoaazmzto.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gttcewikhn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gtugcjvvdp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtqwzozjeg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gtpujohdho.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtzmqzvtbw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtqgjtbesu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gtlqipyrzl.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtukwrfpps.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gtoecoqcny.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvfhfhikb.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwuuvvbov.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtkogbwqlb.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtdxvdidex.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gtefvfxdpc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtoxterltx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigfzy.top/Article/details/gtohsynewo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtmassxvhm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtickbkuun.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gtgvbmfzuc.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtumovzwpz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtxiagqbbi.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtbtjidtcu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gtnocactzr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtqzqnngva.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtuukdtybt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gterzmskba.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtxsexkzqp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangshuangyany.cn/Article/details/gthjpmsrcv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gtqwjqmysd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fengsongda.top/Article/details/gtxgjgklld.html

[F03] 写入文件（覆盖）
来源：http://dali.cheryme.top/Article/details/gtbqyaabew.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtgsipnhak.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtbaomexcb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtfplbmnzq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtabzvfyue.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gtvqgukzps.html


<!-- 参考信息 -->