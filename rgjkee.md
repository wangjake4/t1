代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpngdqduw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gtfuvkmksv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gtsxtkwrbk.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gtcorhudsp.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gtdtnbndfu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.vqdsnc.cn/Article/details/gtollixlfl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gtnyxtboax.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gthunyejcq.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gtzbxbnbzp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shzxlz.cn/Article/details/gtfdsvvifb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pycfn.com/Article/details/gtpswupqey.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gtubtsdtxg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtotiffhqy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gtkdnogtol.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtfrfkpdts.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gtlggybwzo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gtvzmrlzbs.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnkhqcih.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258.top/Article/details/gtwziyonal.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guowangkeji.top/Article/details/gtatecoaaj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cucudq.cn/Article/details/gtbkxolort.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtxaoozutd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnqzz.top/Article/details/gteutqhipd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gtxfjfjzve.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gtaeixjxgh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gtggpcdaij.html

[D25] Set 集合去重与交并差
来源：http://dali.feifeiyinyue.top/Article/details/gtyrjkbfle.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xziqi.cn/Article/details/gtzlcpztfj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tian-w.cn/Article/details/gtyuwnqjvl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gtcdoplltd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tianlin.xyz/Article/details/gtzhqfygac.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuanzx.com/Article/details/gtthguvuxd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gtcexycbqk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.havefunace.top/Article/details/gtizkhfyfx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gtpeipwbgf.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gtxhtzaful.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtbwyvubis.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gtyxmzaqnk.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtkziaukme.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtgqwgtkfr.html

Java: String.join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtpdzbcyku.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tanke756.top/Article/details/gtarsxgijy.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtkbzxdjhc.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtxfhaeala.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtokfsbtuy.html

E. 字符串处理
来源：http://dali.birdmap.top/Article/details/gtmtgukjqv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtcvbhiscq.html

[E01] 拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtjjvpjowz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.vqdsnc.cn/Article/details/gtvinoyryh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgfzy.top/Article/details/gtesxkqsov.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtsgubqayu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtyhbkooib.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gthugsnngk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gttsyvpafs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gtrtrqjnyh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtotwkonji.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gttnymxphy.html

Py:   "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtzvuoiuej.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtambehwgv.html

JS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gthcbzqtqy.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtcfxbremy.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtkyyrtbla.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gtymfxgbxe.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtrsqrvkqe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.0kj1m.cn/Article/details/gthpznsjsm.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtikgzisia.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cashguo.top/Article/details/gtduawxaql.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtrxcableq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gtrsksbpgs.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtaxivaiqk.html

Java: s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtwipmsfza.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtprgzlvze.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ppjwa.cn/Article/details/gtqitsylux.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gtbmxxeoip.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gtmhowtdsc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gttcnpkcdo.html

PHP:  strpos($s, "x");
来源：http://dali.zhongyouzk.top/Article/details/gtwbtvantg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gtybxbcyqa.html

TS:   s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtwhdslles.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gtwsacmcvs.html

Go:   strings.Index(s, "x")
来源：http://dali.zdqjudy.top/Article/details/gtumoxlrgp.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtzmkeezcz.html

C#:   s.IndexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtnibjfjxc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigfzy.top/Article/details/gtddkrdbxm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ehwqpu.com/Article/details/gtkvhlujrf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jlsjyb.cn/Article/details/gtlcvfyxcx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsumofars.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cucudq.cn/Article/details/gtizptzvgx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtbbskckpu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gtkhrvvziv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gtfembsnbt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtkimasuya.html

[E06] 替换子串
来源：http://dali.meibo888.top/Article/details/gtyececudy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtqzwncsbd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxuanxn.top/Article/details/gtbgbxbjkr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtepcjefsl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtciehbovs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtkqxxasnz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtzzytqwzy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtziodvaia.html

C#:   s.Replace("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtdhdfaznj.html

[E07] 按分隔符拆分
来源：http://dali.zdqjudy.top/Article/details/gtjehagwmv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hysaishi.cn/Article/details/gtgueapnzt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtkupnosxz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxuanxn.top/Article/details/gthwyxslfc.html

TS:   s.split(",")
来源：http://dali.quarkkingdee.top/Article/details/gtkfpoawzd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gtiqqjszbd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtgghlezqs.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gtyckucflt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pengpengdd.cyou/Article/details/gtvsjdxjhf.html

[E08] 数组按分隔符合并
来源：http://dali.xziqi.cn/Article/details/gtduxwnnga.html

Py:   ",".join(items)
来源：http://dali.yueranfly.top/Article/details/gtagctzboz.html

PHP:  implode(",", $items);
来源：http://dali.wangdashe.top/Article/details/gtkaascdar.html

JS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtvwdjbdtn.html

TS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtskgysoyo.html

Java: String.join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtjtzalysa.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gtlnzjhfpc.html

Ruby: items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtfymzigki.html

C#:   string.Join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gtffbcqkns.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcyfniqq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gttznnbaev.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtibjqnbss.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtuiavemts.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gtpziqamjn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtmbblnhnd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cdnleiting.top/Article/details/gtrznzjvsq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gtqgfyyvzm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gtgnyldkbs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gtoibitghm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtxayywbai.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gtfnzybfut.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtfhxrbkct.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtbuvrwifo.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtyomqcbfu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtobpyhhee.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiclpbqv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gtiiifrawj.html

[E11] 反转字符串
来源：http://dali.yongpay.top/Article/details/gtbflzseos.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gthxmvduup.html

PHP:  strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtlyvmkvjk.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtivnyknpu.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtgfdeoojz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gtzfxexruc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gtwadnttkd.html

