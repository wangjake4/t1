代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2bczgljnb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gt2qaztehbe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gt2jkeqgnrz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gt2rgqfssko.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2atyvkjhi.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gt2valyoqqp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gt2rhmxexzb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gt2boebeqxa.html

JS:   e.message;  e.stack
来源：http://dali.yuxming.cn/Article/details/gt2ccqpuurn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gt2ztlsqore.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gt2xfxqvzml.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gt2jgqjpufz.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuanzx.com/Article/details/gt2ppwhfnyw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.0kj1m.cn/Article/details/gt2bdojluze.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gt2qjsowrcl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gt2nfsedwfb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gt2yemdmkfk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gt2aqbnehzn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pydnhoul.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gt2gbzeeesk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigufen.top/Article/details/gt2hwpasktc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gt2pnyhvfnk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gt2jnufrmfz.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gt2crqlrrgl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gt2gxovjrik.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gt2ydgqepuc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzzswmsv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gt2vbbjkxdq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gt2blnpqafj.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gt2zbagsjef.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gt2nrjoadiy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2lzasqhux.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2lubthimp.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gt2igwjqmha.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2nwldeqao.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gt2jzuimhco.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gt2bkjattoj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gt2gikrtdrg.html

JS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mtkuhlsv.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2fvnzuobi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daxiang520.top/Article/details/gt2vxqrykaw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jianghu66.top/Article/details/gt2wvmfiwhz.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gt2ndxtrrfb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gt2yswzapad.html

[I02] 提取所有匹配
来源：http://dali.meibo888.top/Article/details/gt2szvvaebv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gt2gnqwtihf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gt2dxsdzuqr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gt2uxcvpjlq.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gt2ryjpceng.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gt2wdgonwup.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gt2vrnexjge.html

