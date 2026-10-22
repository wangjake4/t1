代发 wailian999

[D23] reduce 累积计算
来源：http://dali.zhixingplan.top/Article/details/gt2wlasjitu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2vqlfrqbq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xziqi.cn/Article/details/gt2tdottrur.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gt2eogwjbfa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2pvgvinxa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gt2zdsvoaqf.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zsisorex.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gt2qbhwkdnw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fzhhl.top/Article/details/gt2nobgppve.html

[D24] 字典 / Map 基本操作
来源：http://dali.sweek.top/Article/details/gt2sfieobvk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ztvxwesv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gt2nosaopmx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gt2riqikmnb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2ryrzfirs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yonumen.top/Article/details/gt2dpobmzss.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gt2nzcvojxq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gt2istvdnna.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guowangkeji.top/Article/details/gt2ohxvxqne.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gt2xapzasuo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gt2eagmwqhu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gt2qfgosfkh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gt2hawwlycy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigfzy.top/Article/details/gt2zpujnvmv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2urucfdnc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.snrcjt.cn/Article/details/gt2jmzhrcem.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgfzy.top/Article/details/gt2wjpcqjcw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.smart0.xyz/Article/details/gt2sqsgiphn.html

[D26] 数组转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwjrjign.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ybcxt.top/Article/details/gt2txzttaei.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2nyquwiby.html

JS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gt2uysiozkd.html

TS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gt2xhaftysu.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnpbhdn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hammf.cn/Article/details/gt2eiobarga.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2lpsflobp.html

C#:   string.Join(", ", list)
来源：http://dali.hammf.cn/Article/details/gt2ixvpwhhx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jlszcbnr.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gt2wnppciqm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vsjxdsbn.html

[E01] 拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2bjlqbate.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gzhubu.top/Article/details/gt2afqtcgpi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ivvv.top/Article/details/gt2ttpscams.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gt2dipdskzo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gt2ghurzkxj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gt2irsgcmhg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gt2uqbmoxlr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gt2nugdbqhp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pyaplwsk.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gt2lanqheqe.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2noqcqkzz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gt2vyoldlue.html

JS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gt2jqariban.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2jgkwigps.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2foxddkjk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.meibo888.top/Article/details/gt2ihqyhida.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqxwfffo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tianlin.xyz/Article/details/gt2iduyzckk.html

[E03] 截取子串
来源：http://dali.fzhhl.top/Article/details/gt2awhfqkxp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gt2tfqvzqsl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2zwiffpew.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gt2wijkrnpa.html

TS:   s.slice(1, 4)
来源：http://dali.meibo888.top/Article/details/gt2berennnd.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2dvhcgolf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cashguo.top/Article/details/gt2qdszyumg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shzxlz.cn/Article/details/gt2jiqqjonb.html

C#:   s.Substring(1, 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zylfovkb.html

[E04] 查找子串位置
来源：http://dali.zhengqikj.top/Article/details/gt2xrncvgpb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gt2yhjmafsc.html

PHP:  strpos($s, "x");
来源：http://dali.aizwys.cn/Article/details/gt2hjrqdhrw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gt2zkfmjeiv.html

TS:   s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gt2ckgssuej.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gt2ydggihgr.html

Go:   strings.Index(s, "x")
来源：http://dali.ivvv.top/Article/details/gt2jcbcjwcn.html

Ruby: s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gt2ztnzdycs.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2dspncklg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gt2hkibqgcj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gt2jgjlpxkx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hysaishi.cn/Article/details/gt2cdgrfuvp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnrefvl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gt2qrstowxl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2reihpqhv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.9152youxi.cn/Article/details/gt2lcezrgyg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenlongwang.top/Article/details/gt2rjyzlilb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2cnsnytvg.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gt2klpfnjrz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gt2wflzocmi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gt2digibksh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2uyunsivg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2fraetiwt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2wcerpeyt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gt2anactjdd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2syuxqchk.html

