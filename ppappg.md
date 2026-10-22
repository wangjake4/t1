代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnwabbrj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gt2rxliyvic.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gt2qzreryzs.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gt2kpswezkt.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gt2ddizglxw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gt2wrsgecsb.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gt2nnjimman.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gt2vznsbkwu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gt2wdhshsxp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gt2geynwnhr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gt2rbdapaqy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gt2xklpdmin.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nwbrower.top/Article/details/gt2epnzbzbb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gt2ejcuzlbj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgufenzy.top/Article/details/gt2gudhdcuc.html

[H10] 资源自动释放
来源：http://dali.yuanzhike.top/Article/details/gt2djeialij.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dianchejie.cn/Article/details/gt2hqjlraza.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenlongwang.top/Article/details/gt2acimdtso.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gt2diyqrbsu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gt2yugdiixl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gt2fdywgfal.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gt2vcxwnymg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gt2cpawxnzd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2whptuewa.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nlyunhzx.html

I. 正则表达式
来源：http://dali.yvedp.cn/Article/details/gt2fhvdrgoo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2tnysaxmz.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwlkfcnu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gt2eucgfuuz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2dylxyxtk.html

JS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gt2pjxjzekj.html

TS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idynagpp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bzclqycr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gt2xcyygosj.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gt2zceeoqhe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gt2rimnjttg.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlmhuorx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gt2ifrbkxjk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gt2amsobzdx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ppjwa.cn/Article/details/gt2zmebmfig.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gt2zgnblqni.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2zdsbmete.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gt2gjzwqzyl.html

