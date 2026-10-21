代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gthhqohxnt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gtdabtuzpm.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gtfpwswieu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gtrevvrmre.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuanzx.com/Article/details/gtudtsstih.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gtqpeeuilh.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gttndfmfxz.html

PHP:  array_count_values($arr);
来源：http://dali.tanke756.top/Article/details/gttqukmsle.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygsjxzyz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtcehfvfsq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gtqdeemfph.html

Go:   // 手写 map[T]int
来源：http://dali.aizwys.cn/Article/details/gtadltywsy.html

Ruby: arr.tally
来源：http://dali.jinqigfzy.top/Article/details/gtipkkvfkf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jiagoushi.top/Article/details/gtklajpqdd.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gtncogwwhh.html

Py:   x in arr
来源：http://dali.ivvv.top/Article/details/gtyvayzrzx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gtrsqyqfmd.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtzelenzcj.html

TS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtzlfggmrw.html

Java: list.contains(x)
来源：http://dali.xylfe.cn/Article/details/gtkcwtfxtq.html

Go:   slices.Contains(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtgegyczfe.html

Ruby: arr.include?(x)
来源：http://dali.cucudq.cn/Article/details/gtotogcaup.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtkhmdqfao.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhixingplan.top/Article/details/gtgiytozat.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gttnyqdveh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gtwczelqcc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.bjfxy.top/Article/details/gthodzxmkp.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gtfkceiynm.html

Java: new ArrayList<>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtzqktzujm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnqzz.top/Article/details/gtzeftpnvt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gtfzklsjwl.html

C#:   new List<int>(list);
来源：http://dali.yueranfly.top/Article/details/gtyixewmht.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gtzozvsnas.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gtymgmiret.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gttfanxkcu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtbgnhtnti.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gtbagbolip.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuetiantiany.cn/Article/details/gtsjheukjr.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtkwxxqghd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gtktgvponk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gtctynbafo.html

[D24] 字典 / Map 基本操作
来源：http://dali.yongpay.top/Article/details/gtshshaeem.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xylfe.cn/Article/details/gtalljjdlg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhoulong.xyz/Article/details/gtsmnjtlto.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtshxzwazl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtxszskoab.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cqqwz.cn/Article/details/gtjwncnvhr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenzaomai.com/Article/details/gtipxljhyt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gtmsdfmqhd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gtpcggapfs.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gtplzpmhec.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gtoeqnpgfp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gtityuwpyn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zdqjudy.top/Article/details/gtqozhqzum.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hysaishi.cn/Article/details/gtymufktsj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuanzhike.top/Article/details/gtxbssvqpp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cashguo.top/Article/details/gtsqvwiawp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.bjfxy.top/Article/details/gtfhdloohx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gtifgslfpz.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gtzafrthri.html

Py:   ", ".join(map(str, arr))
来源：http://dali.0kj1m.cn/Article/details/gtdfsycfia.html

PHP:  implode(", ", $arr);
来源：http://dali.daria6918.cn/Article/details/gtlrxwndwa.html

JS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtikdgriuh.html

TS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtjystpqju.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtlmdviqkh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gtfmloovxr.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtenuycyzd.html

C#:   string.Join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gtoqmlaise.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtcpycauug.html

E. 字符串处理
来源：http://dali.tanke756.top/Article/details/gtoeuvnevm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwuvtjnlj.html

[E01] 拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtlywmwgno.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gtihjvgwct.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sxryk.cn/Article/details/gthyllngvx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtwzyyqaqe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtpquwmnce.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gtltoxbuhx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ehwqpu.com/Article/details/gtsyoxpcsr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cqqwz.cn/Article/details/gtgncmgjht.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yonumen.top/Article/details/gtozpsuxam.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gtxmgqxdvm.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtshwnudkm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tian-w.cn/Article/details/gtuticicwa.html

JS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtziloyheh.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtyybugnjf.html

Java: "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtmqblgmhi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gtxfshamss.html

Ruby: "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyfjhbli.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daria6918.cn/Article/details/gtkoperbiy.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gttgwlotqp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yongpay.top/Article/details/gtekaccift.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtbsuupqxf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtozxfilwz.html

TS:   s.slice(1, 4)
来源：http://dali.cheryme.top/Article/details/gtztgivcww.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gteifvdscz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gthkhjscnn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtztydltcf.html

C#:   s.Substring(1, 3)
来源：http://dali.sysykeji.top/Article/details/gtgziyxlbo.html

[E04] 查找子串位置
来源：http://dali.chenlongwang.top/Article/details/gtqoesxkft.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtpuglfrbv.html

PHP:  strpos($s, "x");
来源：http://dali.xziqi.cn/Article/details/gtkimotuih.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhongyouzk.top/Article/details/gtqlpzfazr.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtfeufaugd.html

Java: s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtrqyukngw.html

Go:   strings.Index(s, "x")
来源：http://dali.ybcxt.top/Article/details/gtwdmyxeaz.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewvbqlue.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtmjxahxwo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tanke756.top/Article/details/gtyalkuybg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtafufzumf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfixkupk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpvjyhcn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hammf.cn/Article/details/gtjppggfxf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtdesaszyi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shangyingyoupin.top/Article/details/gtnoygffuw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gtagdbymuz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtxatceyuj.html

[E06] 替换子串
来源：http://dali.ivvv.top/Article/details/gteyhudcrr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtfzjhjrcz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.snrcjt.cn/Article/details/gtskpigdup.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtzggjixpn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtfusuitoq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gttisoqxyc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtikjapiix.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtfqbuxvao.html

C#:   s.Replace("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtxqtzkcwc.html

[E07] 按分隔符拆分
来源：http://dali.chenzaomai.com/Article/details/gtxpgbbvrv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.svipenyu.cn/Article/details/gtwmfesvzc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nwbrower.top/Article/details/gtxmutslzs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shzxlz.cn/Article/details/gtlmlumocx.html

TS:   s.split(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtvbnfjsnh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxuanxn.top/Article/details/gthcbdedca.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yueranfly.top/Article/details/gtdjpireju.html

Ruby: s.split(",");  s.split
来源：http://dali.bjfxy.top/Article/details/gtmonnuwpr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cdnleiting.top/Article/details/gteefvwtyx.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gtyyvalfei.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gtcayidlkf.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gtusedtevd.html

JS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtplcnvpyk.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtnrulowuh.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtwwxvbsgb.html

Go:   strings.Join(items, ",")
来源：http://dali.fzhhl.top/Article/details/gtphzzssga.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtabjsikmj.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gtsuvbkxxx.html

[E09] 去除所有空白字符
来源：http://dali.jiagoushi.top/Article/details/gtymuekuxv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gtnukshtxg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxteayhuk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtrsheakoj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtewxvidsn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtqvobxhgy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.iojbl.cn/Article/details/gtbozweazw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gtqlzibdfp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yonumen.top/Article/details/gtdyjdtmjg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gtrqqfqjyr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtkstemoqa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.andypj.xyz/Article/details/gtcvsivsur.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngvojggc.html

TS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtthtmwkwr.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtqdojytej.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtjqvirwli.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gthiyybnmj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfprluavx.html

[E11] 反转字符串
来源：http://dali.snrcjt.cn/Article/details/gtfegwhydb.html

Py:   s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtnlcmkywo.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtlafovvra.html

JS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtvbcqqcyb.html

TS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtkarrmhbs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gttpmzwpbt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtjmbahepd.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gtwlegehbl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklzsekik.html

[E12] 统计某字符出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtmkjnhkeh.html

Py:   s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtjbabbufu.html

PHP:  substr_count($s, "a");
来源：http://dali.xylfe.cn/Article/details/gtzybhcrnd.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtzuaolwtv.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtmwehdwbe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gtidzzqhua.html

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gtzhshfboc.html

Ruby: s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtaoobsljy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gtnjputpdi.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtbhzqlqsu.html

Py:   for ch in s: print(ch)
来源：http://dali.cdnleiting.top/Article/details/gtnnwnanlr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuoytupg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtvkwgrlvb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtdqxlgxsm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtbouxegpm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnqzz.top/Article/details/gtdgnhwbnj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuanzhike.top/Article/details/gtkrqnvvew.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtzlodkszt.html

[E14] URL 编码与 Base64
来源：http://dali.iojbl.cn/Article/details/gtvzxtbcch.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gtkuwqorhi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gtzjfeotlc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gtrhifbuxw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtmtjaznbo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gtmnhhbfux.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.meibo888.top/Article/details/gtnkakihje.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gthfvzbnyk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gtlmmyflrb.html

[E15] HTML 转义 / 反转义
来源：http://dali.zycfv.cn/Article/details/gtdcfxvkpy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gtjgklxara.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yonumen.top/Article/details/gtrydgdcki.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tianlin.xyz/Article/details/gtmvxdazuf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gtawryfvdq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gtekyectpe.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gtmlstnwwi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.0kj1m.cn/Article/details/gtoxdjwfhw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.mhx1999.top/Article/details/gtxeqiapre.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gtvmvesfio.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gtzblbnbiw.html

PHP:  number_format(1234567);
来源：http://dali.hnqzz.top/Article/details/gtuyuztygd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtllvphmqk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtehojooui.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjsxmxpq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtcwklmo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj202588.top/Article/details/gtvilxpgsr.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gtmvnxxopp.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gtegennfoo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gtbhtkrimk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nwbrower.top/Article/details/gtymzbykff.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtepeidxqx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtdxobhako.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gtcfmvtihv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtnyczysok.html

Ruby: s.capitalize
来源：http://dali.meibo888.top/Article/details/gtsqilollm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gtduqmlthd.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gttpbzgxbb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gtgpnsygjt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daria6918.cn/Article/details/gtakhgqzox.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtvqzgnvft.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtjuswspda.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtepsxlyyi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtxtfcixnj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzwcgvhb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxevjdukt.html

[E19] 多行文本按行拆分
来源：http://dali.tian-w.cn/Article/details/gtsqohdqxi.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gtjegtvpuc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gtdbbsuepw.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gttkqujsky.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gttawpjotn.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gttfnosowj.html

Go:   strings.Split(s, "\n")
来源：http://dali.cheryme.top/Article/details/gtttigvzmt.html

Ruby: s.lines
来源：http://dali.andypj.xyz/Article/details/gtdpxmwojf.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzaxdbaw.html

[E20] 判断字符串是否为空
来源：http://dali.yueranfly.top/Article/details/gtlutczmbo.html

Py:   if not s:
来源：http://dali.shzxlz.cn/Article/details/gtxvmwojsf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyiimtsnr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gtfmlqyzxk.html

TS:   if (s === "") {}
来源：http://dali.zhiwuduotai.top/Article/details/gtbkoovhwu.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtsxlmvtoz.html

Go:   if s == "" {}
来源：http://dali.smart0.xyz/Article/details/gtitegvcvx.html

Ruby: if s.empty?
来源：http://dali.fengsongda.top/Article/details/gtewcedbkr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gtzsvidxzl.html

[E21] 超长截断加省略号
来源：http://dali.cqqwz.cn/Article/details/gtvokzlxkl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gtphbimeoj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtiornxluv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtnyuwrwke.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtalcrvfut.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtcgitvlxs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gtvyvvuefu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtephhwncl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtujgbmvlc.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gtnzmqkbrq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtqzhpmjtl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtpoowvpzv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtmshqdckh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtaqyvwsyz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuanzhike.top/Article/details/gtqhqsmmll.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtckzrdllm.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangdashe.top/Article/details/gtavndrioo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yongpay.top/Article/details/gtnfymhshc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzyhjqtss.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gtgthgbcct.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttsbnbotr.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gttzwniaqy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gtlegnqotq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtndujemxc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj202588.top/Article/details/gtfrskoliz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtehrkuziv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtwuvnxcjc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gtubafxbvq.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtmtypjalk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtceimzbtn.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gtzqaqsbhb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gttofugvvr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtpzbtaxot.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtjgixwavy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtlrdreydl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gthdrsrejw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtfvqoxgyw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gtqowvjjna.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ehwqpu.com/Article/details/gtcikmswmz.html

[F03] 写入文件（覆盖）
来源：http://dali.cucudq.cn/Article/details/gtnlbdvkec.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxuanxn.top/Article/details/gtyxhalqvy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtgmkmsjnj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtrrmfhavl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtyelxuzkq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gtxrxnkujt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gtwmwsulxm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtklwpegjb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtkxucjsiu.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gtfixohaoa.html


<!-- 参考信息 -->