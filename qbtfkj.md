代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gtknpqwvax.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gtdabsgayr.html

Go:   // 手写 map[string][]T
来源：http://dali.xuanzx.com/Article/details/gtgmdskupi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gtlrqxtiyo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.c1oappe.top/Article/details/gtgvhrmgtq.html

[D20] 统计每个元素出现次数
来源：http://dali.yvedp.cn/Article/details/gtyufvnsfp.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gtxbemhzqc.html

PHP:  array_count_values($arr);
来源：http://dali.gzhubu.top/Article/details/gtraauglat.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmntcpvyz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtrnzsaudv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpevbhbey.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gtgymytieb.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gtilgjxtjo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ybcxt.top/Article/details/gtjnikhtcr.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gthsosbhtn.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gttiehflpo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gtgzeiajah.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gthbfqjljt.html

TS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtjtfjkyli.html

Java: list.contains(x)
来源：http://dali.pycfn.com/Article/details/gtqhoqzzwk.html

Go:   slices.Contains(arr, x)
来源：http://dali.sweek.top/Article/details/gtbdthsrmu.html

Ruby: arr.include?(x)
来源：http://dali.yj20258.top/Article/details/gtnvwjjxrd.html

C#:   list.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gtsddqqoiw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gtnmngqkyz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gtmkowamrf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gtmilongvv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fzhhl.top/Article/details/gtfimhfeqi.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfjshzou.html

Java: new ArrayList<>(list);
来源：http://dali.vqdsnc.cn/Article/details/gttpicktfx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hywenlv.cn/Article/details/gtruzcrlcd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuanzx.com/Article/details/gttbgpcqhk.html

C#:   new List<int>(list);
来源：http://dali.guowangkeji.top/Article/details/gtxqyaynry.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gtsapcrqzg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtqogmlovt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tanke756.top/Article/details/gtpxbkppbb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtijktmzvp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtxibaczew.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yueranfly.top/Article/details/gtabvdqbhr.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtpzkgwrhs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gtmuuztrqo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.quarkkingdee.top/Article/details/gttnrkdosq.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gtlscsphux.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gtllbhwauz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gtvzjxedtb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtxooswshc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtbwtpkidf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gtbritcvkk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hammf.cn/Article/details/gtqwzhtfil.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gtryiflgbr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gtxgrqvlqx.html

[D25] Set 集合去重与交并差
来源：http://dali.xuetiantiany.cn/Article/details/gthjogrkei.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhengqikj.top/Article/details/gtafliglgx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aibaodan.cn/Article/details/gtdriifyyk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gtmrbzxfge.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuanzx.com/Article/details/gtaynrruhn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.svipenyu.cn/Article/details/gtfqvngdbx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gtumlqntol.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gtxzgiyydz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.andypj.xyz/Article/details/gtxtahnvwk.html

[D26] 数组转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtpbidgtgl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtmysssiox.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gtrtdroypj.html

JS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtyyjnvfnm.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtzyyevzxt.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtrizyymhh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlktiqfj.html

Ruby: arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtzchejszf.html

C#:   string.Join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gticecjhpv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtynhmilev.html

E. 字符串处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtonuilbtt.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbvfjwhid.html

[E01] 拼接字符串
来源：http://dali.yj20258.top/Article/details/gtqnjuoeyf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.c1oappe.top/Article/details/gtppovcjfs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj202588.top/Article/details/gtjqlcnlid.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gtrhkrcucr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gtixsbthxe.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtzeliicit.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtdkotplnl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngiwtwkf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtoycschap.html

[E02] 重复字符串
来源：http://dali.hysaishi.cn/Article/details/gtcdtxjkfu.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtceonthyu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.316326.xyz/Article/details/gtzkodmpof.html

JS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtyijjvm.html

TS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtsrhtdilm.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtodzfqvtz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gtfltqquwl.html

Ruby: "ab" * 3
来源：http://dali.yj202588.top/Article/details/gtztujqqhq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.redwolf501.top/Article/details/gtkrjggwgm.html

[E03] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnhjpzcn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jyoumei.cn/Article/details/gtvdexufzt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtzmvunceu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtthakzmho.html

