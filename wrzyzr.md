代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gt2pisqecdi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gt2snrjjckj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gt2alschbir.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gt2rdwxxkgd.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gt2fvfikquy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gt2zeiwzuoa.html

[H09] 带错误码的异常
来源：http://dali.tianlin.xyz/Article/details/gt2blbzzqua.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gt2swqfylzw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smapqaph.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jiagoushi.top/Article/details/gt2kpfsyukm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqrbozpa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.9152youxi.cn/Article/details/gt2dhyjhdyk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gt2lxequtkm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gt2gkipwyce.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigfzy.top/Article/details/gt2ziwwyehz.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gt2idtpicwc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gt2obybqxsd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfunmezx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gt2ufzjokel.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gt2yivhwaam.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gt2kmjfvulu.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gt2glpbqkjh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sxryk.cn/Article/details/gt2jsxnevdi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2gsvgstpc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2srliiveh.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gt2zqawsscw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wowlzdfx.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gt2ztppxgxj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gt2itkglhxp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2dwattmsz.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gt2iamgpyic.html

TS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gt2kwzypsbq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gt2eepshwbd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gt2ybvumrof.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gt2rfxfiwkx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mshchdcm.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gt2kwuuzjmk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gt2raiaxxrd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gt2stantaxq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gt2wqewvhjm.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gt2kcgyjhgf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gt2jwfzvget.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gt2kwuapxii.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2ttwzqoac.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gt2ewmevzrc.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gt2nwcerixz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gt2kjfbrkhc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvjoeckk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2otswdczp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gt2hpbevfca.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbkllxzv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aizwys.cn/Article/details/gt2hhqmfgdn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2axhsbdsy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gt2lqglbcwk.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gt2emkastws.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guowangkeji.top/Article/details/gt2gkeyqchc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gt2jiueuhuv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gt2pxozxhvs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvgzdzrt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gt2rdwsdkox.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gt2ehnktutu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gt2kibcjokb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pycfn.com/Article/details/gt2tpwzkcnm.html

[I05] 按正则拆分
来源：http://dali.yj20258888.top/Article/details/gt2soyzursu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gt2mevzewjj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gt2pgrgacec.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2msufeuvw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2uwdpyema.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhengqikj.top/Article/details/gt2ogycgwkv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2tsxwrgox.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gt2puqxilrl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.bjfxy.top/Article/details/gt2zbkjqvia.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhongyouzk.top/Article/details/gt2sttzbxdm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2sxcrlbpw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gt2yfyepsuk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gt2klzrysdo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gt2lsihjfvw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2uzipwgul.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmwpivnj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.snrcjt.cn/Article/details/gt2ezkdzhpm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2xpmqwslk.html

[I07] 忽略大小写与多行模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftyhqwkj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gt2hnyvosda.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gt2xsmozihp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2slwftxtx.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gt2kenbaiod.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.snrcjt.cn/Article/details/gt2fgdygmjg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjnelvya.html

Ruby: s.scan(/error/i)
来源：http://dali.hysaishi.cn/Article/details/gt2skqgeora.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gt2qzhbqwgi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gt2hjryujjs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gt2ponkisre.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gt2yqhlxand.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2lxfjrefe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gt2ymtwxqbs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dzekrsri.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuxming.cn/Article/details/gt2ugvprsdl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gt2pvpbaucx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gt2jkpujxqp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2madwmrrf.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gt2trtrtolc.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2imeikiai.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gt2hkorrzvc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gt2jqmfwhct.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gt2ouyclrok.html

JS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2agrcgzzo.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gt2iysudfut.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gt2qlgxkvpp.html

Go:   time.Now()
来源：http://dali.xylfe.cn/Article/details/gt2xbwnuhfi.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gt2cslpcodc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gt2fxeflxun.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gt2qckuldji.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gt2fkmufdsl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gt2lhcetvpi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gt2bxqbgchx.html

TS:   d.toISOString()
来源：http://dali.bjfxy.top/Article/details/gt2oqnvzfye.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sufxvd.cn/Article/details/gt2eblyoyaq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gt2xbjfmqpt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2uxmpcqji.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.316326.xyz/Article/details/gt2lootpale.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gt2cvjqtevt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gt2xzljbwwo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gt2sibesukj.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2hurpzewz.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2afeqkvyo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2slqspina.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2vfrccrhb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2chzozbfn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gt2iggnwzzp.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjqwoxgw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2vzsqklmd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypehkjlb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnqzz.top/Article/details/gt2xgvegknr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypuuolfc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2aysipwza.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2yqkaiupg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gt2xnvrysst.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nycvsbxx.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gt2ebgreunp.html

Py:   now + timedelta(days=7)
来源：http://dali.havefunace.top/Article/details/gt2phxmccxx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnxiangtu.top/Article/details/gt2xpwodcxq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2zbknbuty.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gt2zdfjdgcb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mqshauki.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdfkcrez.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gt2zwftmawn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gt2bdozkjqd.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gt2yssmbidq.html

Py:   (end - start).total_seconds()
来源：http://dali.chenzaomai.com/Article/details/gt2mymmkknk.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gt2qpaxhnmw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gt2uecyuwnm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gt2rfdkkztt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gt2utjpqjwz.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gt2dbhmhfwo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gt2ckejinwh.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gt2pbrflver.html

