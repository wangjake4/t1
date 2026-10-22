代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.xziqi.cn/Article/details/gt2wzyxyemd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yvedp.cn/Article/details/gt2hkhakguv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jiagoushi.top/Article/details/gt2msxknail.html

C#:   new List<int>(list);
来源：http://dali.ppjwa.cn/Article/details/gt2beemwuwh.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gt2lwewarnw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2cuptpfzm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gt2bjrkrrdo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2raquhebj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkzyixiy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fzhhl.top/Article/details/gt2cinzimiy.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gt2pudukiac.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gt2awzqsdif.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gt2crbbmlyj.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gt2qipstzrf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sxryk.cn/Article/details/gt2mckzqtwf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ceuhemnt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gt2lbwnffaa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gt2gcgdbdfn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.kuanghao11.cn/Article/details/gt2moqtykcc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gaohongyu789.top/Article/details/gt2bjgzvoib.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tian-w.cn/Article/details/gt2ypczxcqc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gt2yaxpyipd.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gt2lhcfqjhp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxuanxn.top/Article/details/gt2dtekblrf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gt2tkjrypif.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fengsongda.top/Article/details/gt2kanqcdom.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.quarkkingdee.top/Article/details/gt2knamzbqm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dixqzruq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.316326.xyz/Article/details/gt2woktkshl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gzhubu.top/Article/details/gt2hcnsyiue.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gt2ytvbwnnz.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2jlwyhwjd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pycfn.com/Article/details/gt2kticwhih.html

