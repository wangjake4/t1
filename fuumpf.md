代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2heflfvit.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2lhvqbgqm.html

C#:   list.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gt2olivoitm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuxming.cn/Article/details/gt2ukxylurn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knhdkmwt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gt2gpwrxpfu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2qjwdcvwb.html

TS:   [...arr];
来源：http://dali.svipenyu.cn/Article/details/gt2qsxrgyeq.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gt2zjxkinly.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gt2xcqzlrde.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gt2opbltein.html

C#:   new List<int>(list);
来源：http://dali.jqgfzy.top/Article/details/gt2rpbnvlwj.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gt2yiocimjk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gt2aljjykzq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xinyue.icu/Article/details/gt2pahbmvvf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2cpwnygxz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gt2dxybnhqj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gt2vavnjche.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gt2zliiwrbb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gt2hekfyhxg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnqzz.top/Article/details/gt2qzbbecja.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gt2tuesykat.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnwarpnx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gt2wjhuisix.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cashguo.top/Article/details/gt2yoxjgdfo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2zbgopuae.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gt2roeypjkw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uecxzfil.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmorqaux.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.kuanghao11.cn/Article/details/gt2tyfipmps.html

[D25] Set 集合去重与交并差
来源：http://dali.shuidangran.top/Article/details/gt2hqzpyvgt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gt2ryeawiqk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gt2qdgpfhfu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gt2etwvknfx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gaohongyu789.top/Article/details/gt2vfrxhmxm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yueranfly.top/Article/details/gt2cfuhqsls.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aibaodan.cn/Article/details/gt2tmkgsqel.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gt2mpiojraz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gt2qjiydmyk.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kprnmipl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vawthyjt.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2yltdcwrn.html

JS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gt2iilnpudz.html

TS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2ctctqlhf.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gt2rvrpyugb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gt2ttxaplmg.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2anyrhtzo.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gt2xappdzuc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qdbtikkz.html

E. 字符串处理
来源：http://dali.haohaochexian.top/Article/details/gt2rcmlteax.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2qrkiewpw.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gt2aczeftad.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuxming.cn/Article/details/gt2rdkcdqwc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gt2ccnqliod.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gt2pubwafqk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gt2hmmlqmsl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.kuanghao11.cn/Article/details/gt2ixyiykhu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fzhhl.top/Article/details/gt2gbtbbjgs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhoulong.xyz/Article/details/gt2afkvszdi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2iqfvghul.html

[E02] 重复字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwfqfact.html

Py:   "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gt2iaaxrmvp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwzsrqvh.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gt2cikitiwp.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2fahjtbbx.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gt2urzquemp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jiagoushi.top/Article/details/gt2swwomdmp.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gt2myyhtude.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gt2wsykbesx.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gt2hrzotqgp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gt2kemsgijs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2kuqxibko.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gt2oxgtpucr.html

