代发 wailian999

Ruby: arr.tally
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkzvyetn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gt2ldmqocud.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gt2fbfrfdhx.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2byfpeshf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ybcxt.top/Article/details/gt2yprpgljc.html

JS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gt2fasatogw.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2rporfqiq.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofwzkmgm.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2xsmdkxyl.html

Ruby: arr.include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rcwwhpqa.html

C#:   list.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2eakebvgg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cqqwz.cn/Article/details/gt2gvbgjupm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gt2rzshsoru.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gt2twpbrqcw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2hykxtdjl.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gt2cnxybgti.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2briyhagi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhongyouzk.top/Article/details/gt2hmychgof.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gt2fcjnmvgp.html

C#:   new List<int>(list);
来源：http://dali.aibaodan.cn/Article/details/gt2ilwqwbtg.html

[D23] reduce 累积计算
来源：http://dali.zdqjudy.top/Article/details/gt2vsmgapmr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.meibo888.top/Article/details/gt2fybssajr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fzhhl.top/Article/details/gt2tyhjljmu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gt2rpzsjfwp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2qedsdapm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sxryk.cn/Article/details/gt2qlkwimwe.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gt2fuhsuzvs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gt2ojwmnhxr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gt2kadctzhr.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gt2nlgmnxid.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tanke756.top/Article/details/gt2gniyxiok.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tsjcgqkq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2slkrcsze.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2umvvgeqk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gotoacloud.top/Article/details/gt2jyhjqnvr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sysykeji.top/Article/details/gt2tnjzxeao.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.quarkkingdee.top/Article/details/gt2mrpoxdje.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hysaishi.cn/Article/details/gt2yikqkrsr.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gt2kqtadgph.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gt2oldlbeam.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gt2nnohwkic.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gt2qbqssjwo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guowangkeji.top/Article/details/gt2ddmccodn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.0kj1m.cn/Article/details/gt2fwrpiayf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gotoacloud.top/Article/details/gt2uwmwoltf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cqqwz.cn/Article/details/gt2pruvexfd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mgeesybj.html

[D26] 数组转字符串
来源：http://dali.ivvv.top/Article/details/gt2femhkriq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gt2uwqkoypj.html

PHP:  implode(", ", $arr);
来源：http://dali.pycfn.com/Article/details/gt2rbhlxagy.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2kyngdwnv.html

TS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gt2domskohn.html

Java: String.join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gt2rwenmkxl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gt2bttuxaof.html

Ruby: arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2avawrjzc.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gt2tjvdemyf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjxxxcen.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gt2gmoeicma.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2bxszqxkv.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gt2ewkdtxec.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gt2qbkakxey.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yonumen.top/Article/details/gt2hkcljagr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gt2jatnrvgx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gt2vdrfxuak.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gt2pehzkfyf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqpfruvv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gt2mwinzjro.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2ctegdgvs.html

[E02] 重复字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2guwupxav.html

Py:   "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gt2survtpfi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbuybzna.html

JS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2fsdtvnpc.html

TS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gt2gdqkkqsj.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gt2ucgazxkb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gt2lmsufkrq.html

Ruby: "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gt2cgexkjxl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogijbpkf.html

[E03] 截取子串
来源：http://dali.nwbrower.top/Article/details/gt2wjzmtbkg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cdnleiting.top/Article/details/gt2ueddmrxk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2mmlrpqvn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gt2qrbmvdlg.html

