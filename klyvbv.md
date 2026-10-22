代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.cheryme.top/Article/details/gt2pqqxqolh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhiwliue.html

Ruby: arr.dup;  arr.clone
来源：http://dali.kuanghao11.cn/Article/details/gt2tqrmnqup.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gt2hdsuptwx.html

[D23] reduce 累积计算
来源：http://dali.daria6918.cn/Article/details/gt2jpewiovg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2jsgnpxnt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gt2dywhhnbx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gt2swhjaqkj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvmiuqgs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gt2uytroukf.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gt2qypvvvjl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gt2vlnkxbdk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xylfe.cn/Article/details/gt2bzciwahp.html

[D24] 字典 / Map 基本操作
来源：http://dali.meibo888.top/Article/details/gt2srtoqnym.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gt2hpbafbqp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.havefunace.top/Article/details/gt2cmqugxnk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2ajsockvs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2vgaaszzr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigufen.top/Article/details/gt2sezngdwe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.birdmap.top/Article/details/gt2lkoghklu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hywenlv.cn/Article/details/gt2qlntdibh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.andypj.xyz/Article/details/gt2yoonmnrk.html

[D25] Set 集合去重与交并差
来源：http://dali.aizwys.cn/Article/details/gt2uuydstpe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezlcxpew.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gt2aastvizf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2iaexkxxz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dashuyun.cn/Article/details/gt2ezgolkbu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gt2ichnbqqr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.bjfxy.top/Article/details/gt2akyzmnub.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gt2jwbwjwmj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gzhubu.top/Article/details/gt2kygqhmay.html

[D26] 数组转字符串
来源：http://dali.hnqzz.top/Article/details/gt2vshoadtm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2arjybtna.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqscjiig.html

JS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2khsurypz.html

TS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2uftiakll.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gt2tkyntbfe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gt2mgbnplme.html

Ruby: arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2yneliqfm.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gt2jtkaoxrx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2lzfzxeob.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjxxlhfz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2pmtwubea.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2quemdqwj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gt2qgzyhxkt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gt2muzphthv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2qbcfewfz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gt2ceoibavc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ponmitqp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cqqwz.cn/Article/details/gt2tgrxyfgu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnohgucd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2xzcefuat.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gt2rkjpgooj.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gt2lmlzwvsr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuanzx.com/Article/details/gt2qllknwss.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gt2rgyvyfks.html

TS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2ghcmzxdq.html

Java: "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2jtcgvkcr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2vjxpxheu.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2jujxfead.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daxiang520.top/Article/details/gt2qbjqtzqa.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gt2gzlascqw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.0kj1m.cn/Article/details/gt2soehqhuv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2arpkjnmv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngrymont.html

TS:   s.slice(1, 4)
来源：http://dali.cheryme.top/Article/details/gt2vgpvlacp.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2soxxwois.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gt2jngvyqmy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gt2kqjabdpn.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gt2hsizkclj.html

[E04] 查找子串位置
来源：http://dali.yj20258.top/Article/details/gt2ssjiceuk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gt2eiaolamy.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gt2aoaglsyh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cqqwz.cn/Article/details/gt2fqeptjwi.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gt2escplkrm.html

Java: s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2bvxfcppv.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gt2jxufmrpv.html

Ruby: s.index("x")
来源：http://dali.cucudq.cn/Article/details/gt2oeygpoyx.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2ytydkxpe.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ivvv.top/Article/details/gt2wtsjmdpl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zdqjudy.top/Article/details/gt2otochype.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zdqjudy.top/Article/details/gt2jtxgblnr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gt2jouzqpvs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qjlijpmn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2hxoqkzqx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.svipenyu.cn/Article/details/gt2iaujcuto.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shuidangran.top/Article/details/gt2glzkxuve.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cndzqhmk.html

[E06] 替换子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wgykdmrd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2ppblwmso.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gt2icntjqqd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2zhgijxxc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkrvwuzh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2blbcmsad.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2zzwmqowx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vyravimm.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbnfjfsw.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2phpbiqli.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gt2tgptrsaz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2bditpjyd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gt2epihipol.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2pfzricmg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yongpay.top/Article/details/gt2yjhuhfnh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhixingplan.top/Article/details/gt2mgphwxod.html

Ruby: s.split(",");  s.split
来源：http://dali.hywenlv.cn/Article/details/gt2xrwkovao.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gt2djjnccqg.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gt2dqogfwpb.html

Py:   ",".join(items)
来源：http://dali.cucudq.cn/Article/details/gt2frilkoqz.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gt2dqmqnzkf.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2soiugthc.html

TS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2xocqmgev.html

Java: String.join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gt2azmwrfxw.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gt2pyapnpbf.html

Ruby: items.join(",")
来源：http://dali.gzhubu.top/Article/details/gt2oreehjmx.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gt2glveqxro.html

[E09] 去除所有空白字符
来源：http://dali.ppjwa.cn/Article/details/gt2wziieqyq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gt2adzoatnc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xinyue.icu/Article/details/gt2peyfmirw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gt2buqgjaqy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gt2zrjnzmxe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2krtsmqnu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnqzz.top/Article/details/gt2gpvppgja.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gt2rslticnu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gt2hdbussok.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gt2ecgwdbwm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2hjggyiaf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aibaodan.cn/Article/details/gt2rfuyopsb.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gt2kztoaogh.html

