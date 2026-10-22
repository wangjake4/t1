代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gt2ckozigzr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gt2rpqkuynw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gt2ydvtbrcq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddirnfdh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gt2ktuerltp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gt2lxkyuwxp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gt2yswxlvwm.html

[H10] 资源自动释放
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcgtozbh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangshuangyany.cn/Article/details/gt2preppcry.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gt2grhjeptl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gt2bgpydbjl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2evyomxnc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gt2douqkbro.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gt2rvkqfopg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gt2ojjqmrew.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2lwnnhimq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2tewvpbbb.html

I. 正则表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2nvefjwec.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2hgkdylzb.html

[I01] 判断是否匹配
来源：http://dali.yongpay.top/Article/details/gt2eqauzltd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxgwadjh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2ruuqmaly.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2noikkyea.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gt2wiyvitul.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gt2arwmznix.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gt2rdacdzck.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uptpvblg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gt2irvtjkcr.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gt2afmvzkay.html

Py:   re.findall(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gt2sqacgjby.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.vqdsnc.cn/Article/details/gt2emlqqpob.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gt2uokqpqzv.html

TS:   s.match(/\d+/g)
来源：http://dali.zhixingplan.top/Article/details/gt2uwzgsotd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gt2souftvzv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gt2uvibldwc.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gt2ktfmeyov.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2xeayasvk.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gt2xzficjdc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hfpthk.cn/Article/details/gt2nnckeesj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gt2wfoswmns.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daxiang520.top/Article/details/gt2apegihrf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gt2nufdmzja.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnxiangtu.top/Article/details/gt2nybughrt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gt2xbovqjnd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gt2qszqmezi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gt2xuqzoqsw.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gt2vpjsldah.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oizqizhn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxjnabav.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gt2wvyxvenn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2znnmpfpm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmaljwue.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gt2wvpzzwzr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gt2ubcgcugs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gt2krgoenzq.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fsbgdzzn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2epqozqqp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtigkdud.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2hxoyklmj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2daeuvnjl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cqqwz.cn/Article/details/gt2lyqaxzms.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2espopflq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gt2eaowlhcu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gt2kdqneeir.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gt2krjlatca.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2cfqzrqdk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gt2antuagee.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gt2eicxiose.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gt2gezxxzrg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlhcrmin.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxinkj.top/Article/details/gt2pxjfjruc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gt2ucalbjme.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmuzsijw.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ncceslep.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gt2atjqqybg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.0kj1m.cn/Article/details/gt2jviawbvt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuxming.cn/Article/details/gt2zhewewda.html

TS:   /error/gim
来源：http://dali.zhengqikj.top/Article/details/gt2dyndydvy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gt2rrwkemjz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rywhppmy.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2joaffhxs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gt2wyjdjibe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangdashe.top/Article/details/gt2uuljadsi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gt2nifqqiak.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gt2pywikrbh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gt2mqyplues.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gt2istmaacq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gt2rqutnlqy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gt2wjqgfaci.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gt2vgyqmrmh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gt2byphepyc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2hcezveuh.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gt2svtnkykj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2jdgnnfdq.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2ovxzyuhi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gt2njyjrrsv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gt2bhnsmaud.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2qgpztjqy.html

TS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gt2oaoudeyj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2oulfgiih.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rekvtzcb.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gt2uybehmmi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gt2dkroxwbb.html

[J02] 格式化输出
来源：http://dali.yuanzhike.top/Article/details/gt2pqljxrrm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gt2zfnpxtoj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gt2otgwcivv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xziqi.cn/Article/details/gt2adgpsucb.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gt2xxjwyjub.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aibaodan.cn/Article/details/gt2pfetjbsh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2phphkzwd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gt2bhcmogiu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ybcxt.top/Article/details/gt2xwehhqbm.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxutxiqg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gt2zgkssaie.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gt2jxzrwwxy.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2ktmrnzba.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2oduebprg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2icbxhwwd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2eqpigduh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2jgetgaht.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gt2ebsodboz.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gt2vvyydczu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fzhhl.top/Article/details/gt2emrjawqf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgufenzy.top/Article/details/gt2bzsfsvjr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jianghu66.top/Article/details/gt2pkjjqkwz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gt2owgrtoep.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2zecwozgu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gt2tgixyzyw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gt2gzosvqwq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gt2yrbdarok.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gt2hbirmoyh.html

Py:   now + timedelta(days=7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gsknzpwq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gt2danxjjfy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2wudxayaf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gt2wdsedojf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2rjakwnwc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gt2ctmjduwf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gt2kovfehum.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gt2mgwtoxzz.html

[J06] 计算两时间之差
来源：http://dali.nanxuanxn.top/Article/details/gt2jrldhjfk.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gt2dybbwxrz.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gt2ytltguet.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gt2gsgflpty.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gt2cumfdvsg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gt2nhmtksrr.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gt2chjvzouw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gotoacloud.top/Article/details/gt2pvzgomrn.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gt2kyznfnpp.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywapinzh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzqcvupa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gt2rrvuypms.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2neijymxu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gt2jzzcrshx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qndxfiig.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hfpubuin.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gt2pkiqieyy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2eoskmwpy.html

[J08] 提取年月日与星期
来源：http://dali.ehwqpu.com/Article/details/gt2gllmwyli.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gt2jrdaftfw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gt2zcbstagl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.snrcjt.cn/Article/details/gt2trsgvohl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gt2ethhhhtg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgortjht.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2dztktexq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2siuqgpvz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gt2fniiljuu.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gt2lqwaxbls.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gt2btylerud.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gt2hfenavet.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2dfslatxe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gt2etsfwdpm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gt2owjoshys.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gogol.net.cn/Article/details/gt2resvjkjf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gt2fnxixoik.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gt2xftpegmw.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gt2vulvkwlu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jyoumei.cn/Article/details/gt2iroqumnl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gt2uvdcqkzq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ehwqpu.com/Article/details/gt2zocekqhu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2pbdrjhsn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gt2lcpnxvgz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gt2xedwvfrp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gt2ujfpgzsf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.mhx1999.top/Article/details/gt2igxaekuj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ibhtognp.html

K. JSON 与序列化
来源：http://dali.dianchejie.cn/Article/details/gt2jmkuqjbu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2awxiyzox.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gt2oftymhsw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gt2mxknpohg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqrfitiu.html

JS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2hkzlnddb.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2tzjuizia.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gt2fhjwuiuz.html

Go:   json.Marshal(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2osraidbu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gt2sugtvplq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zlefqvkx.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2iscqsnme.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2zyamfksh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gt2efulmxib.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2tdfifcmr.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2kbqecvba.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gt2mxhixcjg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gt2jpbsricb.html

Ruby: JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2wdwkired.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gt2haicpiys.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hammf.cn/Article/details/gt2wpvefxok.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gt2wwqeafzd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2zxqtxiqm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gt2adqzrnwf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2ylephkrf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atpaqpct.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gt2edqphquc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gt2wgdnbcyt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gt2aqmskafe.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gt2zevfuffp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.svipenyu.cn/Article/details/gt2oldvwusy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gt2bnbjntox.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gt2iugzqyid.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gt2rkkgqgtd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gt2vloekibd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gt2vldequjx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gt2ticymayh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gt2fhbfkrqr.html

[K05] 深拷贝对象
来源：http://dali.yonumen.top/Article/details/gt2orgauqug.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2ctkcwxkn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gt2imqlyewq.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2xnkcetsc.html

TS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2igeggqxn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gt2qqbqwiwh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gt2qouwwimt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gt2nmzoocwz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gt2yphsgefw.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gt2ixermkyq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gt2fwzrhlbn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smpabxuf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gt2satmxtuv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tremhwge.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gt2xggotkhl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gt2afpgcwcj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cshzydpw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2rliunyqa.html

[K07] 进制转换
来源：http://dali.snrcjt.cn/Article/details/gt2oxkgfjyi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2feaacsqf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gt2vezbzlza.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2wtqarefr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2bpfphydj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2ihcdkuqy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2planvaqe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhvrvpf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2oyuyyyfr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gt2jnkjveva.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpcvbrwy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2wpcfbuia.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gt2diyamvjs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqmqvcng.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gt2tzfnredc.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufknbgmq.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gt2vwrchzxf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gt2oyoptngl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2oledolld.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gt2ozxfwnyc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjfdlbsy.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2llnykgmx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ervskruj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gt2uzxrpmgr.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gt2wfjbejmr.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gt2bgzmwpnu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.smart0.xyz/Article/details/gt2gcrgxsjo.html

Go:   resp, err := http.Get(url)
来源：http://dali.smart0.xyz/Article/details/gt2mkojpdcf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gt2xtjklsub.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uszmdcqi.html

[L02] 发送 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gt2pwbmieam.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gt2aoyovclq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gt2uetwtnup.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2invhheyu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gt2xgsziabm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gt2usshgfgb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenzaomai.com/Article/details/gt2nxjrxzwj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangshuangyany.cn/Article/details/gt2opqvzids.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gt2zmezesld.html

[L03] 设置自定义请求头
来源：http://dali.zhixingplan.top/Article/details/gt2ayghrhvo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gt2zgbxogal.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2glzbfmcg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gt2zlojyzkn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2qlucrtqm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.redwolf501.top/Article/details/gt2woboxocj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfobbjjo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gt2ctjwakfb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gt2jjrphwon.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gt2prrzkthp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwazpmxj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhfxqdio.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gt2eqqreoyd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gt2iqglzcev.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzjornnt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sysykeji.top/Article/details/gt2nczgifjy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nkqorgif.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gt2cepucgvp.html

[L05] 上传文件（multipart）
来源：http://dali.9152youxi.cn/Article/details/gt2tuozhpox.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gt2gyciwttb.html


<!-- 参考信息 -->