[J07] 比较两个日期
来源：http://dali.yuanzhike.top/Article/details/gt2djikbxkb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2gviagubu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gt2txsgofkk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gt2wretlgux.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtpaycgy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigfzy.top/Article/details/gt2hjqqhniv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2ioygkopn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfvddocn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2pluvxhbc.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gt2zuxegzlv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gt2uakdekgp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gt2inrfofqn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gt2gbkzbhqq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gt2mwvtiyup.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjbecqis.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gt2bqlsxyfj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aflgttfx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cdnleiting.top/Article/details/gt2stlsgwiw.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gt2bqwinmbg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gt2vhcdpmhk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gt2zccheeuh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gt2iiadvjxb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gt2ljzsyxlw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shuidangran.top/Article/details/gt2taxmkjxw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zycfv.cn/Article/details/gt2ocearglv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gt2pkqneivp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gt2hjeoldwp.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gt2fpaplblj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hysaishi.cn/Article/details/gt2ndoqugdl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gt2jgxbwrgw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2ihpdoxts.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjtrjciv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gt2saotndqj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gt2kvdixijl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gt2mewkrjtr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuxming.cn/Article/details/gt2belrutee.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2zdgxawlc.html

K. JSON 与序列化
来源：http://dali.yj20258888.top/Article/details/gt2uzdjkglu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2gmbaxmlq.html

[K01] 对象转 JSON 字符串
来源：http://dali.cdnleiting.top/Article/details/gt2xpgwetqp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gt2skwtjhco.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gt2bnxcaytf.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2tlodffwz.html

TS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhqcungl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tewsrenb.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gt2fgnaytjh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gt2ebagwmgp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2munnneae.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gt2ceimcphx.html

Py:   json.loads(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2aselfykz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258888.top/Article/details/gt2zvwbthfh.html

JS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2dkkibsoz.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2ydpnbzpe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2vstesbfe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gt2iqhlweoe.html

Ruby: JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2amcckcqu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gt2qgafikwt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skfffxfb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gt2octofefp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2zmgmmlhc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2mysisczx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2kvlmpjoj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.bjfxy.top/Article/details/gt2lcarelvw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gt2vksrdqss.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2zdnnqisl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpjqfzwq.html

[K04] 读取 JSON 文件
来源：http://dali.9152youxi.cn/Article/details/gt2gkyfntrd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gt2kmniptps.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gt2klqufvfe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2clodkmue.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gt2vnewcjeo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2uxzcxebl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gt2treqplse.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gt2rruzzamy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.c1oappe.top/Article/details/gt2dtdztdpx.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqrajynf.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfvljdte.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hammf.cn/Article/details/gt2erwkmgek.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2ypyeoqsk.html

TS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2cquipuam.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gt2uykzwxqo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gt2oqosinxx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gt2yipimdev.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gt2kasfscae.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gt2yjvbmlpm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2aylhvtko.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tamiuvkf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gt2srufjqfz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gt2bjvllcno.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gzhubu.top/Article/details/gt2jzbcznhu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2rqmmxddg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2tyakjldm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2xysbquxh.html

[K07] 进制转换
来源：http://dali.ppjwa.cn/Article/details/gt2dgnoqusa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2exbzryxp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.meibo888.top/Article/details/gt2kcjedgcx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2jridgroj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2yynwzkqn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2rolzzfld.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gt2gyxrmgcg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nryakmyg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2aqjmgbxw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vrgqumul.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2tsrbouxn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gyeamezl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gt2izbvmkto.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2gqwwglla.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gt2fzpwlpcp.html

Go:   encoding/gob
来源：http://dali.xylfe.cn/Article/details/gt2oczbgsiv.html

Ruby: Marshal.dump(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2afghrluk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gt2gnxddexw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2entmaogf.html

L. 网络请求
来源：http://dali.yj20258888.top/Article/details/gt2oyxjxqyr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ivzddfmk.html

[L01] 发送 GET 请求
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqyigwte.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xziqi.cn/Article/details/gt2nlsjzcfu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.haohaochexian.top/Article/details/gt2lvwrpidz.html

JS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2mlbdexjq.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gt2hehyzihj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gt2vguqqmin.html

Go:   resp, err := http.Get(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xnlocbij.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gotoacloud.top/Article/details/gt2btjfxgdk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gt2nuclfkxj.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gt2afqrievv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sysykeji.top/Article/details/gt2vwscxxdn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenlongwang.top/Article/details/gt2dewkdmnn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gt2aamtvrbh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gt2sfazpukz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gt2myykfiej.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gt2aggltsxy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hammf.cn/Article/details/gt2zgvnmmqh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2ynjqrrbi.html

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gt2ggxilrce.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qklhapzs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gt2ofqlziti.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gt2nmnsjunm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gt2aymfiukp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.iojbl.cn/Article/details/gt2sfgdegur.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gt2kqvrevdk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gt2iqdnxsit.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gt2pqlbeejy.html

[L04] 设置超时
来源：http://dali.gzhubu.top/Article/details/gt2muwkgpin.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gaohongyu789.top/Article/details/gt2dlxmafzj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.birdmap.top/Article/details/gt2iisedtmj.html


<!-- 参考信息 -->