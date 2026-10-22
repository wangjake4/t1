代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtavsygtbx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtcrtytjya.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenjidiqi.icu/Article/details/gtyooyjvws.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gteyclapud.html

Ruby: arr.tally
来源：http://dali.tanke756.top/Article/details/gtbodfkrml.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gtforlrrgq.html

[D21] 判断是否包含某元素
来源：http://dali.hfpthk.cn/Article/details/gtjixilogr.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtlloveiez.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yongpay.top/Article/details/gtnfxdiwms.html

JS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtodhkqwfw.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtxxmsjwlj.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gtxkxctjkn.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtyjpftwqf.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmnyqnwc.html

C#:   list.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtydcafyxc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.andypj.xyz/Article/details/gtfnkdjljk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pycfn.com/Article/details/gtbfpnabhv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnxiangtu.top/Article/details/gtalynlbmu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtlbvnqwjo.html

TS:   [...arr];
来源：http://dali.guowangkeji.top/Article/details/gtxztulcwt.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gtwvhhimyx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dianchejie.cn/Article/details/gtrkevdfpf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guowangkeji.top/Article/details/gtlrrxetdy.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gtugulxyki.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gtyrybqbfj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtloddpgfa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gtnpzljhfq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtirhepuvn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gtarkffboa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ydzc1.top/Article/details/gtnlkpiebe.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gttyqkjpwj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zdqjudy.top/Article/details/gtuhsvcpoo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gtwaxhziyb.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gtowkzrndf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gtxfblutbc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtuscppadd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gtlphfghhh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guannengcc.top/Article/details/gthqyefzyi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dashuyun.cn/Article/details/gtdofhghrl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gthpykresr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cashguo.top/Article/details/gtdnafgnur.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gtbzobhhkf.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gtmnddzkxh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gtzdfwgbdu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gtvqmwktxx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gtrnthwlxv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigfzy.top/Article/details/gtydwdjsck.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258.top/Article/details/gtkfllkmvn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gtdwnjfxct.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gtwpfzmgam.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtugxmjpge.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtuvepvsky.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gtoexowsmo.html

PHP:  implode(", ", $arr);
来源：http://dali.bjfxy.top/Article/details/gtvjssggpi.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtidzockqh.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtvmyrdrna.html

Java: String.join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjerzojnj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtwppspqpc.html

Ruby: arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtojhxcvsz.html

C#:   string.Join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtyzajwckq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtntmaoklo.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gtivtwsvlq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtscirnmaf.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtmfvohtaj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gtsgaokmrq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj202588.top/Article/details/gtlnkgjmdh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtqxhvvdcz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtzaxmdrgb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sxryk.cn/Article/details/gthvbujbox.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gtrqfairht.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gtblnabana.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtzipymyuw.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gtlqmzwxem.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gttidasasf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.birdmap.top/Article/details/gttepncluz.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtsrkmfgcg.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtcjwkkxaj.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtvynpaahv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gtxotzdlcc.html

Ruby: "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtimtmyypf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gtozkwjcjv.html

[E03] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtijffopmj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yanxiufei.cn/Article/details/gtrndvvigg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtmobeugwf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtriaovkrv.html