C#:   s.Replace("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2oovuzpsa.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2bcgzehhx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gt2pbvoohoc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj202588.top/Article/details/gt2oynkltol.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhttcrxx.html

TS:   s.split(",")
来源：http://dali.guowangkeji.top/Article/details/gt2aorouwsq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gt2mcwehbto.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hammf.cn/Article/details/gt2exwjvjij.html

Ruby: s.split(",");  s.split
来源：http://dali.0kj1m.cn/Article/details/gt2opmyqila.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuanzhike.top/Article/details/gt2dxmoiynt.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrrqdtq.html

Py:   ",".join(items)
来源：http://dali.tanke756.top/Article/details/gt2cvwcjlhk.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wkbynamc.html

JS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsiprsav.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gt2jggjstow.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gt2zfzpyxgz.html

Go:   strings.Join(items, ",")
来源：http://dali.hnxiangtu.top/Article/details/gt2ranelqnt.html

Ruby: items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2elatbnmy.html

C#:   string.Join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gt2igibwbcw.html

[E09] 去除所有空白字符
来源：http://dali.c1oappe.top/Article/details/gt2xuwlrfru.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2yfbvbich.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2fhvzjntk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gt2osmanrhk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gt2duuwdhzj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gt2xecksaah.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gt2psqjdsdv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2pqxtwjky.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gt2boubyhdl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gt2dxklacel.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2nvgxmpzd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangdashe.top/Article/details/gt2vivzctxo.html

JS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gt2ngvmipyw.html

TS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gt2jsbcovug.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2kxibfddf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gt2utdmkvqg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gt2fgjjksbx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnzyhlyq.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2edljumfl.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hznubfdu.html

PHP:  strrev($s);
来源：http://dali.ydzc1.top/Article/details/gt2txblybtt.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2mbsaqzmd.html

TS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gt2tujzyduq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gt2mnwszdqn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gt2aprofbbh.html

Ruby: s.reverse
来源：http://dali.haohaochexian.top/Article/details/gt2izhyrohq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gt2atounzqd.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gt2ymueovfm.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ocdfbcwy.html

PHP:  substr_count($s, "a");
来源：http://dali.chenjidiqi.icu/Article/details/gt2jyoexncw.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2drmqhicb.html

TS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gt2bmvrjqpw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigfzy.top/Article/details/gt2hxnpwlhf.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2plwzlgnb.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gt2wqdwgryx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gt2zvaihzuo.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gt2igbekfnr.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gt2rrylvihw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zycfv.cn/Article/details/gt2nczzoquy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gt2npydpfii.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2omjnfxwc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2pgwztwdj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yonumen.top/Article/details/gt2yqdccjcz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gt2irsdbseb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dtfiwnrw.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gt2hpkgglwv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gt2yoooipoq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afwsfmht.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gt2kuolssrt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2dqopuvux.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gt2dqpgixvv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gt2xbkozlwc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.meibo888.top/Article/details/gt2rvzcbnbz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2cvecbghe.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuxming.cn/Article/details/gt2nhxjwrcg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gt2pqzqgxvr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gt2dxzjxwov.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.meibo888.top/Article/details/gt2cybybfra.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gt2oepupncd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gt2gldcfzxs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2ktfcutha.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lenjkgqa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixpchyqx.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gt2yasnyamc.html

Py:   f"{1234567:,}"
来源：http://dali.shzxlz.cn/Article/details/gt2bvlmckmc.html

PHP:  number_format(1234567);
来源：http://dali.snrcjt.cn/Article/details/gt2zwdqplyz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqrqlbc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gt2shrpesla.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vaysfskk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhoulong.xyz/Article/details/gt2fhuntyag.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2eymqmcbo.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gt2myxglgxl.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gt2bcpkhqyf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhengqikj.top/Article/details/gt2fwnoylyj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2fwhkmxje.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2ahpxjgld.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2vldtgjcv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2cmttzbif.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2auvwqljc.html