TS:   s.slice(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2yercpaxt.html

Java: s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gt2qstxrokq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gt2feqmnvcq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258888.top/Article/details/gt2hwyfkirj.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qokllhet.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gt2xaweqoty.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gt2zbbdwgkk.html

PHP:  strpos($s, "x");
来源：http://dali.cdnleiting.top/Article/details/gt2bsvqrhif.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gt2jsmwrwqj.html

TS:   s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gt2kquizbfn.html

Java: s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gt2umbbxhia.html

Go:   strings.Index(s, "x")
来源：http://dali.pycfn.com/Article/details/gt2obtbrzvm.html

Ruby: s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2svexzocg.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gt2mdbizwtp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxinkj.top/Article/details/gt2dyqhwjui.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gotoacloud.top/Article/details/gt2aqcuetau.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnqzz.top/Article/details/gt2ogkqkhaf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2punvrkyb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gt2szwtrnpn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2pdvyfiym.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cdnleiting.top/Article/details/gt2cahaigpv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2hepxuryf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2kadacflb.html

[E06] 替换子串
来源：http://dali.zhoulong.xyz/Article/details/gt2caizifuv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbwfntor.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gogol.net.cn/Article/details/gt2lkcveejx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqzuhrmv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2znelwifc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojkxuomj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2ivprnqcm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2bogoaxvq.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtlvoqhs.html

[E07] 按分隔符拆分
来源：http://dali.meibo888.top/Article/details/gt2zoaswyre.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jiagoushi.top/Article/details/gt2tshqmcga.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnernbuu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigufen.top/Article/details/gt2koeidrfb.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gt2wzqcmvyt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gt2ocodawnd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tanke756.top/Article/details/gt2ritirlnt.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gt2zalirpcw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shzxlz.cn/Article/details/gt2knkvqden.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gt2umrcxdht.html

Py:   ",".join(items)
来源：http://dali.tian-w.cn/Article/details/gt2sjelmpnp.html

PHP:  implode(",", $items);
来源：http://dali.nanxinkj.top/Article/details/gt2uolwkdda.html

JS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2newosspf.html

TS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gt2mgppdupy.html

Java: String.join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gt2hciwqjce.html

Go:   strings.Join(items, ",")
来源：http://dali.yueranfly.top/Article/details/gt2glxsfliw.html

Ruby: items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2pjgnhnnv.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gt2rotwaorq.html

[E09] 去除所有空白字符
来源：http://dali.meibo888.top/Article/details/gt2qwgapnnf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gt2cvicojmc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2komrfqzs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gt2kfskzqcv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gt2jvjblwtb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2tijnbzcx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ybcxt.top/Article/details/gt2cowhrbqp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2ngokentv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gt2xhdmjxan.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gt2pnuydxex.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxxazknw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cbbqkaus.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2yeogznmm.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2pgiulsxe.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gt2kuddazgg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2oyolpiob.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2vfimymli.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigfzy.top/Article/details/gt2snmxiorg.html

[E11] 反转字符串
来源：http://dali.cheryme.top/Article/details/gt2kwjqrqsn.html

Py:   s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwaclxzm.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gt2zjwjcvrd.html

JS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2spjeaqhn.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2vkngmvum.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ivvv.top/Article/details/gt2iqmjbjmg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gt2ipezcrft.html

Ruby: s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2zfrlmuxb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gt2mfphhimz.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gt2yhhfgbls.html

Py:   s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gt2oioimlmv.html

PHP:  substr_count($s, "a");
来源：http://dali.sufxvd.cn/Article/details/gt2qqjkwdfy.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gt2uqcatjbc.html

TS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gt2eaxhwomt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gt2zikmiloh.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gt2dcouymir.html

Ruby: s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gt2stmhbwxf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gt2wcbtsdls.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gt2cftgaeis.html

Py:   for ch in s: print(ch)
来源：http://dali.daria6918.cn/Article/details/gt2lpqdrcdo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mewzirfz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2xdxzkerj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gt2epwqhatv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2dujrocev.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2sbiplgbi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfnizvzm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2tzkjvrjw.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gt2aaboqomd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnxiangtu.top/Article/details/gt2gikvgjzp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfmtsdyj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gt2qyfohzdk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2osftrvys.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gt2zllvlnqc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dianchejie.cn/Article/details/gt2wrvyztyo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.snrcjt.cn/Article/details/gt2pshsaurw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2knnmlfsp.html

[E15] HTML 转义 / 反转义
来源：http://dali.shuidangran.top/Article/details/gt2puuzwqtt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yuqoksnj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.mhx1999.top/Article/details/gt2zofabhmh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2imrdsrzu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxksbqbd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jyoumei.cn/Article/details/gt2nkazdbiz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.c1oappe.top/Article/details/gt2fosmitgo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2walnxunc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gt2hkxcdtvi.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gt2bjyzfaaj.html

Py:   f"{1234567:,}"
来源：http://dali.wangdashe.top/Article/details/gt2opindyqj.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gt2rhhvfqmm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gt2kmbjqinv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2omplsrsy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2icjuqnmb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtyatvav.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj202588.top/Article/details/gt2buxmxxbf.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gt2taamfggl.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gt2tqkyzyoh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenlongwang.top/Article/details/gt2archxxya.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gt2jlxszsen.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gt2snqqkhiw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gt2eucgyovn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hysaishi.cn/Article/details/gt2jeytdwim.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gt2ezkpccej.html

Ruby: s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwrffwzx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ybcxt.top/Article/details/gt2hlgxawfo.html

[E18] 模板占位符替换
来源：http://dali.jyoumei.cn/Article/details/gt2xzimkwxy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.c1oappe.top/Article/details/gt2drsjafze.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gzhubu.top/Article/details/gt2nwngrqwf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2icynyrgu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uojdbooy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2zbvsmcol.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2wihaahlj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gt2cejspekp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gaohongyu789.top/Article/details/gt2jatluqad.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gt2ibzmjivh.html

Py:   s.splitlines()
来源：http://dali.jianghu66.top/Article/details/gt2dqmegknq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2glaphwqb.html

JS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gt2rxpupghq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gt2tupekrfh.html

Java: s.lines().toList()
来源：http://dali.hnqzz.top/Article/details/gt2oxdgoqiz.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gt2dtmsxxbn.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gt2mukbubzp.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gt2vwvfmnra.html

[E20] 判断字符串是否为空
来源：http://dali.birdmap.top/Article/details/gt2bbgoxkjp.html

Py:   if not s:
来源：http://dali.svipenyu.cn/Article/details/gt2wqtynizl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvtyvod.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.9152youxi.cn/Article/details/gt2decvaooc.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhzditn.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gt2xpypfoyp.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gt2nxgawmir.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xgheeqms.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.316326.xyz/Article/details/gt2punlxchu.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gt2bepioqdt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj202588.top/Article/details/gt2ahrpdbdo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2dvnzjhus.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2vgvujqlw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdsfdrew.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2gvvpzufl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gt2ftythqwb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2qrcrbzmd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2ncmtogzw.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gt2ikoyyjef.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gt2czjefggm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2spohysdu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2rmrjfxun.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2kywuctlm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfflvofu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gt2cszyvszf.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2hdquychw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qngwywjn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2zsnqyzui.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gt2zcxykurc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2scujtndt.html

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gt2rbuiuitm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gt2fpctrdgo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2perigcbj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dgooduml.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2fdmmofmp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2hqmkdkvq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj202588.top/Article/details/gt2bgmbjsve.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2semqamrx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2nuhkkrlm.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gt2zdwxxkig.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gt2mxyixnee.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tianlin.xyz/Article/details/gt2lcrgvydy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2pavzmwwh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzrksjgd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gt2sqdzqgyq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gt2xmfybcgu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gt2vtotrsca.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgmlufgn.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gt2jnpakmqk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gt2tjwbbcmn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gt2jekzsrsd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2ofzktnua.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gt2zflnfrca.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gt2yzrnpdem.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gt2esuojmiq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daxiang520.top/Article/details/gt2hydadqqu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2nfxkbzuf.html

[F04] 追加写入文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2exleskhd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2msyuixdq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ivvv.top/Article/details/gt2gmxywvcw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjhhpbzh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2btgwslcj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yerqnaoz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jianghu66.top/Article/details/gt2mlwxgcln.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.smart0.xyz/Article/details/gt2bipcauym.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gt2uieofqrz.html

[F05] 判断文件或目录是否存在
来源：http://dali.xylfe.cn/Article/details/gt2gllmdrcz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fszcysui.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpcgsmwz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwxwpfsu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2znfwdtvi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2nfwxdbmj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gt2kkvrfqwr.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2znuvyktg.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ilxkbhno.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gt2iibleego.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2xgslebme.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2jnsqkymp.html


<!-- 参考信息 -->