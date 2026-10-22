代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.ybcxt.top/Article/details/gt2ppojflhg.html

JS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gt2gldrlbel.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cuafodum.html

Java: list.contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2grnvmrvl.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2sgxoiyfj.html

Ruby: arr.include?(x)
来源：http://dali.316326.xyz/Article/details/gt2yswtajlu.html

C#:   list.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gt2pjbnojeb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gt2pzducrmr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gt2ztyidirk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gt2tqvwzesg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2wvsimrkq.html

TS:   [...arr];
来源：http://dali.zhongyouzk.top/Article/details/gt2kconwazw.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxgrfwjn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gt2qklkqemi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gt2qdeglszf.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gt2ytperlho.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gt2xoaejndo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gt2krpmyrmn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvpdxzkn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmgwfqho.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2rnkizfxo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gt2afbrntlq.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gt2itwrpqso.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gt2hgisedzc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tanke756.top/Article/details/gt2fmjqdxch.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gt2xriiiolq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gt2iodnoxsj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gt2cctibysn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2hjkmqlcy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2gnrqlhoi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nftguaxp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jianghu66.top/Article/details/gt2lryovidp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qlezreov.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gt2bvjoauxz.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gt2eccyvuqm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yaeewcmp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hysaishi.cn/Article/details/gt2ewwooozo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gt2invhbywb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gt2xxonpwul.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gt2lvubkfiz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gt2uwprowzv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gt2laerlxpg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gt2wmyoarmi.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2oqrwyzgg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gt2aaewfcex.html

PHP:  implode(", ", $arr);
来源：http://dali.fzhhl.top/Article/details/gt2hjjvxjkv.html

JS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gt2kbpszpxt.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gt2xgzdlxrj.html

Java: String.join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gt2nzueqgyg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guannengcc.top/Article/details/gt2envrneuu.html

Ruby: arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gt2ihglanvv.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gt2acxiutvq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2vuwenkbn.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gt2shvslfle.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2pcsdkviu.html

[E01] 拼接字符串
来源：http://dali.tian-w.cn/Article/details/gt2wjcasmcw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gt2jxoevqly.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gt2rhqhijqx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fyeenzbj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yjafogkz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gt2vopqstct.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gt2ykigyclc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gt2rudkzmem.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2qsudrqfo.html

[E02] 重复字符串
来源：http://dali.xuanzx.com/Article/details/gt2brmoubbr.html

Py:   "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gt2sdxsxmld.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gt2svbvogeb.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gt2uxbnxcah.html

TS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gt2gxlxoufp.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gt2yywtdtpz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gt2paufpoqz.html

Ruby: "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gt2gsnbwcpg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gt2iijdtymx.html

[E03] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxethrct.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gt2rhtiwvch.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2eabfrflz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2wsrnkqnr.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gt2ksbtmmhd.html

Java: s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2yjpuuvay.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dianchejie.cn/Article/details/gt2wnnlrymp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gt2suarubjs.html

C#:   s.Substring(1, 3)
来源：http://dali.ehwqpu.com/Article/details/gt2uuuxinmn.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gt2zrfebujt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2zhggajyc.html

PHP:  strpos($s, "x");
来源：http://dali.zhoulong.xyz/Article/details/gt2tbdousvg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fzhhl.top/Article/details/gt2wvstmfou.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gt2niumuszl.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2hyyzxuda.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gt2ttwftgcf.html

Ruby: s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2reucvqsa.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2axzbtkza.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gt2vksdrgyo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gt2wkzbqqrr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aizwys.cn/Article/details/gt2sasxbrba.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2idhxwyaa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gt2qbfjlkxu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gt2tqviztjl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nwbrower.top/Article/details/gt2itdwxyey.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ivvv.top/Article/details/gt2cgzshurm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gt2ftawhebj.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gt2tnhwcodn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gt2bqfnuona.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuanzhike.top/Article/details/gt2ocjgnmgu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2muyigjww.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2krtxxzic.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2indjzsdt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2sjhareat.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2pqoiozey.html

C#:   s.Replace("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2sjefpyab.html

[E07] 按分隔符拆分
来源：http://dali.guowangkeji.top/Article/details/gt2zouggfya.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj202588.top/Article/details/gt2isplliyk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlocnkcf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gt2jpsfloab.html