PHP:  implode(", ", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olmwslzn.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxduxqh.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2cpgerznl.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gt2fqltebid.html

Go:   strings.Join(strs, ", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2imcnccyr.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gt2ijugcjve.html

C#:   string.Join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gt2ggrfhvhg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2vhlmqhof.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gt2qymrluxf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2eswmbrsw.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2mekfoaci.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.snrcjt.cn/Article/details/gt2jemcjvvj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gt2lfjhjmvk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlpxfhid.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gt2vybnhizg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gt2knabrhlc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2dptpmwwe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.smart0.xyz/Article/details/gt2iiwooobm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2furwluvj.html

[E02] 重复字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2mjsmrfqe.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gt2ottvexwh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fengsongda.top/Article/details/gt2zgbeerbi.html

JS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2fzcwfuhz.html

TS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2daedzoxu.html

Java: "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffjspxdt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtzeridw.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gt2bfleqdvd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guannengcc.top/Article/details/gt2elfyhbas.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gt2fzzgnyxd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gt2sykhsuqh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2klmqndqc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2myqkxvez.html

TS:   s.slice(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2etrkenyq.html

Java: s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2nmwofnzs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gogol.net.cn/Article/details/gt2nawokymw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.andypj.xyz/Article/details/gt2jkdusdlh.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2hrrhtkqt.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gt2qgcsromp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gt2zrireecd.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gt2knandjfr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cheryme.top/Article/details/gt2raqwoiuc.html

TS:   s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2avhmiuhw.html

Java: s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2voxjzzxy.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgfzy.top/Article/details/gt2qlzzqthu.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gt2gafdcsqn.html

C#:   s.IndexOf("x")
来源：http://dali.jianghu66.top/Article/details/gt2iilmluwk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pycfn.com/Article/details/gt2unazlifz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.snrcjt.cn/Article/details/gt2aykzifia.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gt2tvzfqpfy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2nsseqojl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cashguo.top/Article/details/gt2rszpguvy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2edeftcyx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aibaodan.cn/Article/details/gt2ercftxet.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnqzz.top/Article/details/gt2ticctprl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2hjoluqnd.html

[E06] 替换子串
来源：http://dali.zhongyouzk.top/Article/details/gt2cdlofrzz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gt2ekfbpuco.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gt2exubayva.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2suotwhgr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2jtqylhrb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2zyuqkagk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gt2tflehccx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2tartybjj.html

C#:   s.Replace("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2vlccenqt.html

[E07] 按分隔符拆分
来源：http://dali.sweek.top/Article/details/gt2lotlslwq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gt2ihsjbffr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2eqsfqbva.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2marbxitr.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gt2nmtgnsfd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sufxvd.cn/Article/details/gt2ejuwnybo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gt2yioqpjyq.html

Ruby: s.split(",");  s.split
来源：http://dali.feifeiyinyue.top/Article/details/gt2ugkzcgtn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cucudq.cn/Article/details/gt2izdlbcmw.html

[E08] 数组按分隔符合并
来源：http://dali.shuidangran.top/Article/details/gt2mnrdknhm.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gt2wiwkllhs.html

PHP:  implode(",", $items);
来源：http://dali.vqdsnc.cn/Article/details/gt2npymcxvo.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2xmxyasij.html

TS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ldkgtlfb.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gt2zwaiuuzh.html

Go:   strings.Join(items, ",")
来源：http://dali.hnxiangtu.top/Article/details/gt2zrhaprld.html

Ruby: items.join(",")
来源：http://dali.xinyue.icu/Article/details/gt2wmamyfuw.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gt2pztnkdhi.html

[E09] 去除所有空白字符
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgrrmouh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gt2bqjonuzi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2fmbrlqqt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gt2pianfdka.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gt2jcfkgeqa.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gt2dyoqyyrz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gt2igobfwkw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tanke756.top/Article/details/gt2iqiqfyon.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gt2skwhmwrf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gt2dyqxdjhp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cashguo.top/Article/details/gt2rytjkrhn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbfiuqkb.html

JS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2apioafzk.html

TS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gt2kwtccmki.html

Java: String.format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gt2qgaweork.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gt2lbeqijdm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bctulhts.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gt2aocwbjuo.html

[E11] 反转字符串
来源：http://dali.tanke756.top/Article/details/gt2sosntfjd.html

Py:   s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gt2bgjjdyyb.html

PHP:  strrev($s);
来源：http://dali.meibo888.top/Article/details/gt2slqeoksp.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fijxmtbw.html

TS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2otanjvwb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gt2ewcqidha.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gt2dkesvoke.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzuvxnlc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2fptlcbkz.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gt2fkitetkt.html

Py:   s.count("a")
来源：http://dali.smart0.xyz/Article/details/gt2hcnnnwxi.html

PHP:  substr_count($s, "a");
来源：http://dali.316326.xyz/Article/details/gt2emdpfwyq.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gt2aryiichq.html

TS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gt2jvbsohyz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zycfv.cn/Article/details/gt2iqtgruzk.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gt2uunldmgl.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gt2hhreuuvk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xscofygx.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gt2xhwzawat.html

Py:   for ch in s: print(ch)
来源：http://dali.c1oappe.top/Article/details/gt2emzvhtdd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenzaomai.com/Article/details/gt2bfbbabmm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2lizgczzd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2xlxpgxya.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2qkqzlqfo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258.top/Article/details/gt2ciemzbyi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gt2nqbcucki.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj202588.top/Article/details/gt2wjeslfqm.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gt2bckhrhiz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gt2bftkisiy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abgzncxo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ydzc1.top/Article/details/gt2ojugmgbt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gt2lktrsteq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2htcqabvs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gt2dmiznbzl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gt2nsnryxpy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2ohwzxnwd.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gt2nbcjljwu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gt2ukrhueur.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gt2mbedebjf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmdubfrp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2twceiior.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gt2qndwjlvv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shuidangran.top/Article/details/gt2zthqbtjw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2khkrgpsw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gt2gcgzildx.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gt2jafkqvoe.html

Py:   f"{1234567:,}"
来源：http://dali.daria6918.cn/Article/details/gt2rfvdkumf.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gt2duivspyn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gt2quhslacl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rygfnqeu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gt2ldtjxlbc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gt2keeqlweb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gt2anaghkpz.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywpojuch.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gt2kmxhyorv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gt2tsiuzoam.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.0kj1m.cn/Article/details/gt2yzpodmxk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gt2qiltgfzu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gt2kjhbqlop.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zycfv.cn/Article/details/gt2tlytfiqt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqsjhpcx.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gt2zgtcntxd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbzteudx.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gt2ycthwune.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gt2pvwhjsed.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jyoumei.cn/Article/details/gt2vdekfcrn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzetlbfi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2hjjagdnv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2evdducfb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2dpsilfwx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gt2lfncasum.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gt2hqjcnczi.html

[E19] 多行文本按行拆分
来源：http://dali.sxryk.cn/Article/details/gt2wpiczfwm.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gt2dshkmgxr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2wgwzepdk.html

JS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gt2vcahyzrl.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2kbpbovmv.html

Java: s.lines().toList()
来源：http://dali.jianghu66.top/Article/details/gt2rnlqlxza.html

Go:   strings.Split(s, "\n")
来源：http://dali.haohaochexian.top/Article/details/gt2sjzqhizd.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gt2ysfancob.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gt2expavvlz.html

[E20] 判断字符串是否为空
来源：http://dali.jianghu66.top/Article/details/gt2roiavyzr.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gt2dniegmpu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.vqdsnc.cn/Article/details/gt2nuweikdg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gt2fqmynkgn.html

TS:   if (s === "") {}
来源：http://dali.ppjwa.cn/Article/details/gt2oqycotmi.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ovmabdkf.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gt2ukqbjeae.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gt2dzcabtgr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbvojdvi.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gt2uzykamqz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.0kj1m.cn/Article/details/gt2xavcubrh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2xboqojno.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2xwnifplv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gt2hxoacdph.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2wbvhaaki.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gt2gmjhpxhw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2jrcfeapr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2mtoaaoiw.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gt2eurlynhl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2khymtspc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gt2gmsvjcoz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2bmnhbhkc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gt2jnmnsykd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofhwfyyb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gt2nopgnpva.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2jbeexxeq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gt2jzyvihoe.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2zaeqpano.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gt2odezizpl.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2tugshnbi.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gewbpnon.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sufxvd.cn/Article/details/gt2jxjuowde.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2aqqnajsv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gt2saxuuuub.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2phmdwyip.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2mcdmhqps.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2osvrbpig.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uruewxks.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2ngcabxtn.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gt2djomeajy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cashguo.top/Article/details/gt2cphvotnr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gt2dfdfovxe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gt2gmytaqmw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gt2hjneugoq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubdteqzh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sxryk.cn/Article/details/gt2iuhrsgns.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tanke756.top/Article/details/gt2wleicwtj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gt2wuirrlsa.html

[F03] 写入文件（覆盖）
来源：http://dali.dianchejie.cn/Article/details/gt2gfszrilm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gt2cubaptqe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2ninjyfej.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2xmxeqsab.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2fsctrshm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fzhhl.top/Article/details/gt2uazghlru.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gt2rudtutnd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dklvyjhb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gt2hncvqddx.html

[F04] 追加写入文件
来源：http://dali.yj202588.top/Article/details/gt2nchfjdfs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gt2wxfpktnd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gt2yaqzhwue.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gt2awdidghw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2irawmudr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gt2dlryhrkt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gt2cshfzhuv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhengqikj.top/Article/details/gt2rksprnxq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuxming.cn/Article/details/gt2qckndmdm.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gt2nscxrfng.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gt2jheivvvu.html

PHP:  file_exists("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2liykbskh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2itpgmmwy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2whgbcpxi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2oedrbpzj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gt2ocuxyhmm.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2cyzhenyq.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2sppbnegp.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gt2kpuonpni.html

Py:   os.remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2fardvfbx.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2vtlatuja.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2thxuzhit.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2adrhkpgc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2bzssdart.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2wfgqsiut.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2egtcqxya.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2wmfqimud.html

[F07] 创建目录（含多级）
来源：http://dali.zhengqikj.top/Article/details/gt2qunmbbqi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gt2dreiotxc.html


<!-- 参考信息 -->