Ruby: s.scan(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gt2evmmrfbn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gt2hwbkohgb.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gt2nmcgzqze.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gt2iysdpiqw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gt2slrxqdei.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhixingplan.top/Article/details/gt2aaqncfhb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gt2emifdfzf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnxiangtu.top/Article/details/gt2tvafxnfw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gt2ehzpvfxq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2voqaztub.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gt2dfticazn.html

[I04] 正则替换
来源：http://dali.kuanghao11.cn/Article/details/gt2ljhjamcj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gt2wwouckek.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gt2bphlajvy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2sihjuusf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2okzyvdqw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gt2fjehhrkd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmfdwvny.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gt2tfbonlwj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gt2uwmffrtr.html

[I05] 按正则拆分
来源：http://dali.daxiang520.top/Article/details/gt2juwaddea.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.9152youxi.cn/Article/details/gt2zyrwumws.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2rmrlzvkf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2cqbtittp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2hjhncysr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gt2luvymshr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gt2ejxyfdpa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2rrxcwthk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gt2bkbzhmsb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gt2vbrhrpix.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2snjydhcy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ciovngnc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gt2dibvugrq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gt2urghuhpo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2vjtyifse.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.meibo888.top/Article/details/gt2pphqmlgn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gt2kexzrglh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2zwwznkny.html

[I07] 忽略大小写与多行模式
来源：http://dali.gotoacloud.top/Article/details/gt2todcmcmv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.havefunace.top/Article/details/gt2mkjofncr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sweek.top/Article/details/gt2xprfbaop.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gt2ntoieppr.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gt2lqzlwxlk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgfzy.top/Article/details/gt2eaocftio.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gt2ievysmrb.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gt2epdoluxp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gt2syckbyzo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gt2vntsyqlu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gt2szbzmpai.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tanke756.top/Article/details/gt2uynrsiel.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gt2ygigoacs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gt2iteecgeu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gt2rhiwmqgr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gaohongyu789.top/Article/details/gt2doslocjq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gt2jaoimlsc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2dbcrwndc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2psxqqxkp.html

J. 日期与时间
来源：http://dali.snrcjt.cn/Article/details/gt2qzpkszhw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2vjhxzoay.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gt2pztuvyzt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnqzz.top/Article/details/gt2luqlojfh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gt2pskfchbv.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gt2vfmwiamz.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gt2kxvadipg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckxwrgcu.html

Go:   time.Now()
来源：http://dali.yonumen.top/Article/details/gt2cexarohy.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gt2kbtqjaam.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gt2lravipei.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gt2nrwfllbr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gt2ehabbyah.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gt2wjstsdho.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gt2sqbljgoj.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gt2izpyxhql.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gt2wqwlsfud.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gt2xkbdokzq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gt2rtnpzjyz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gt2okontsab.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gt2jcvvtspq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gt2lptmxmvx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cucudq.cn/Article/details/gt2llijwaqu.html

JS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2vtblhixh.html

TS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2knarlmug.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2ynmwawmi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2duvvqkra.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2gqwotlmn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gt2vwovofot.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gt2ktxcfksu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thetmowj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gt2pvfysrvl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tanke756.top/Article/details/gt2jvucqitx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yvedp.cn/Article/details/gt2rqtcuyob.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2utwohizg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2plrotlkd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2qztrgdqy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2vyvjmrqj.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gt2nsmxuhcx.html

Py:   now + timedelta(days=7)
来源：http://dali.cdnleiting.top/Article/details/gt2fxslysog.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gt2daeenlfj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gt2xleqhcuj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2mebbqljy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gt2yyehgoma.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gt2rmyxydqo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.mhx1999.top/Article/details/gt2rfejxjuu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2bqufosib.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gt2nfbxyjxu.html

Py:   (end - start).total_seconds()
来源：http://dali.vqdsnc.cn/Article/details/gt2ecutafyj.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gt2rnckxmit.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gt2ufqogxay.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shuidangran.top/Article/details/gt2viicbuhq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gt2jdytoeao.html

Go:   end.Sub(start).Hours()
来源：http://dali.cheryme.top/Article/details/gt2lcwzdegt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gt2npqxjdsn.html

C#:   (end - start).TotalSeconds
来源：http://dali.cqqwz.cn/Article/details/gt2dwjmwlbq.html

[J07] 比较两个日期
来源：http://dali.yongpay.top/Article/details/gt2tunjllkk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2wqlhacqu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rsgmxvwo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gt2noiqlhmd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gt2lrpfbmvb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gt2tebhzaow.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gt2hyvpopfu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qlhfypjb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2byhfwjfp.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gt2ptpzyydv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gt2qmtqcyuc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gt2tmanvnns.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gt2nmjpgvkb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gt2ieqpeuux.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gt2ryepmxwv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gt2htmiiwwc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shuidangran.top/Article/details/gt2wogwsfab.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gt2ewmimuml.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gt2yitaylbr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhoulong.xyz/Article/details/gt2xrymwfem.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gt2tebnephu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gt2udbjnynq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gt2usqtlvec.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gt2zuerhgbf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gt2reseubrv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xopylkff.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgfzy.top/Article/details/gt2untidkcy.html

[J10] 取今天 / 本月第一天
来源：http://dali.ydzc1.top/Article/details/gt2mhdouowo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gt2lakdrtby.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gt2hscqfzec.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gt2styxofcj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2dfzdsxwg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.c1oappe.top/Article/details/gt2ngnmvcra.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcaxzhcz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gt2ycggbqly.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gt2vncqvpwk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdqwowqz.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gt2nivoabem.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2xtodudta.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gt2acdarmuc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lsnjmshq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gt2ocadotfb.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frnvclqj.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2osculkcl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gt2egqhgfus.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2dvtjuvcb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gt2hnvyiste.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2zbgixgjm.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2xysrkpqe.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gt2hkafesgl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuanzx.com/Article/details/gt2usaudkcp.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2ayrmyjqt.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2ptzpwblp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2feuaiuhm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gt2bwuebxrp.html

Ruby: JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2yyeklrlp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gt2wiopdkrm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gt2ylfghukn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gt2hiwspvgv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gt2ambwveir.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2skrxacai.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzczwhxt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytqhldyf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gt2uysxmxxu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gt2epmoyxra.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigufen.top/Article/details/gt2liljfhcx.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gt2nidmajzh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gt2qbyrecyv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gt2abszjinc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gt2bmgjwsmk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2gwpznqqi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cheryme.top/Article/details/gt2jsizrbaj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2hcctwztu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2cqmgvsmw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gt2dxvdctnn.html

[K05] 深拷贝对象
来源：http://dali.cheryme.top/Article/details/gt2zqeycrok.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gt2enanlvgo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgfzy.top/Article/details/gt2eaznrbxz.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2bdfwjtcx.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gt2meyeldxb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gaohongyu789.top/Article/details/gt2ectctdei.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gt2jugnsitb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jyoumei.cn/Article/details/gt2xohrcgzv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gt2cvrwleuh.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigufen.top/Article/details/gt2kenmrrrg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gt2dblgycem.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gt2ckciyumj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekhamsix.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gt2wjlgzieu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gt2peistqvg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2actslvmy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2gtunctzr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2yntupabj.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gt2haatuxvb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2hfuneump.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gt2xqvwdggg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2tgjmvxvw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2puzshatq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2zmnrwmty.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gt2lsfsnfzc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj202588.top/Article/details/gt2lmrfewdk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2prboivdl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gt2zlgdrgbg.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gt2twoqcnhd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dianchejie.cn/Article/details/gt2ogeregfe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gt2oilcohtj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gt2wilysoxr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gt2wotiopyb.html

Go:   encoding/gob
来源：http://dali.andypj.xyz/Article/details/gt2ryyzaqrw.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdqgszj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gt2ukuhcxlc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2sezotfof.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gt2khuwyfhr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ssqfouao.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gt2ajxyvkro.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gt2ezdiglbm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yvedp.cn/Article/details/gt2oqomozdo.html

JS:   await fetch(url)
来源：http://dali.hnqzz.top/Article/details/gt2papsfvfq.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qyjxsjdq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2vedcdcqx.html

Go:   resp, err := http.Get(url)
来源：http://dali.havefunace.top/Article/details/gt2btditlct.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gt2istfnbbg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guowangkeji.top/Article/details/gt2civcrbtk.html

[L02] 发送 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gt2ifcbuyff.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jianghu66.top/Article/details/gt2bjuarwhu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangdashe.top/Article/details/gt2qdveqxbi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gt2hsiwbhql.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gt2crumtvtt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gt2uvqnyfxs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gt2lbwyquwu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gt2pwbowcpe.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gt2xeciwljy.html

[L03] 设置自定义请求头
来源：http://dali.yuanzhike.top/Article/details/gt2tnllfyvv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gt2hxsnzqtb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gt2jmvazbuf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gt2kwkblqaf.html


<!-- 参考信息 -->