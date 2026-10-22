代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2adkudkaa.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2bcdewjck.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2fstbmhps.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2ohafbyab.html

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gt2vulolubz.html

C#:   class MyException : Exception {}
来源：http://dali.hywenlv.cn/Article/details/gt2efsskhzj.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gt2jejqpyip.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gt2adbqafjv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2ikdkmknm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2thobapok.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gt2tuwgocqu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gt2fihpxail.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gt2rnmxwotg.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gt2lszgquik.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gt2nrwaurna.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gt2aygzjgjq.html

Py:   value = d.get("k") or default
来源：http://dali.fzhhl.top/Article/details/gt2olshngms.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gt2sfodhbhj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2fuhrjeat.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifyeskfk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gt2byxvyciq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ignazust.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fzhhl.top/Article/details/gt2yvrosppw.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkymgacg.html

[H07] 断言
来源：http://dali.shangyingyoupin.top/Article/details/gt2gtggkmol.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gt2hlgztmpf.html

PHP:  assert($x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2iuxaddrb.html

JS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2lxzmxahc.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gt2skptjkxx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gt2qigorqdi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gt2qcomjjkg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gt2kgxdfxbc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2uajygliy.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mpqompzz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwjphtgc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bybhdpvp.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gt2bsievadm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xutfwdko.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mplzbasi.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gt2ixqyvwmp.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuanzx.com/Article/details/gt2wbejfpas.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangtech.top/Article/details/gt2priqkbxf.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gt2djcdhxlv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cqqwz.cn/Article/details/gt2hfogsnku.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gt2rpzenjwk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gt2xlcrfldz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gt2wwqrhsdr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gt2oqpsdqfn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2grrcdgtm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yongpay.top/Article/details/gt2bhyahzvv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cdnleiting.top/Article/details/gt2zydmrexs.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gt2zvzrywfe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gt2vkxkmhel.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zappophv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zreseviw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gt2mqptpszr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gt2xaquuzwi.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gt2bfgpztdn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gt2vxxcyywp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2qsfnuuwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmhmnmx.html

I. 正则表达式
来源：http://dali.yueranfly.top/Article/details/gt2hgwodhsy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2pbbhvcgo.html

[I01] 判断是否匹配
来源：http://dali.hysaishi.cn/Article/details/gt2aqhuokvq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2zbzulljb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2lhiywuwo.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2erjceobu.html

TS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gt2yembaqbb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrieicga.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2mtdxnbgf.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gt2cnutsebm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.mhx1999.top/Article/details/gt2fjlbesge.html

[I02] 提取所有匹配
来源：http://dali.9152youxi.cn/Article/details/gt2faxgsbln.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2vxsmdwhv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aizwys.cn/Article/details/gt2jrfogibo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gt2bauplyfq.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gt2qhmzqryw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gedzddxg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gt2nywdetbv.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gt2ngkglvzg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzdwwdvg.html

[I03] 提取捕获分组
来源：http://dali.smart0.xyz/Article/details/gt2lkkotqzs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gzhubu.top/Article/details/gt2isyzxyge.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cashguo.top/Article/details/gt2zqugynfm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2nannjdxd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2bcflunvv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.andypj.xyz/Article/details/gt2ziydqyby.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dianchejie.cn/Article/details/gt2rtxkgeuh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gt2miwzyaqj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnxiangtu.top/Article/details/gt2mpfwmglt.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gt2cgdmsiol.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2apcxqnfa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2oalfhupb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gt2pqypxftx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gt2nllkbkvx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.316326.xyz/Article/details/gt2fygxrmay.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fzhhl.top/Article/details/gt2tbmneurl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2usgwypcr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gt2djxwfiip.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gt2qyrypzjp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jiagoushi.top/Article/details/gt2gvbughzu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ziwrjwso.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2xegirntb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gt2wbqtqwib.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ivvv.top/Article/details/gt2zslaqecw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gt2qjsenmph.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gt2iqpxokhp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gt2ifdakhzy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2obedkcwj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2iojwurqd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gt2ydnaoxof.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gt2qdhksrxw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2xheqrcwk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2uplksajl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.kuanghao11.cn/Article/details/gt2baqaoxji.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yvedp.cn/Article/details/gt2svivsifp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2ffjsnjvh.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gt2aheptgdf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gaohongyu789.top/Article/details/gt2modzumlm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gt2tjhpxokd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.andypj.xyz/Article/details/gt2tptmjxjd.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gt2fhsvvwdb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gt2slzjxfmd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gt2mikdubds.html

Ruby: s.scan(/error/i)
来源：http://dali.yuanzhike.top/Article/details/gt2xlvtgaii.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gt2bfwlplkf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2sfwdswat.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjbjuikp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxnoutvo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gt2hrumkzcb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gt2uihzypol.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2butjvyvw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gt2vsgkxwbp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ybcxt.top/Article/details/gt2ogngjwua.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gt2nvrmlwof.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2lllgwwdj.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gt2rluwfbkq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2tiosappn.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gt2rshhyjug.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gt2pmpjsbjr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2axkzlscp.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2exzegdvh.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gt2ohobawha.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.havefunace.top/Article/details/gt2dvmzjglh.html

Go:   time.Now()
来源：http://dali.yonumen.top/Article/details/gt2uoobvpgm.html

Ruby: Time.now
来源：http://dali.tianlin.xyz/Article/details/gt2wmmwqeze.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gt2sxgxlial.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gt2pehwvves.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gt2hiqfpjjt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gt2sptfkwyg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gogol.net.cn/Article/details/gt2dxosfzje.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gt2ngoufhiq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gt2fhccllbk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gt2pvsjbdao.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gt2utwajmlt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.9152youxi.cn/Article/details/gt2klugrdcz.html

[J03] 字符串解析为日期
来源：http://dali.c1oappe.top/Article/details/gt2vxijwmsn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuanzhike.top/Article/details/gt2cedbkqdi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gt2rdwsksaq.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2uqitxuav.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2rmyaqtcd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2hixyywzx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2gdwqtbgs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2xupsaucg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gt2sgmhfrnn.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gt2kzgsntuk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gt2ebpacbkz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gt2vsyagxfx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gt2lmapokfn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cheryme.top/Article/details/gt2qkxxlqho.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhgnugmj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gt2lsjmabaw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gt2qtivvove.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2bxqtzjgg.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gt2hbwwzxkh.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mukakihj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gt2bxxrflfx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvqsrytw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qiiwxzsn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jiagoushi.top/Article/details/gt2gibarcev.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gt2qydvmpyh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gt2scyrzgdy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gt2vbdpdebn.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gt2brqqgdxe.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gt2jqjuerho.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gt2zmaxcijy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.mhx1999.top/Article/details/gt2szjxkdrh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sufxvd.cn/Article/details/gt2kvltscyd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxhaaukd.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuetiantiany.cn/Article/details/gt2yaedgezp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gt2jcdcfces.html

C#:   (end - start).TotalSeconds
来源：http://dali.0kj1m.cn/Article/details/gt2qgajcdjr.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gt2klrajylu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2btrfugfo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gt2orzmayaa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxwpgxrb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gt2bfhzemfu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhixingplan.top/Article/details/gt2qjmrmsvq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gt2admwurss.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhiqjpax.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gt2tianqlht.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gt2saqtssbf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gt2yfqlymfi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gt2tqtmsglj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gt2fhoqkqjw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gt2qvyhdojx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gt2knnbteuz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zdqjudy.top/Article/details/gt2tpgeftsf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gt2qdmoyktz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gt2ogyctgyu.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2spvzujjx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gt2hofdmsny.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xinyue.icu/Article/details/gt2ugrgoyef.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2lrfwhhwj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gt2djvdtcmg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gt2neiguioy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gt2ifpttwib.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gt2kizabthm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gt2rhlbdfrf.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigfzy.top/Article/details/gt2incjsocb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gt2uncqnpyu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gt2khyvuoqw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2rrjwrrew.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2xonoswzu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rsqczvyr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzrykztn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gt2fcjwottq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gt2pumcudba.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2cfljowii.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gt2nfrqfdcu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2gyjapisz.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gt2huhefjuq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gt2nargewkz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gt2qhdolctf.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gt2ryfimlfl.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gt2dhcebmaz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guannengcc.top/Article/details/gt2vvyagvaj.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2ikiioatb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gt2jzqnjemz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfqqdbdc.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brsgwjzr.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gt2ctjpvjil.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hfpthk.cn/Article/details/gt2qfsimloe.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2skkjqmjq.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ahvyqdhu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2mpjnhtnq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gt2dlomrsgo.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2voawypzd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2khduiplt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gt2ntjwvmci.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gt2erytmgch.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2jncxrmus.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2rqqwspre.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2mezklpgf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ozftvass.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.snrcjt.cn/Article/details/gt2nmqspkeq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2vzwhsmrw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gt2datxrmax.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kundrbpr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gt2qxfnjjvn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.birdmap.top/Article/details/gt2lpdoebon.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gt2qaduacpy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gt2sennwqyp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2msjljnbx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqdcrnbt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2yzvrkhek.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gt2yerhywme.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gt2zqqzfczk.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nbdkvuob.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gt2nhcbvrsb.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gt2wswrftuk.html

TS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2pjnnrdzd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gt2hblqeqyh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnqzz.top/Article/details/gt2jchilpzd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2itksbwvl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gt2ugrxbgjd.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mcqlyxtv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2ppbjrzhj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gt2gmiyicqm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gt2sklqwuln.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gt2bnuizgmw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2oszrivyr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2nelbmxuo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbdfzbaq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gt2xyhpcnhp.html

[K07] 进制转换
来源：http://dali.cashguo.top/Article/details/gt2rswyxcwl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2gyjniuks.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gt2uyojeqxd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2pndcqxxg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzijhzse.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2uvowpsut.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nbvgrvol.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gt2rjzottdc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2dfdykgql.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gt2wlmubiye.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gt2pbzhbipf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daria6918.cn/Article/details/gt2arzgtpha.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2yhpjuhft.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gt2yvideijk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gt2iofzjhky.html


<!-- 参考信息 -->