TS:   s.split(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2jqnjwioo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mlnejsdm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cheryme.top/Article/details/gt2unnxlebm.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gt2iluclwyb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2heowsxfh.html

[E08] 数组按分隔符合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vspdnfjo.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gt2uxfegaum.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gt2axfonqxb.html

JS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gt2yxysyksv.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gt2cwvibxwq.html

Java: String.join(",", items)
来源：http://dali.yj20258.top/Article/details/gt2foiyyxus.html

Go:   strings.Join(items, ",")
来源：http://dali.quarkkingdee.top/Article/details/gt2oczlxoxy.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gt2cvshhnwb.html

C#:   string.Join(",", items)
来源：http://dali.tanke756.top/Article/details/gt2woquzugc.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gt2uqfhbqva.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ehwqpu.com/Article/details/gt2xuazrvmx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258.top/Article/details/gt2vcepflzk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gt2glengjdo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gt2hdwzsiej.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gt2pjahxnug.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2egyaxnkd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dianchejie.cn/Article/details/gt2gxxixdkt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gt2ujcxsvys.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gt2veugoufe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2yxxggpdk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gt2dzmpzsmq.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2mjpwfkhh.html

TS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gt2kbbbelqq.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqbzhgzf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2qmplzpdb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxvieqzk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gt2lbovhcuh.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktlphcvr.html

Py:   s[::-1]
来源：http://dali.sxryk.cn/Article/details/gt2jmnplgzt.html

PHP:  strrev($s);
来源：http://dali.cheryme.top/Article/details/gt2aslollue.html

JS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2jyiixapr.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2ukyqmbgc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gt2juefvxom.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.svipenyu.cn/Article/details/gt2vxjbtvbp.html

Ruby: s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ardafzyf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gt2spcpicsp.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gt2ugpwsokq.html

Py:   s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gt2lsizdbol.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gt2npjytove.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gt2eflkksuc.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bljhrrkn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.redwolf501.top/Article/details/gt2cggfsphi.html

Go:   strings.Count(s, "a")
来源：http://dali.zhixingplan.top/Article/details/gt2dmpvdmge.html

Ruby: s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gt2qtfbuoge.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nebpkrqy.html

[E13] 逐字符遍历
来源：http://dali.yangfankeji.com/Article/details/gt2lacoejep.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gt2clyctmkm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gt2puaarobg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2dyhjyssq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2siwdesme.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2hmadagzt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gt2khyqomut.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gt2ptxrtsnr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2tzxesbld.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gt2hlcooqia.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gt2smbyvaup.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.bjfxy.top/Article/details/gt2gswaxola.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xziqi.cn/Article/details/gt2ibxlukbl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewqfofdv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cashguo.top/Article/details/gt2fshdpret.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gt2xtfvqujd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gt2hqdsiyjn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2snfkhmkb.html

[E15] HTML 转义 / 反转义
来源：http://dali.yvedp.cn/Article/details/gt2kdokgtav.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gt2rgvmxygx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gt2gexaunbp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdqqkwwi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfviprwj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rsolcijr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gt2zajqzlhk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gt2hsqyyows.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gt2pqwbcoqu.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gt2dlbgibmw.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gt2wcmrcrxw.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gt2celmjrnw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gt2ybylzeca.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gt2aeelxcid.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nwbrower.top/Article/details/gt2vvwprfvn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2qnrsosre.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gt2cjkyrodm.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gt2lfixawaq.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gt2osblvgba.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gt2pnmvlsff.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgfzy.top/Article/details/gt2wmtfftzk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2fbyadzlc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vilxhwnc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gt2dunenpxd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yueranfly.top/Article/details/gt2munlgxoq.html

Ruby: s.capitalize
来源：http://dali.jyoumei.cn/Article/details/gt2hvffbuwu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gt2gjkgslds.html

[E18] 模板占位符替换
来源：http://dali.cheryme.top/Article/details/gt2nhnxorlx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gt2bffetubx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dianchejie.cn/Article/details/gt2cgocgrik.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2cjtgaetb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kyulxvdc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjekucu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2wmsvkcdw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gt2lmhkwrxd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gt2kkxqlbmx.html

[E19] 多行文本按行拆分
来源：http://dali.hysaishi.cn/Article/details/gt2vxucfpxg.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gt2rmndeavo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gt2hjgsuepv.html

JS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gt2foefygzr.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gt2eskrypcx.html

Java: s.lines().toList()
来源：http://dali.iojbl.cn/Article/details/gt2jlppitdq.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2enikxnpr.html

Ruby: s.lines
来源：http://dali.guannengcc.top/Article/details/gt2ukkjrumt.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gt2wqucdmla.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gt2awerpecu.html

Py:   if not s:
来源：http://dali.snrcjt.cn/Article/details/gt2sttsrtij.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj202588.top/Article/details/gt2kcjbsjye.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gt2dpdoqlzk.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gt2znrmbjvr.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gt2bpvdhuzf.html

Go:   if s == "" {}
来源：http://dali.gaohongyu789.top/Article/details/gt2qzozuqfe.html

Ruby: if s.empty?
来源：http://dali.ybcxt.top/Article/details/gt2yjohqpnz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gt2vlydjued.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gt2oxqfvodh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj202588.top/Article/details/gt2mbciiarh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2pxtxhvfj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2bciannjb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2lamueevs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2ckmgwnbh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.svipenyu.cn/Article/details/gt2lzmkdxjq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2uefcgucc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2lzcvipto.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gt2zxnmebde.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2mgxiguyk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gt2cvuvxysf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skplorag.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2ixxknelu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gt2pjsyxdft.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gt2kqbujpxv.html

Ruby: s.bytesize;  s.length
来源：http://dali.tanke756.top/Article/details/gt2fpmwznlr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gt2pgasesnc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2yewmrdsx.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gt2cxlpyjkt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2fufooudu.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gt2lcgbnntr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gt2sluoqvem.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2ueynzqxj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2setysvza.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gprmjyep.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2jgdwltbz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jiagoushi.top/Article/details/gt2phqtvrfn.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2kjeideyc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2yxqykgsc.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gt2xmscnvlk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cashguo.top/Article/details/gt2pfumspnw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gt2ludlzoxv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gt2hqaoatrm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2jeysijqa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ytwglvpg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gt2kegxikhr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gt2tjlyiezv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gt2zxzgobyw.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gt2kylfbwvo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dianchejie.cn/Article/details/gt2zawlxono.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2phcgokth.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2nhaznvqd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdrgusie.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gt2bfnlidgi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gt2ccqrliro.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nmghwwjf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2clolwxdw.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gt2qfuinfdx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2yxvctsnz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gt2lxodlikj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gt2xgdawtfy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gt2outyxert.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gt2aitheshh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.meibo888.top/Article/details/gt2pflvrwqq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.mhx1999.top/Article/details/gt2yluqmtyb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcteojng.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gt2hfamrpks.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ribloxpc.html

PHP:  file_exists("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2vrouktzf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2uuenwutc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2ttmcnpym.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2afvwoqkj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdazwzx.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2xbxkbwgt.html


<!-- 参考信息 -->