Ruby: s.capitalize
来源：http://dali.nwbrower.top/Article/details/gt2maznxpvf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hammf.cn/Article/details/gt2gfrapoop.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gt2qwtacprl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gt2svicetqb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gt2jekdrkik.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2pwtcwhda.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2hwebnspz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2fcbqaqdf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2rniikqoe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.kuanghao11.cn/Article/details/gt2qtndlpmf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gt2hhpdatue.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gt2tuiwzaja.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gt2uwckzihk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2vopqzkrz.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwisnxzb.html

TS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gt2jjzmowrz.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gt2fbzumrnr.html

Go:   strings.Split(s, "\n")
来源：http://dali.guowangkeji.top/Article/details/gt2uxogsrsc.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gt2wepujkos.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gt2ezqfinwx.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gt2lmotvcrq.html

Py:   if not s:
来源：http://dali.yuanzhike.top/Article/details/gt2hifjxzgu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gt2apxpyxws.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxjhwmpp.html

TS:   if (s === "") {}
来源：http://dali.gogol.net.cn/Article/details/gt2apqilcxc.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gt2mbdlkggt.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gt2pycojdmp.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gt2kfefmefm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258.top/Article/details/gt2hymhcwws.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gt2fqyemten.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyharjrj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wksuuord.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2hsvsqrln.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2lwpldzvo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2ggbcgjyg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlcltfjh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2ebauwgyt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2fxfywtio.html

[E22] 字节长度与字符长度
来源：http://dali.guannengcc.top/Article/details/gt2kpbmjxdi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qbugywlu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2puxvkeje.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2yclqgchu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gt2mrailcax.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gt2utqwvkra.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jianghu66.top/Article/details/gt2zbzvznag.html

Ruby: s.bytesize;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdpkdgnv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gt2gogaakxr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcmoemov.html

F. 文件与目录
来源：http://dali.316326.xyz/Article/details/gt2gktvxjep.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2jqsuiaig.html

[F01] 读取整个文件
来源：http://dali.jinqigufen.top/Article/details/gt2nviywlhg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guannengcc.top/Article/details/gt2ivvdzaro.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2flhabrau.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gt2avjsmjds.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2gcrlroah.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2kwuiizxa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ycyhohrk.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2ncemyfnj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2htrqwbdj.html

[F02] 逐行读取文件
来源：http://dali.ybcxt.top/Article/details/gt2wucywndv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigfzy.top/Article/details/gt2swyuxjab.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gt2rvzsjddm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2dqgzdxgw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gt2vkzoewxf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2aayvkmqn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gt2vwscawri.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzivdzto.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfbqyuts.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gt2njhsltzb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gt2eusschhp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2hnyrffjd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2eregmlwr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gt2nyxlqqtq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ydzc1.top/Article/details/gt2jksoldip.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gt2rrothdva.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aizwys.cn/Article/details/gt2ovjndbzv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2litphkeu.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gt2hxyzvkxo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gt2swublebx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.0kj1m.cn/Article/details/gt2imwcxgzm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gt2wyhtpqnh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2dtsuaply.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gt2uepidtfz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2xaqfuoyx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cjnbtfrp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ppjwa.cn/Article/details/gt2zdehjlia.html

[F05] 判断文件或目录是否存在
来源：http://dali.jianghu66.top/Article/details/gt2gbmkhrrn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gt2ckyzdnjc.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2humbvgup.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2bjcwpogz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2nsuflyhh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2qfzlvkhq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gt2ybkhtzjo.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2smfinvgg.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2hrmkjetm.html

[F06] 删除文件
来源：http://dali.c1oappe.top/Article/details/gt2lduvwfpn.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2nsqygtgz.html

PHP:  unlink("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2wtqkykmk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2xmljpopj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2umkmxifz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2jczzltjb.html

Go:   os.Remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2kzymdgvg.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2afatkqzo.html

C#:   File.Delete("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2xndwejwz.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gt2rlyqxseq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gt2fpfqkbyr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qupkjjur.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2phhoyruz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gt2xctuyxad.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gt2wigfkjqu.html


<!-- 参考信息 -->