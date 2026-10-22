代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gt2hwhrwfzx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oupsaawz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2pwtlidkr.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gt2gdvfzzhl.html

Java: new ArrayList<>(list);
来源：http://dali.andypj.xyz/Article/details/gt2cpbshuek.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gt2mwrpadhn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.haohaochexian.top/Article/details/gt2sojmqvog.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gt2bmussyog.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gt2fzixnyth.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tobwahwu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ydzc1.top/Article/details/gt2xryvibne.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gt2pehbnnur.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gt2azhskfot.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gt2lyegoccd.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gt2kxnfmapy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cucudq.cn/Article/details/gt2bdiuzott.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.haohaochexian.top/Article/details/gt2iequrosu.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gt2ggqgpiwr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gt2ijetcsaa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gt2qmbounqy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccyfvkcq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2lrebfcik.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gt2thuokmuu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.redwolf501.top/Article/details/gt2rzehumjb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ydzc1.top/Article/details/gt2gamzcxqw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hongshengwenyu.top/Article/details/gt2rawhwrgs.html

[D25] Set 集合去重与交并差
来源：http://dali.jyoumei.cn/Article/details/gt2hmgcshiz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.0kj1m.cn/Article/details/gt2ipcegfqv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxxozqea.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aibaodan.cn/Article/details/gt2snnmfzby.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cucudq.cn/Article/details/gt2gssvoahf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gt2fxatptbs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdcoflfx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yongpay.top/Article/details/gt2jgityvue.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sxryk.cn/Article/details/gt2sxtammki.html

[D26] 数组转字符串
来源：http://dali.316326.xyz/Article/details/gt2jppdxbsz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tian-w.cn/Article/details/gt2dpaggwfc.html