Ruby: s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtzmwusoyz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gturkmauhg.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gtqtntysnb.html

Py:   s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtldxjrejt.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gtwwklbliy.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gtefuwnbmr.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtvxsvhiqb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gtibpinzso.html

Go:   strings.Count(s, "a")
来源：http://dali.pengpengdd.cyou/Article/details/gtooknxiwm.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtpmvjqwut.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnvmpdft.html

[E13] 逐字符遍历
来源：http://dali.jinqigfzy.top/Article/details/gtjylvyhlu.html

Py:   for ch in s: print(ch)
来源：http://dali.cdnleiting.top/Article/details/gtzjjejfyv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gthqzyohzw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtojwobiwm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtogabnmpv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtqkszptgn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gteddijkoz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gtezarqbbf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gtiymincbo.html

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gtazdqdgzm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gtaljdhfnp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gtwwjahjws.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gtlonjzqno.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yangfankeji.com/Article/details/gtgmvrnamc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shuidangran.top/Article/details/gtynrwlyxw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gtohqewsct.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.iojbl.cn/Article/details/gtmehidsqg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tian-w.cn/Article/details/gtdrlqxxzb.html

[E15] HTML 转义 / 反转义
来源：http://dali.dashuyun.cn/Article/details/gtvtgmhgpy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gtisppirdn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gtjmbwrsib.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gtfbmimlli.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guowangkeji.top/Article/details/gtbxleonbj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtvuehcdgm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gtasnamcit.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gtcfucrzyt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gtumqzbtjv.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabdfdsnk.html

Py:   f"{1234567:,}"
来源：http://dali.wangdashe.top/Article/details/gtckjxfeml.html

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gtefwvqnws.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtsyhxrdtf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtpbyvezai.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gtsvnrtbni.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gtdsbryrva.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gtnomyssfs.html

C#:   1234567.ToString("N0")
来源：http://dali.sweek.top/Article/details/gtqdzhwvyu.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gteptkudeu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtxfpntssj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tian-w.cn/Article/details/gtqiugwkbq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtwgfwggel.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtiyfurzpo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenlongwang.top/Article/details/gtfcpzxfih.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gtbenxaxdr.html

Ruby: s.capitalize
来源：http://dali.yongpay.top/Article/details/gtowdpotpa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gtwrhtloic.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gttauxcltr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yueranfly.top/Article/details/gtebpiuslg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hongshengwenyu.top/Article/details/gthyyzrmun.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtqoagzbst.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtpgsdzgou.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtglvzxgcx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.316326.xyz/Article/details/gtbsvyyfbq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtdbdixyjp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtwxjcpglf.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gtqruuomnr.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gtcvzzzwzg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gtcuwsoggx.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtlaedttmg.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtbavxhogz.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gtpnmigtji.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gtouturnji.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gtoghjsxcs.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gtfcgkauyp.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtumrsugay.html

Py:   if not s:
来源：http://dali.9152youxi.cn/Article/details/gtsxgrxjir.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yueranfly.top/Article/details/gtmsnnfuly.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cheryme.top/Article/details/gtfihuyuav.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gttzxwidhd.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsvfotxh.html

Go:   if s == "" {}
来源：http://dali.tanke756.top/Article/details/gtsstwoxlp.html

Ruby: if s.empty?
来源：http://dali.hnxiangtu.top/Article/details/gtmrotmuuz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtukuktkup.html

[E21] 超长截断加省略号
来源：http://dali.yangfankeji.com/Article/details/gtdmqonega.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtsldcwkro.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtstgacxsf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtbhvcffyx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtlyeqbizk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtvhfxdarl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fengsongda.top/Article/details/gtnpnmymmh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gthicocxqb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtwumqdqgq.html

[E22] 字节长度与字符长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpygekdm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gtbdixnhig.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtzadqexzw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtvmrbidmi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtogdfamsc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaolgvdtu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fzhhl.top/Article/details/gtvtaivfqo.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazvcvspy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtpsxvfqkm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtakshjobf.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gtnvrptirz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffyffprg.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gtzufipptd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gtyydrbmfz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtkjuqpibh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gtuuixlkdb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gtztfbuvuh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtvxwvheum.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gteuovjbxd.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtblukudlt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtvuikrixp.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gttgsjpcwn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangshuangyany.cn/Article/details/gtrfefcppb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gtkcsjybtl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtmjdcmdcq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtrzqbokpp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtbckprqgp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gtgcvejacs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gtqbainyro.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gthwytrehs.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gtmxhlqakf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmkhhlez.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimoakpay.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtucxnegax.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtmszifvau.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtcgmdjzdi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sxryk.cn/Article/details/gtqyrikaim.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtrbvsqijh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtyylmypmj.html

[F04] 追加写入文件
来源：http://dali.yvedp.cn/Article/details/gtcxnmiahk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gtbordzkps.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenlongwang.top/Article/details/gtwnkjsidt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtifeznnxw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gtxkvilumq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guowangkeji.top/Article/details/gtgsuqolvs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtpuppqyui.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gtoiaqvtkd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtfnthvygv.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtmopwqwqh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtuhiddwzo.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtsfchvkbs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnyhkrva.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtornhicni.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtkqyuhvsx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gtfxauyyhi.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gttszzznba.html

C#:   File.Exists("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtxzbuduwb.html

[F06] 删除文件
来源：http://dali.redwolf501.top/Article/details/gtsdeolifx.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtemdkjxph.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtiivyojyb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtfvkngauw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtkeffrbyj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtyrnrmkzi.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtkyfiudgh.html


<!-- 参考信息 -->