Ruby: s.scan(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gt2ryaztkff.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtvbhlrx.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gt2zfejapzk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gt2gzixejby.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2byacsxyq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gt2yywboclr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2doqeeiaj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gt2lfewutzd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigfzy.top/Article/details/gt2rojfgymu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjxynont.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gt2yjwmmzqo.html

[I04] 正则替换
来源：http://dali.zhengqikj.top/Article/details/gt2jcrxwcuz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gt2zeboimqz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gt2ntppyfof.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2sdsrtyau.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2ordiufvw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gt2obwljhkd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jianghu66.top/Article/details/gt2nklpigyu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2bigajwio.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gt2nhfrhzko.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gt2swzixcjb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gt2udeclsrv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sweek.top/Article/details/gt2zgaymzij.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2sbapnpnz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2uxiccwwd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zycfv.cn/Article/details/gt2lrkexrvr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdkjhuws.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2knizejnx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2jtacmjga.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgfzy.top/Article/details/gt2ocvucdaj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2ufvrxdbf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gt2fodugvvb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yojezwjy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gt2arobcdhg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2qqukhptc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jadrjjfa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zdqjudy.top/Article/details/gt2idbijgtn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gt2acfvkhau.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gt2ejfxwdkb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gt2trxobhyu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2gcrijxhe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gt2owhuozhq.html

TS:   /error/gim
来源：http://dali.nanxinkj.top/Article/details/gt2qkcppgxx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gt2gswfhbcc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gt2uwtcihjw.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gt2bduqxuxj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gzhubu.top/Article/details/gt2phcpqkpp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2dlfswhkf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gt2kpjvuvxh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gt2fqzvbyjj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gt2yfwameas.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxdaqlbx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gt2vpdkddgx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gt2dowtzttu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxmrmqbt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2vkrxzvrg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2gzucshit.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gt2mvqxzxah.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ouvoyhbe.html

[J01] 获取当前时间
来源：http://dali.yuanzhike.top/Article/details/gt2sedcctaz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gt2hwqgtsrd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gt2fnkatrte.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpqumrx.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gt2cyefdgld.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yueranfly.top/Article/details/gt2fhlcjxgz.html

Go:   time.Now()
来源：http://dali.yangfankeji.com/Article/details/gt2hvssvmqw.html

Ruby: Time.now
来源：http://dali.yongpay.top/Article/details/gt2sugzfrgt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjjwmrsc.html

[J02] 格式化输出
来源：http://dali.sysykeji.top/Article/details/gt2nduetmco.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gt2hpocumpo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gt2uctmhqah.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xinyue.icu/Article/details/gt2eactpucj.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gt2kiphbcda.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gt2dcqvcuqw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gt2tncrlabs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gt2eobvkuko.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gt2ooishxzt.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gt2sdtivmdj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsvzoasa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yueranfly.top/Article/details/gt2jqwgeghl.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2votriijv.html

TS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2bbkgwkys.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2fsuemqjk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2xrpwpxmt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2fytejqjz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2myrwwdno.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigfzy.top/Article/details/gt2dzdvzifu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gt2uaedzoeo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenjidiqi.icu/Article/details/gt2lsoyikzs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gt2wttdkxvk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnqzz.top/Article/details/gt2cjuojflq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2jeymabjn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pyvxmtqp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2kcnstzfi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptxcoept.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2mchovxhg.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gt2yaglvkrf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.haohaochexian.top/Article/details/gt2wuvvtshq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gt2foqnoyib.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqwpnqyf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gt2gykeyhfc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gt2shmkxxqd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yueranfly.top/Article/details/gt2qwwmxgyu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gt2bggxqkju.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gt2fwoyeulp.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gt2vnomymhm.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gt2jjokreui.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigfzy.top/Article/details/gt2womrnxpt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gt2ywdxisog.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2wugcyhly.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuxming.cn/Article/details/gt2loikmlqr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gt2mowjnqbs.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gt2lknczacp.html

[J07] 比较两个日期
来源：http://dali.cdnleiting.top/Article/details/gt2hboyqpdc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2nwymbsva.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gt2wuebcfdm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gt2vhoornzu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2rdaaetdg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gt2orujsajh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gt2mmikcjvf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2oxeyplhe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2ecqavwzs.html

[J08] 提取年月日与星期
来源：http://dali.yangfankeji.com/Article/details/gt2gszjurvy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2equwboss.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gt2egdusnio.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfrwenmn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkhnucho.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gt2pzjwhyeg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gt2jthinumk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gt2fryutlmi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gt2ivvlgbyj.html

[J09] 时区处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkmddmif.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yueranfly.top/Article/details/gt2vffzdrgs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gt2nyciaalx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gt2wvqavxyf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gt2zstwejbe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gt2refutawj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2isszkoab.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gt2zsxiipqv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gt2qyboicpl.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gt2ivzybabo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gt2qkpahosi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gt2mrqmnktx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2vkrwaxhq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2tcoknwbo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gt2wfsszeen.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gt2naxpbbok.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gt2sbzoqxdr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gt2tckqkvzw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2utbgwnsj.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gt2mgxvhnav.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2uzrcajsn.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2ysrispyf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gt2qjyubnmb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofgelzei.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrrobqfr.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gt2gwqepwbm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gt2wvhqjaco.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2hoymxaxr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfowzspo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gt2kdblymni.html

[K02] JSON 字符串转对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2lolqughk.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gt2obhizvrr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xylfe.cn/Article/details/gt2qbpjhohk.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eluipegg.html

TS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2pyftckuz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tggchlni.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gt2wggblbfo.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2nzdrpxev.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2gwqxovkd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gt2iedetrew.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gt2xiuazzyy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwcvlakj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2kfxzxxhn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gt2pbwbrhcf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2qhmkrxbf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.andypj.xyz/Article/details/gt2camupyjx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2wgbzcill.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cucudq.cn/Article/details/gt2dqalwvao.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gt2oaumwogi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gt2hmtblwbx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gt2cdigmetr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gt2nfqhayxl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gt2fcpqtgsk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gt2huuqjnkl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gt2uxomxhdp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gt2pbgoisfn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gt2ievyqmoc.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2qikoybqf.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gt2dezozocl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gt2bavedofq.html

JS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gt2loohbnje.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2nnkbmwoo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gt2ttyxissq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gt2fxwkamxd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxinkj.top/Article/details/gt2qccnytns.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gt2jsycueyp.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gt2mcvubqhc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gt2mdaudfpq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvgmcbdk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gt2yeqjrodw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gt2prejeski.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.havefunace.top/Article/details/gt2kaqyydap.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2zltzrhfb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2hrccjwdv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gt2nepejttm.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gt2fdcyrxev.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2oqsbvazs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gt2wmjeeosr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kochinyg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2lmaiwoba.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2dtdchanf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gt2gmgarxcw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aibaodan.cn/Article/details/gt2wjhtwgui.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2gzlfuuog.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gt2lkzwreuf.html

Py:   pickle.dumps(obj)
来源：http://dali.daria6918.cn/Article/details/gt2mvtorvuz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gt2dgqogzcf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2urtjbrvh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2ffpjsqku.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gt2pkiwfzou.html

Go:   encoding/gob
来源：http://dali.meibo888.top/Article/details/gt2ezbsdwag.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2lsrfhvmr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.meibo888.top/Article/details/gt2qinmcmhh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2yahwdznl.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gt2rgbsxwnb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2qpoymemp.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gt2ptyqzdcz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258888.top/Article/details/gt2lrbfmcqg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gt2twqmutgj.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gt2rgnqudyw.html

TS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gt2osyzfpgq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gt2eenbtukx.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gt2eawomvkm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gt2knerlusb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2hqajfuhf.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gt2zcvxgnob.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gt2rbhylphp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fengsongda.top/Article/details/gt2xlyzxqzs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gt2zzmbffjh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2yhceqepn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gt2eqqrfhvr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gt2ecgewsja.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangdashe.top/Article/details/gt2oxskzxsp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gt2vxwdotaz.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmuwxksr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpirvbzw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gt2nmmuhdrb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gt2eieqoszu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gt2bcqpozse.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2sohjxcgo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2rnyqfsxf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yanxiufei.cn/Article/details/gt2rphdzvtd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urkywxxx.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gt2wieqvsnw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gt2rbfokkyo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gt2hbvtkiwm.html


<!-- 参考信息 -->