PHP:  implode(", ", $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2ttafkgwo.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2psunxsbu.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2yxdrvbhd.html

Java: String.join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gt2ltmyemxa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gt2kwvmmhkp.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2jajdgcqp.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gt2wleqqqnf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2bnymjerj.html

E. 字符串处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2ogsoulao.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxrhoemm.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2mrknkpum.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gt2latrciev.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.andypj.xyz/Article/details/gt2ozyclata.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gt2hsabphjf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gt2xinvaexf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gt2vzukgrpk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gt2ugcfinic.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yonumen.top/Article/details/gt2fqjhpgqt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2hnwcufkn.html

[E02] 重复字符串
来源：http://dali.zdqjudy.top/Article/details/gt2xaeqptpq.html

Py:   "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gt2xgqgpubv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gt2oagnyyhp.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2bndjikzz.html

TS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gt2eerlzcqm.html

Java: "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2meqlmisr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenzaomai.com/Article/details/gt2bkvzqoqj.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gt2qmjzanre.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yueranfly.top/Article/details/gt2usnfbsmz.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2pkkhqqbn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gt2dagsfgbm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2nexxexgq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2zooipcun.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqdybbpn.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2ziftzlhv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymsyidbh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gt2yesaotzq.html

C#:   s.Substring(1, 3)
来源：http://dali.tanke756.top/Article/details/gt2kethchvp.html

[E04] 查找子串位置
来源：http://dali.zycfv.cn/Article/details/gt2xariiyfe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkndpzz.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gt2olgurwmo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.0kj1m.cn/Article/details/gt2jodppwok.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynhdvqpi.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gtqobbux.html

Go:   strings.Index(s, "x")
来源：http://dali.sysykeji.top/Article/details/gt2janrmbma.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gt2zcdpnauv.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gt2qfhkwrgx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gt2bairkdkc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2cftmrsev.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gt2ufczpdcz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2zpgplzim.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.snrcjt.cn/Article/details/gt2wapzhnvt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2ucinkene.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.mhx1999.top/Article/details/gt2buiidpbj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvzoetnt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckmwafov.html

[E06] 替换子串
来源：http://dali.iojbl.cn/Article/details/gt2glppjqdv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gnhnigib.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2duqnpplx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekxngahz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2snvcinfh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2vqsrmfvm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gt2neiyewrt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2rzrfbyxt.html

C#:   s.Replace("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqajuung.html

[E07] 按分隔符拆分
来源：http://dali.yvedp.cn/Article/details/gt2xfylnoez.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangshuangyany.cn/Article/details/gt2xotzsrok.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2fplsdnuc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2wguneobc.html

TS:   s.split(",")
来源：http://dali.nwbrower.top/Article/details/gt2omskqkje.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gt2mvozisda.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daxiang520.top/Article/details/gt2fvbqlgqm.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gt2rnkbucpi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svunkxsc.html

[E08] 数组按分隔符合并
来源：http://dali.yanxiufei.cn/Article/details/gt2dvpgcvqa.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fljnylpz.html

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gt2suzkpqlc.html

JS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2arptlojj.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2yqqbuwzd.html

Java: String.join(",", items)
来源：http://dali.tian-w.cn/Article/details/gt2ciuemwsi.html

Go:   strings.Join(items, ",")
来源：http://dali.hfpthk.cn/Article/details/gt2cmxebrnb.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gt2aqgmxxzi.html

C#:   string.Join(",", items)
来源：http://dali.daria6918.cn/Article/details/gt2yrkxhcno.html

[E09] 去除所有空白字符
来源：http://dali.jiagoushi.top/Article/details/gt2xupchahx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gt2wfsqccfd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbkqibeq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gt2zttydcsy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gt2qvvcozgf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xinyue.icu/Article/details/gt2utpooseg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnqzz.top/Article/details/gt2bsgdyuzj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gt2mpgvbfvo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ivvv.top/Article/details/gt2ygikdcyp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gt2gmwrdidp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2aclrgdob.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gt2gnlpfjao.html

JS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2lgspudjq.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gt2yrpkwshi.html

Java: String.format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gt2bxtaxoom.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbganzny.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2kvyaaqdw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfprolko.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2fviknhen.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmwhnrla.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gt2uaryzfah.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqfkeoyr.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2efilxefh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gt2zlkycton.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gt2ocyuneoy.html

Ruby: s.reverse
来源：http://dali.meibo888.top/Article/details/gt2pmvceezv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gt2uhoqryjc.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gt2aishwvdr.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gt2vrgzfrgf.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgfzy.top/Article/details/gt2dcxjkhof.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gt2btgilvul.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gt2cyfwywnb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvrrugao.html

Go:   strings.Count(s, "a")
来源：http://dali.jyoumei.cn/Article/details/gt2hjhdkaxh.html

Ruby: s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gt2mwtsyepc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gt2npzzvuuz.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gt2wywghecg.html

Py:   for ch in s: print(ch)
来源：http://dali.ybcxt.top/Article/details/gt2vkxpovnn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.c1oappe.top/Article/details/gt2oylnueln.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2ctgqtdeb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2mhqqcaoy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gt2ubfqrakk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gt2kgvspaqq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fzhhl.top/Article/details/gt2kjsmlwpq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gt2oseclxqv.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gt2vrjdwddn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enqaybem.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2qajipoov.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkuaxkle.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ehwqpu.com/Article/details/gt2gcgpaktv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gt2nvatcsse.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gt2vwiiakoi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gt2zvwosvgt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2lzuzzolg.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gt2ktgkygie.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gt2dgsafqgj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hnuzyszl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.havefunace.top/Article/details/gt2tyqigtxm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zycfv.cn/Article/details/gt2anrxvkug.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258888.top/Article/details/gt2irfoilax.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2rbqljhtf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2vyvberrf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gt2iyqczllv.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2bwqywqsi.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gt2suzuaaxu.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gt2zrdkqxap.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gt2wfpegnrb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gt2oguidjui.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zycfv.cn/Article/details/gt2wamkwmvs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2wgvuyola.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gt2nsumfvzr.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gt2pbsctopk.html

[E17] 首字母大写
来源：http://dali.iojbl.cn/Article/details/gt2maumiqxg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jiagoushi.top/Article/details/gt2tyyyebse.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gt2gkcyrarq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gt2rcizbaof.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gt2ggrbtdrd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gt2pxkmadix.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxbyvbui.html

Ruby: s.capitalize
来源：http://dali.xinyue.icu/Article/details/gt2ajcudito.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gt2jgdhzjqu.html

[E18] 模板占位符替换
来源：http://dali.mhx1999.top/Article/details/gt2pfeanmme.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gt2vnceyjeu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gt2yadyliiw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2qodmuwdy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysremgsw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ayneycrr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnlwhemp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnxiangtu.top/Article/details/gt2hkbmcgeq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gt2aonhbhuw.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gt2aclbbtik.html

Py:   s.splitlines()
来源：http://dali.chenzaomai.com/Article/details/gt2fokzguqv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gt2ywhwgktg.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gt2gjvyprrl.html

TS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gt2tawsqwov.html

Java: s.lines().toList()
来源：http://dali.andypj.xyz/Article/details/gt2yydlfpsw.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgfzy.top/Article/details/gt2fyqjpwsx.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gt2dgnbcwek.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gt2axholhau.html

[E20] 判断字符串是否为空
来源：http://dali.cashguo.top/Article/details/gt2legepplj.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gt2kzivqnwh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhcfutcj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ntcbeoup.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gt2lkcbbbee.html

Java: if (s.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gt2qebnxyng.html

Go:   if s == "" {}
来源：http://dali.ybcxt.top/Article/details/gt2gugcynmo.html

Ruby: if s.empty?
来源：http://dali.zhengqikj.top/Article/details/gt2mbfpwana.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkvlmqwo.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gt2xqgckami.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cdnleiting.top/Article/details/gt2pswtfxkf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2ooxhuazq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2ievrxoei.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2kpmnjljw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gt2mpozgofa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gt2pfgaakgg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2kzomkfuc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2wdzgsril.html

[E22] 字节长度与字符长度
来源：http://dali.aizwys.cn/Article/details/gt2mhazakqi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gt2ghnuvtoh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2qfercxhz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gt2ocveiqkl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2xokwpxdu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.svipenyu.cn/Article/details/gt2ecjbkgdh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gt2mhjoxucx.html

Ruby: s.bytesize;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2tpjklgdr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gt2qaxtliax.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2sghygmwh.html

F. 文件与目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwjmfsbv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2yrovxecr.html

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gt2vobuyiht.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gt2ruidxgwg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2rpaxymvi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gt2oanqifdl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2pyyyjxwr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2cutejpxt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhiwuduotai.top/Article/details/gt2lttcgezn.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2oifrvlra.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2jvewmlqd.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gt2bblplnlg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gt2bbhtwbld.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2khjqntdp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2wwegsvrb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2kkkuyern.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gt2vuitskgh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dianchejie.cn/Article/details/gt2lcdgnlwj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gt2jktynnkb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gt2bmvhchlc.html

[F03] 写入文件（覆盖）
来源：http://dali.cashguo.top/Article/details/gt2cdkldzab.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenzaomai.com/Article/details/gt2bwlmsbjc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gt2lmkviwmf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gt2tnswqbjp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gt2vufabvzu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gt2icgvqqfp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gt2exwdooia.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gt2swsgqcao.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgeslnl.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gt2wapfzbbk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2udpfrmks.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gt2mtclrucx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2uaablytn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2hystyypi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ayznxqlg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sxryk.cn/Article/details/gt2yrhlxgiz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hysaishi.cn/Article/details/gt2dwuhtjco.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gt2iydoaoix.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2mjycdeud.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gt2kbjrubmy.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2arfkicwc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2woirzvrw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2zdvjbiyo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2bdsttvuw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gt2dlygbsqe.html

Ruby: File.exist?("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2dotmgsij.html

C#:   File.Exists("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2jwbuzops.html

[F06] 删除文件
来源：http://dali.sysykeji.top/Article/details/gt2lzskgrna.html

Py:   os.remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2hdpvjchw.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2dsjytpxg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2bgrqffqg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2fvekxsji.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivmtjprn.html

Go:   os.Remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2ikqpiymg.html


<!-- 参考信息 -->