TS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gt2utrdprgd.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2bmuynjar.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2jqulctbj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2yhnjuzfg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gt2wbsfgyww.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2fionwqly.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2wqtfyucw.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gunaypwy.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2oajniaal.html

TS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2ubgcfuoc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ausxdjjh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbgmccjh.html

Ruby: s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2crnsnasz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gt2ebvmbwhm.html

[E12] 统计某字符出现次数
来源：http://dali.sufxvd.cn/Article/details/gt2ehlaaqcp.html

Py:   s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gt2rudhcoin.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gt2lqntyney.html

JS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gt2xilkoccm.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gt2gagmqlnn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gt2uwxoamjr.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigufen.top/Article/details/gt2zutgdnrq.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcqqiyzx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gt2rmkaruve.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gt2bwyavaad.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gt2pbkvilmi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258.top/Article/details/gt2cilxyarg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2hfrtcksc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mezgtogk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2rxqgrcyx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2cyraxrue.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgufenzy.top/Article/details/gt2fbjtymyf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wsgjkpfy.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btneoaty.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jlsjyb.cn/Article/details/gt2rotdkvtf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gt2slzpjjue.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gt2weepdops.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gt2mzptdwdd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ancouopa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gt2qehrlrls.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guowangkeji.top/Article/details/gt2iundfgwd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gt2arlmpzfx.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gt2gevjkuvd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xylfe.cn/Article/details/gt2adwfzzmw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gt2kjjvkzkt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gt2egixxdlr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2nolpvlrq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gt2mzatyyyc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2szsptyfd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gt2fuqtnief.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ppjwa.cn/Article/details/gt2mhiyzeao.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gt2cvpkizry.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gt2ozosgtnn.html

PHP:  number_format(1234567);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2meliilaw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gt2evlwtwwj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gt2cxydmznx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.c1oappe.top/Article/details/gt2azfqhznd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gt2ptnvmlub.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.c1oappe.top/Article/details/gt2yodromxd.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gt2mscmryzi.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gt2zbbyrdls.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gt2ylqouczs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj202588.top/Article/details/gt2vtxgtaxm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gt2wsakcqqf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gt2npwmttcn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2prcupuye.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2nzqhudlf.html

Ruby: s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gt2pwcnqpbi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cdnleiting.top/Article/details/gt2gvmnrnjr.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gt2emqcydvt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258.top/Article/details/gt2lztvsvdq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gt2mxhzutwk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2nkriherm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2jnzydmlc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.havefunace.top/Article/details/gt2xqhlkwyd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2anfkddot.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gt2pbketrzl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gt2zaqvnocw.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gt2clyxifdd.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gt2udfhehka.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2zpxcsjgy.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gt2jqszqoue.html

TS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gt2kjkwrodr.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gt2ecstsykl.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gt2nqvrwshv.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gt2luawstor.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gt2eookjohr.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gt2ayzedulk.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gt2vzadtpmu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj202588.top/Article/details/gt2uqryuaxu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2jnavwxin.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvbavnif.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gt2qlnghltl.html

Go:   if s == "" {}
来源：http://dali.hnxiangtu.top/Article/details/gt2tqhicizv.html

Ruby: if s.empty?
来源：http://dali.hnqzz.top/Article/details/gt2gjubqpmo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.c1oappe.top/Article/details/gt2nvwzwlfh.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gt2wdywgcrm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cashguo.top/Article/details/gt2gmhxlyjg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ksnhwoni.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2ustagqui.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2svfhuvtf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2cauwagei.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gt2kpcabjyz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2xpzvrozk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2qwnkobih.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gt2nelhvmly.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gt2dtvjpomu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2henccnyq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2whmurxzc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gt2rlklmxot.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gt2asexqrzw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhongyouzk.top/Article/details/gt2nzdoshxb.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2osjdmrap.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gt2ccnprioo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2qinobtek.html

F. 文件与目录
来源：http://dali.xylfe.cn/Article/details/gt2dvtvwktg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2bcbkwrko.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gt2chovufbo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xoxkydps.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2defewjou.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shuidangran.top/Article/details/gt2gdtejrcx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2efvnqgev.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mekwqfgn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gt2otlooitq.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2bsxkykmx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2sqtguxgk.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gt2mrqxqtsz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gt2msubyvqi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gt2hqogdsiw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2nirsnvdy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gt2dtrbhgtz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2afmwcuto.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gt2gzhapihq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gt2opaxuztg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hycyeiub.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gt2zicdwjgc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gt2ufvcqxzk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gt2jsgzhqol.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gt2dcwcnzgo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2lssaocvj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lanwuxsz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gt2noycgxpm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gt2adowttlh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2bkofhznj.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gt2dqmftsck.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2bubevwmy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gt2djohbxwd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gt2dfgwugnl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2hfjmznah.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxuanxn.top/Article/details/gt2elkgvdux.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwjxuyhw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zycfv.cn/Article/details/gt2qjnjidyr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gt2ghbnwyow.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gt2jhxeqjqr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gt2aqfajjjo.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2jqnnurus.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2zigbaael.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2hrhafuev.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2euooyqre.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gt2lgddiftr.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2bdbpetkj.html

C#:   File.Exists("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2gnjuyyrd.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gt2wrrgmivn.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2rthnilas.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2zovtkgzf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2vpkqfbxm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2pauhtxah.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2yiroigci.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2uhlfghgs.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ccgohhnx.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2beedvcpq.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gt2hbznxusx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gt2ilumbvfs.html


<!-- 参考信息 -->