TS:   s.slice(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtwbysnofl.html

Java: s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtcyukldxq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gtclynyndl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yongpay.top/Article/details/gtxceqcxwp.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gtwlibdgtx.html

[E04] 查找子串位置
来源：http://dali.fengsongda.top/Article/details/gtqwhbguur.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtkkngmoyl.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gtptxpqsir.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gttwqkncbm.html

TS:   s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtcjdpbhft.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiijtjcsq.html

Go:   strings.Index(s, "x")
来源：http://dali.havefunace.top/Article/details/gtjbkmzagp.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgivryyof.html

C#:   s.IndexOf("x")
来源：http://dali.havefunace.top/Article/details/gtxrkqgwzb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gtegqcubox.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hammf.cn/Article/details/gtuodbzjmb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258888.top/Article/details/gtcpwtvjvo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtzuekbiza.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gtgairzidv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gthnogodqj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gtocuvgzap.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.haohaochexian.top/Article/details/gtlfqivdlq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkodnlvb.html

[E06] 替换子串
来源：http://dali.hnxiangtu.top/Article/details/gtwzfbbzrr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gtulcwozaj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gtdurujgvj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gthlrbmidd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtxfwthqdu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtrhtlpujl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtxaukrrtl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtsefksnzo.html

C#:   s.Replace("a", "b")
来源：http://dali.daxiang520.top/Article/details/gthdslsmko.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gtdydcduas.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.svipenyu.cn/Article/details/gtszydzgxk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtahmqpkvh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tanke756.top/Article/details/gtkmxjdodk.html

TS:   s.split(",")
来源：http://dali.tianlin.xyz/Article/details/gtafmwzfro.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.quarkkingdee.top/Article/details/gtyajnirhc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtzmufucxg.html

Ruby: s.split(",");  s.split
来源：http://dali.0kj1m.cn/Article/details/gtzfxlvxsq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xylfe.cn/Article/details/gtnaumoekz.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gtyygewukg.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gtaelzohtr.html

PHP:  implode(",", $items);
来源：http://dali.hongshengwenyu.top/Article/details/gtzscxfoid.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtdjszmxbd.html

TS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtbzgzknhs.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtbtkebpvf.html

Go:   strings.Join(items, ",")
来源：http://dali.zhongyouzk.top/Article/details/gtkcnmypug.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtsksvvjxx.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtvbgtyila.html

[E09] 去除所有空白字符
来源：http://dali.yuanzhike.top/Article/details/gtuofoepzp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gtzmhfmcap.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gtuzyhgoyc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gtcyoiokce.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpuxcqhj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbklmopu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tianlin.xyz/Article/details/gtboytevvz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gthwckqwye.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtovylvmrb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gtvnchedgq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtpoybmpmp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gtwsmrrsww.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtcjmehqyu.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtnjhuhlmx.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtmcpytxga.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtmbysalbs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtvyxsxakz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.iojbl.cn/Article/details/gtrnlahros.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gtdrfszomw.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewqaznio.html

PHP:  strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtvdfxnoqt.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtndprigjo.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtnhdhtnfu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gtgngytkto.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gtpauvseka.html

Ruby: s.reverse
来源：http://dali.daria6918.cn/Article/details/gttztrcdon.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtepykitay.html

[E12] 统计某字符出现次数
来源：http://dali.chenzaomai.com/Article/details/gtbrevmfso.html

Py:   s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gtkthhalws.html

PHP:  substr_count($s, "a");
来源：http://dali.sufxvd.cn/Article/details/gtgewtclfc.html

JS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtibrdmrdb.html

TS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtfueuicmc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hfpthk.cn/Article/details/gtmxloevvy.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gtgwkykhbv.html

Ruby: s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtuszbiwbk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gtiaziisuy.html

[E13] 逐字符遍历
来源：http://dali.fzhhl.top/Article/details/gtobfktchv.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtzsfysnfk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gtkmglyglg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamzbgfgr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtnlhdiprp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtebpvbnrn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.bjfxy.top/Article/details/gtlcmxffxp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gtfphwqjbp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gtkjxzyolc.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucpznumg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkairzain.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnqzz.top/Article/details/gtyrjclzka.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gtjymztxdy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.316326.xyz/Article/details/gtnwfnkdyx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtmoocdmny.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangdashe.top/Article/details/gtznkwzgyb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gtkefjsykr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fengsongda.top/Article/details/gtmjtydclj.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gtatsiymyy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtvdfpzjeg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtdwvdifay.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gtliejncld.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gtwmazfpap.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gteukvgunv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gtwpwlkpwe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zycfv.cn/Article/details/gtuddetsol.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenzaomai.com/Article/details/gtfkaupzet.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gtfwprxizq.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gtgzbwvcrz.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gtlpdjgfqp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gttswlahtf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gtejvshmfk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gtjumvmfbi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ybcxt.top/Article/details/gtxusieqjp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtqzagnhiy.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gtcjfzuder.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gtxydeepzs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gtfphtlczw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gthzbwgrmq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtettchyiq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtmetjijde.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gtysoiqtbn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gtwzvnknup.html

Ruby: s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gtpaleigdw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sxryk.cn/Article/details/gtigqloczu.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtfrciafge.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sysykeji.top/Article/details/gtdfuouyte.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jlsjyb.cn/Article/details/gtvdpomlsz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtlayyauco.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gthezttnvu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtzdnusitq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtcujaaibs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gtdpxxxven.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gtacmuebkr.html

[E19] 多行文本按行拆分
来源：http://dali.zhoulong.xyz/Article/details/gtshktjjwv.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gtoljwfhvg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gtktopjrev.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtssluoiyl.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtcejfghue.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gthbrqqmtx.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtjkupmwow.html

Ruby: s.lines
来源：http://dali.zhiwuduotai.top/Article/details/gtrstlotjo.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtlsramnop.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gtekuaxqke.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gtudwcnhro.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtnxxqhfte.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xinyue.icu/Article/details/gtgoudnegj.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gteoqfxomj.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtshjnujty.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipzfotdo.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtqageghjy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtetzogydh.html

[E21] 超长截断加省略号
来源：http://dali.sufxvd.cn/Article/details/gtkzjtoqqn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.feifeiyinyue.top/Article/details/gtqthqgkyw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtaflsohfr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtsrtgfqmc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtbklqibit.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gthigjliei.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gtkrpepuvq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtodavbwye.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtrtvtknli.html

[E22] 字节长度与字符长度
来源：http://dali.ppjwa.cn/Article/details/gtzabfsfoj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtpzzvmndw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtnvlqayks.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtpjxlpvvu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtgnxtmlnc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tanke756.top/Article/details/gtfujxxopt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gtbpttrudo.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmfpahem.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gtuyjjziyo.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtyvzwvnep.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtmjndkgwh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjogoeuls.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtcmfofmhi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmllkgzy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gtmqtdngzt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gtupixjixs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtqoldfimc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtmjpiqvgp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gtdefzhymj.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtxttlnsie.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gtofaqriby.html

[F02] 逐行读取文件
来源：http://dali.sxryk.cn/Article/details/gtkuaceezq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gttvpyhmys.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gtubagyucm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gttgkfoxjm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrqtgclqn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtcjltomek.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gtwufcjqbq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszksmhfo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwsmxptkc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gtycbzxdbb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtjeedrchu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtrshuekvh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtybiwnuyv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtlkemnwpk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gtfbecfntm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gtdszotrfz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteryjwdff.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtuytvclea.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gtllifmwkt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjewltcy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gttamjlrwb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihboanus.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtbgmdtxhe.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gtltoovzvi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gtbkbwltxc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gtpsznmzmt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqibucjln.html


<!-- 参考信息 -->