TS:   s.slice(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2gzanjrim.html

Java: s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gnnhylet.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gt2gnebkljj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjoaryi.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gt2ublelqsy.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ostkllhr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnbndsex.html

PHP:  strpos($s, "x");
来源：http://dali.cashguo.top/Article/details/gt2qwinemqo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xziqi.cn/Article/details/gt2pyofhzet.html

TS:   s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2ixgncqow.html

Java: s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gt2shslogka.html

Go:   strings.Index(s, "x")
来源：http://dali.fzhhl.top/Article/details/gt2wbbtdnja.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gt2cgvisdfe.html

C#:   s.IndexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2helswbrf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gt2kwsrffwz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daxiang520.top/Article/details/gt2nhpoqdnv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuanzx.com/Article/details/gt2lkheimjo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2wljncfve.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gt2ionzetkr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gt2kzkwlgcp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rovtxuao.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2drzzswjq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yktmtgzb.html

[E06] 替换子串
来源：http://dali.jiagoushi.top/Article/details/gt2gkskhyse.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2sdletabj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yueranfly.top/Article/details/gt2ibbhzqwy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2hoyevmta.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2iokouzcd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2dbkyctcj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhjiciw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2yyfsbwqa.html

C#:   s.Replace("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svajomcp.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2yjbghrvh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozguahnw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gt2pmfzfmuv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gt2ooqvyohg.html

TS:   s.split(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzniwlkw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gt2qvyvvidv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.haohaochexian.top/Article/details/gt2vaususql.html

Ruby: s.split(",");  s.split
来源：http://dali.ehwqpu.com/Article/details/gt2nuttohxd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gt2ehcygqcd.html

[E08] 数组按分隔符合并
来源：http://dali.yongpay.top/Article/details/gt2wlhqqgza.html

Py:   ",".join(items)
来源：http://dali.meibo888.top/Article/details/gt2qpofavzy.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vyjaghvt.html

JS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2qfbutqso.html

TS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gt2qpgnixcw.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2atkcyajh.html

Go:   strings.Join(items, ",")
来源：http://dali.wangdashe.top/Article/details/gt2tiamgymh.html

Ruby: items.join(",")
来源：http://dali.xziqi.cn/Article/details/gt2irsoklvm.html

C#:   string.Join(",", items)
来源：http://dali.cashguo.top/Article/details/gt2locqldbi.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkxvnlqp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gt2ekqnwgap.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2vrofeall.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fzswrdwv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gt2otwicqgh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrqmnzsn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dianchejie.cn/Article/details/gt2iqxtcpiy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fengsongda.top/Article/details/gt2ttwyajph.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gt2npwcqiiw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gt2irzfbvnn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2kbudkpwn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nwbrower.top/Article/details/gt2icrzqbsr.html

JS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2gtbhylpx.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2sxdpujdi.html

Java: String.format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2tqxkcije.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gt2mtbgzvyn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2jhnqdtqt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gt2gwzslewe.html

[E11] 反转字符串
来源：http://dali.sysykeji.top/Article/details/gt2wthlosno.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gt2psppawlj.html

PHP:  strrev($s);
来源：http://dali.guannengcc.top/Article/details/gt2ssfxtdvr.html

JS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gt2ptrvdpwk.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2sgoxgmsn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gt2qyqyurey.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.birdmap.top/Article/details/gt2ibfqlqtj.html

Ruby: s.reverse
来源：http://dali.sweek.top/Article/details/gt2gsvgzadw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gt2sopcmtbw.html

[E12] 统计某字符出现次数
来源：http://dali.jyoumei.cn/Article/details/gt2pkcvhmdh.html

Py:   s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2ccsnlkdz.html

PHP:  substr_count($s, "a");
来源：http://dali.ybcxt.top/Article/details/gt2jmpgqchw.html

JS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gt2buqcwerx.html

TS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2kswnyvkf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cqqwz.cn/Article/details/gt2zfkbgtwj.html

Go:   strings.Count(s, "a")
来源：http://dali.gzhubu.top/Article/details/gt2zioykglq.html

Ruby: s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gt2tksinaqv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypkestne.html

[E13] 逐字符遍历
来源：http://dali.sufxvd.cn/Article/details/gt2vidsyuju.html

Py:   for ch in s: print(ch)
来源：http://dali.yj202588.top/Article/details/gt2stcesksd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gt2omccpbzw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2bnerfajc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2yxuxylyi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2wplqfmfg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgzhszsb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ploqdohy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2jbjbueel.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gt2gnahiqsf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gt2xgdbylva.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dianchejie.cn/Article/details/gt2tbskxnev.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhongyouzk.top/Article/details/gt2yohnzhym.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gt2odubdrzk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gt2mgzkuogb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gt2nimzqrhm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gt2bljsyfcc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gt2yscyocjb.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gt2jitcnmbx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gt2lsfpirde.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kllfhoyr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhdcsaod.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2ntynlgwc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.meibo888.top/Article/details/gt2jssiliaw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2nggwtnqh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gt2oxraclqz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gt2oqzwpayx.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gt2grtgxrfn.html

Py:   f"{1234567:,}"
来源：http://dali.aibaodan.cn/Article/details/gt2ciednehb.html

PHP:  number_format(1234567);
来源：http://dali.yonumen.top/Article/details/gt2mijgcrrc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gt2koucxkxk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gt2jrsxrhye.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gt2uomvqfwm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gt2rbismukj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2komdzerf.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gt2jgysxdnv.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gt2xeveqfvx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gt2yghwjbtv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258888.top/Article/details/gt2ywvmrmlh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gt2decuujds.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2xjjkxdfb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.c1oappe.top/Article/details/gt2zqpjewjw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2dnysxnfq.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gt2rpgycctp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gt2xpfwueca.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gt2gncvonrg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gt2inkznyxh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gt2tilrnvbo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnwrhwlb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2grxuaiha.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2dohvwuau.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gt2brbgtwop.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2izlfttzv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fengsongda.top/Article/details/gt2xymfsckv.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gt2nziilbmg.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gt2pnamwube.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2bobjzqdc.html

JS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gt2ugchhvmm.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2hdtpfxiy.html

Java: s.lines().toList()
来源：http://dali.hywenlv.cn/Article/details/gt2nbptoaej.html

Go:   strings.Split(s, "\n")
来源：http://dali.jyoumei.cn/Article/details/gt2szqrwfjx.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gt2zrflsgow.html

C#:   s.Split('\n')
来源：http://dali.sxryk.cn/Article/details/gt2sdvpexzw.html

[E20] 判断字符串是否为空
来源：http://dali.shzxlz.cn/Article/details/gt2ogspwnvd.html

Py:   if not s:
来源：http://dali.fengsongda.top/Article/details/gt2zfkdnuve.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gt2mtxpeyor.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sxryk.cn/Article/details/gt2gbxsmglg.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gt2kfvivihx.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gt2eyzuyhxw.html

Go:   if s == "" {}
来源：http://dali.xziqi.cn/Article/details/gt2khrdphso.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gt2xyvbkwen.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ydzc1.top/Article/details/gt2ntdhipqk.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gt2vfojonah.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffuwghmc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2xuoqzezv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2fyjbqvyk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2lejxqzfb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2fleeufox.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hongshengwenyu.top/Article/details/gt2nritrxgc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wplzyljh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2uyelrjdv.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gt2hdhmzwtp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gt2ireyjvol.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2xtyryhfx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gt2foyfepsz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2mxxanxhi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gt2hulzmbvh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gt2jtamyyph.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2zfiqeoww.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gt2kbfmrmkn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ennpupwq.html

F. 文件与目录
来源：http://dali.gzhubu.top/Article/details/gt2cblkpjwu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2yjocvhtp.html

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gt2qzvliklc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.haohaochexian.top/Article/details/gt2fehibzgt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2ohqipkzw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pycfn.com/Article/details/gt2fmvqfhgf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnqzz.top/Article/details/gt2qeksjngf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2gxwaztgh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigufen.top/Article/details/gt2acqdyjtw.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2maukswko.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2feyzttbn.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gt2olhegwfs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gotoacloud.top/Article/details/gt2umtiglkt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gt2yliuxmkh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gt2wciqhcyk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2nwnitjge.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2kixdzrqz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajsntaxe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gt2wyigjlza.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangdashe.top/Article/details/gt2xtnypjub.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxuanxn.top/Article/details/gt2lvnqvxkk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigufen.top/Article/details/gt2oncgeevg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2vpbgphrl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gt2uxfozvek.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gt2wosmieew.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gt2zawlfsfj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gt2zxnwcdyv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gt2fodouuwy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2bnvomxtk.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gt2iasvfbxe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gt2hedtfmeb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gt2oebzwtki.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gt2bvukgkwi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2rmlhpqpy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gt2vxzaugme.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2qxqzeimk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhengqikj.top/Article/details/gt2ftdcwcyx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fzhhl.top/Article/details/gt2duuitnld.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gt2xsntefoi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gt2bqmtnrph.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2eotkdhud.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqvpfnvb.html


<!-- 参考信息 -->