TS:   s.slice(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtavtgweny.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtryxdzrxa.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xylfe.cn/Article/details/gtofopbwqk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gtmmwxpifr.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gtgwniagez.html

[E04] 查找子串位置
来源：http://dali.vqdsnc.cn/Article/details/gtxwdcijbo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtwnwirftc.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gtlajdwvws.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkaahfwje.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtdzcmudug.html

Java: s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gtddqougxy.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gtxfpikbcn.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtgvccsphj.html

C#:   s.IndexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gtmilfhuvt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenzaomai.com/Article/details/gtpdxbwmdq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ydzc1.top/Article/details/gtagoanhip.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sufxvd.cn/Article/details/gthmggycfj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtwtanxhnw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gtdadkadjf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtqepsjqvf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daria6918.cn/Article/details/gtheslsjuc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guannengcc.top/Article/details/gtpwzjpifq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahvlrehf.html

[E06] 替换子串
来源：http://dali.zhixingplan.top/Article/details/gttbxqjheh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtxpmgqqbv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gtuuhdeiyc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gthhgnlduq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gthksfdvyz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtswiruzpd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzjsmmqe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtehpyprlv.html

C#:   s.Replace("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtbpihbdjb.html

[E07] 按分隔符拆分
来源：http://dali.birdmap.top/Article/details/gtxceacmxi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.svipenyu.cn/Article/details/gtdinrsnzv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtrvfxfagy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guannengcc.top/Article/details/gtwgqbnavk.html

TS:   s.split(",")
来源：http://dali.redwolf501.top/Article/details/gtvkmgdcqb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gtlxqngkix.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gtvmyjexzv.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gtjtvxycst.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ivvv.top/Article/details/gtatelgoxf.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gtxkfridin.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gtxjtjebhy.html

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gtqtlepbma.html

JS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtarekmxvo.html

TS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gthpmbnwhx.html

Java: String.join(",", items)
来源：http://dali.xziqi.cn/Article/details/gtlnuxmzct.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gtjyuaprug.html

Ruby: items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtraulkdum.html

C#:   string.Join(",", items)
来源：http://dali.ivvv.top/Article/details/gtlmuptajv.html

[E09] 去除所有空白字符
来源：http://dali.birdmap.top/Article/details/gtyitubpzi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gtqvhxvfti.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yanxiufei.cn/Article/details/gteicpihvb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtbcmllszp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtwskiindp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtxzxrfgmm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnqzz.top/Article/details/gtwvxxyxvo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gtbalsfiax.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gthstapdsq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hfpthk.cn/Article/details/gtesbztrqc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtcadjwoso.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gtiedgykag.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtemvppgsv.html

TS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gttvnqgfam.html

Java: String.format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gttznmxrhy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtkakqvmnq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gthvgcjfnr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ybcxt.top/Article/details/gthuowewbp.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gtlljugqsf.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtgesjlahf.html

PHP:  strrev($s);
来源：http://dali.hammf.cn/Article/details/gtfygvwcus.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtbzaocndo.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtrjfbvbma.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sxryk.cn/Article/details/gtbausoodk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtjbgnvabf.html

Ruby: s.reverse
来源：http://dali.iojbl.cn/Article/details/gtowzqtlyi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtagkzwofg.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gtbqclprbd.html

Py:   s.count("a")
来源：http://dali.316326.xyz/Article/details/gtxpecqjel.html

PHP:  substr_count($s, "a");
来源：http://dali.smart0.xyz/Article/details/gtihssoacy.html

JS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtpfhaxyyv.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtlknqhuny.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258.top/Article/details/gtibwfqjoy.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gtbjvnikzx.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtxyenvxfs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gtpowwymwe.html

[E13] 逐字符遍历
来源：http://dali.jinqigufen.top/Article/details/gtbcyycdns.html

Py:   for ch in s: print(ch)
来源：http://dali.9152youxi.cn/Article/details/gtqktsiwgr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xziqi.cn/Article/details/gtovhvqxgh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtgebgwdzn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtuocjzzms.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gtfexugtas.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtiupcolem.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gtsjuzkfts.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gtzwageuly.html

[E14] URL 编码与 Base64
来源：http://dali.feifeiyinyue.top/Article/details/gtfndcrfqj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.redwolf501.top/Article/details/gtdcgdfqzm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.quarkkingdee.top/Article/details/gtdxtcwkrv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tian-w.cn/Article/details/gtxhpoidom.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yangfankeji.com/Article/details/gtbddwksex.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtnzzflddr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.vqdsnc.cn/Article/details/gtnsljspum.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkbogixy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtftyymcje.html

[E15] HTML 转义 / 反转义
来源：http://dali.cdnleiting.top/Article/details/gtfmrpovtl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aibaodan.cn/Article/details/gtoiirremi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gtcgaaknnc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gtqnklkift.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cqqwz.cn/Article/details/gtevuvvgsf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gtbrxktquv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxinkj.top/Article/details/gtfyodhfeg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.svipenyu.cn/Article/details/gttydhgquy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ppjwa.cn/Article/details/gtlhphgqaa.html

[E16] 数字千分位
来源：http://dali.0kj1m.cn/Article/details/gtiptsjqsu.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gtwqlmsnak.html

PHP:  number_format(1234567);
来源：http://dali.sysykeji.top/Article/details/gttuhcxjlc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gtyqomzjwu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttivsqegq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gtlxdbztdl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gtmwvxdaqa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.9152youxi.cn/Article/details/gtmoaottfk.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gtoaafmtqs.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gtxfsrmlfu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gttgohpraz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gtjjgbiuic.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtrauctedm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtjethncub.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258.top/Article/details/gtohczbrfk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangdashe.top/Article/details/gtyrandvxy.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtbvyvuuig.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cdnleiting.top/Article/details/gtliyvttyc.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gtgbalocvy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gtabdkvzgk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gtscotxnkz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtovfhdxdy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gteozmcshm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtbscnzjqf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtowcztvii.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hammf.cn/Article/details/gtzxtwxptm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gtpomemzib.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gtfzjxspim.html

Py:   s.splitlines()
来源：http://dali.ivvv.top/Article/details/gtjehdcxaa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zycfv.cn/Article/details/gtaohflqmi.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gtcgfogttd.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnozmaofa.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtijmsbqsy.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gtteciznme.html

Ruby: s.lines
来源：http://dali.svipenyu.cn/Article/details/gtixdhqujj.html

C#:   s.Split('\n')
来源：http://dali.yj202588.top/Article/details/gtaodzafzm.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gtnuxjjztp.html

Py:   if not s:
来源：http://dali.jinqigufen.top/Article/details/gtkunuwhby.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gtexivbtxi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gtrbajhsbt.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gtoqmugieq.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtqhuedihf.html

Go:   if s == "" {}
来源：http://dali.mhx1999.top/Article/details/gtwalpedsm.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gtmhnoedrd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gtvaoqrjnh.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gtdymajgbk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gtbjwnmcmp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gttamzqijy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtehssdwra.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtbhelgiza.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtbsfyvrbb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gtrswfelbl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtulgahidi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtwdnoodgl.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gtvkxxkkit.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gtzprckizm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpqijick.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtpmlemhzu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtcqmiensx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtlbmyvwfk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtarnbpwid.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtofonorsz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtvzfmrfjn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgmqftwbw.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gtnxwnolid.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtipksciou.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gteupukcar.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtwmncaclh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtmdjdzmum.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gtsrhwqmnk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtaublhgew.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtudttzjvu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gtympvcvea.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtualbcftg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtuclnuowi.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gtqsawbzlt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gtvbjdttzz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gtzgbgllbs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtzmijvifb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtroxjoyue.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gtkkfcuwjc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dashuyun.cn/Article/details/gtydjltlbj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sysykeji.top/Article/details/gtbylrrmqs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gtdohjsuni.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gtbxjqtlpm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gtbcfsfzki.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtkhthtxun.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gthnaqgoeo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtjtlbdqgf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gtnzxrymss.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gtgjeodexq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtqddyhoav.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtadrhrixm.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gtlcveyrhh.html


<!-- 参考信息 -->