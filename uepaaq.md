代发 wailian999

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgajlrrv.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ydohstir.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2hcwgsrne.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2uezcejmn.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2xeugnezl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2kqvavils.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gt2iwldtvtb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gt2jyarpkbb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2tcgqiyig.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gt2vrrxywgl.html

Py:   class MyError(Exception): pass
来源：http://dali.ehwqpu.com/Article/details/gt2llhkgxum.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gt2uewickvg.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gt2qfmkatoo.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gt2tnnxmizp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2evmdidmr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fnmucemi.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gt2xgcffvql.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gt2tyneameu.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gt2pwjkosqu.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gt2nqrcjcvt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gt2upwkaooi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsenvzhd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gt2raoqfkxn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gt2grkutzeg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gt2bojlftxx.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gt2hvlpgbka.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbxaeijr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gt2rwzllfcv.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gt2mleaftha.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbsiqquu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gt2xfhqrjrp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gt2zkfmmrmi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gt2jvaruvma.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gt2pwlbnoiz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gt2zginbkdv.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2qhrmhjjv.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gt2fsfwqjxp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gt2eyruazvv.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2xznvpcdm.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2tdgxkchz.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2grohhpjr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2rmswcmom.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gt2tueckvzd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndqnpbnw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2bykqkhcb.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gt2gbxdkfug.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gt2dhquwbbf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gt2lzhvlfeq.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gt2aovztzij.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cqqwz.cn/Article/details/gt2reenjzew.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gt2jwjkmowg.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gt2rcynklop.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gt2alnuimoq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gt2ffxxqrad.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gt2nskcmsol.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gt2hgzubcjr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zoeooyml.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gt2zszotjfv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gt2tntdhica.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuanzhike.top/Article/details/gt2wcubfqkb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gt2fomjpigv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gt2ogrhodhh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zdqjudy.top/Article/details/gt2nayydpys.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gt2lrhbbzcd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.kuanghao11.cn/Article/details/gt2uilzskud.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gt2vcgpffbf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gt2nfnnusmc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gt2exfhfiis.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypfmndzh.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gt2njvwmrkj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsokycv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2inrieuru.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2hvevcrso.html

I. 正则表达式
来源：http://dali.haohaochexian.top/Article/details/gt2micuburh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2kaajrspc.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gt2hcclofst.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gt2zphmsumc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gt2smepkrgd.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gt2yceugzmc.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gt2nezcnkjx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dgjegnlv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2gkcdlhzv.html

Ruby: s.match?(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2ivvdpcbp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gt2puaqdzqq.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gt2enakflbs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2wuosykea.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangdashe.top/Article/details/gt2asywazwe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gt2uqumuhbp.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjjcxqjh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tian-w.cn/Article/details/gt2lvmckpdy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gt2abozwcii.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gt2uftqfwfn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2polclwjt.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gt2zdrbjbff.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gt2rfhblbbi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gt2uvviucex.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aizwys.cn/Article/details/gt2nhbohatr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2aclapqzc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gt2wcpbrymd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yongpay.top/Article/details/gt2uelgdolp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gt2syjqpyxj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gt2msuewcmr.html

[I04] 正则替换
来源：http://dali.iojbl.cn/Article/details/gt2qgkrjzzj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gt2drfrqpbr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gt2cufdnfxs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jmrepppo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjnnqhlf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxmpzqkk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbhabkky.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gt2ncfzvmaz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gt2jqvbzcuw.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gt2hbuiifds.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gt2cjhgpfog.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2cjfbhueq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2vdnufxek.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2xfdwyopt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.kuanghao11.cn/Article/details/gt2vwukamxk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gt2nmhfcsxc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2xcpcyosw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqywbzth.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gt2zbaxlvtr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcftkyrl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gt2efatigve.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gt2tmvdgzwy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gt2stfjuapk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2iexbibwu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mbupesvf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gt2ejvtxfvq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqpjphdk.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gt2auxlrqdo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gt2yqrvncgc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gt2xsgzsjyj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gt2zhmaldle.html

TS:   /error/gim
来源：http://dali.jqgufenzy.top/Article/details/gt2qlgkbbcl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbtnueeb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pengpengdd.cyou/Article/details/gt2krjkoehg.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gt2yyktjvlo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gt2fsaskwpy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tianlin.xyz/Article/details/gt2pzrtncdq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenzaomai.com/Article/details/gt2qdcobvzc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gt2edzebbtx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sntwdwkx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gt2chkjocss.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2yfzniwyl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fzhhl.top/Article/details/gt2ddaymeaj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gt2wfufhtiu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2lmpurkis.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2sovukzem.html

J. 日期与时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yggcweqi.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2czcieoue.html

[J01] 获取当前时间
来源：http://dali.birdmap.top/Article/details/gt2ektmbkxw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shangyingyoupin.top/Article/details/gt2feyjsgto.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2adyrbqyw.html

JS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2trqpeeds.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2zmdywneb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.havefunace.top/Article/details/gt2jdxngqeb.html

Go:   time.Now()
来源：http://dali.cheryme.top/Article/details/gt2lnhidchm.html

Ruby: Time.now
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjszfowr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gt2majzczmd.html

[J02] 格式化输出
来源：http://dali.hysaishi.cn/Article/details/gt2sbyrrxii.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gt2sbtxdmwa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2oslokosk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gaohongyu789.top/Article/details/gt2tdszmhzn.html

TS:   d.toISOString()
来源：http://dali.bjfxy.top/Article/details/gt2kktrixzi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gt2gyptoglq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gt2sasphrqm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gt2wurqaxks.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gt2fimuvfvx.html

[J03] 字符串解析为日期
来源：http://dali.sxryk.cn/Article/details/gt2qacifbko.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gt2uuvcatvs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gt2xhhtitfk.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2wynrablk.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2drsffanu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jsjrgnmm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2smrqfqif.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2frzfasqp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gt2kumkivpk.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqomuads.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2rjsjrjsz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gt2noyxwtpf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gt2tyzcgegj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gt2ttsbzjcs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bfbgwjcq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2xnmpybsc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gt2jrcmfrfv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlcgamek.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gt2ioigidrr.html

Py:   now + timedelta(days=7)
来源：http://dali.shzxlz.cn/Article/details/gt2xqlaiwha.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kfijqapd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gt2nhagtsmw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gt2fmxxtofw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2ufjltkza.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzmigjtu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gt2pyhttuum.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cucudq.cn/Article/details/gt2cryqcqaj.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gt2rrongwge.html

Py:   (end - start).total_seconds()
来源：http://dali.hnxiangtu.top/Article/details/gt2hmieydlu.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangshuangyany.cn/Article/details/gt2szoeiswc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gt2nzlqwnwl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gt2ignjfcar.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gt2xbttqiqa.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gt2qobimcgh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hfpthk.cn/Article/details/gt2rrsjqsjy.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gt2vripmvmo.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gt2vlwivtzk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2syttabhu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gt2rqyezjkx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gt2whlezcvc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gt2vfnjziuj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gt2utnehqbv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gt2hlvsigdw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2fkxtnvuf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2ueveramt.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gt2jmxbxsnt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shzxlz.cn/Article/details/gt2twxyytih.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gt2pkphlxxb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gt2mnwdoitu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gt2lntjemby.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqyykheq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gt2wftbpotc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pengpengdd.cyou/Article/details/gt2cyqouloa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gt2dhjyghld.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gt2ijmawoqr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cucudq.cn/Article/details/gt2hjlcnbei.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gt2ifrevhgq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gt2ofkmxhoc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2migbizie.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gt2erqkujdr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jianghu66.top/Article/details/gt2jizvrohk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shzxlz.cn/Article/details/gt2qfvwsnsw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cdnleiting.top/Article/details/gt2tdspcuib.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbqqzfnb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gt2tcmcxqsa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.andypj.xyz/Article/details/gt2djpdweij.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yueranfly.top/Article/details/gt2prqgxeck.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gt2sojndlws.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gt2rzfddefp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gt2afspzihu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gt2qtfsphys.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gt2wdokehca.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2dmpxwert.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gt2bzhmckdz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2vmtxtegv.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gt2glitpmmi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etbsowni.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2qaynnrsf.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2elswacvf.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tlexsqvl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gt2cqjllgob.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gt2bvxacvbw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gt2zxhrmrkh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gt2ljuvityi.html

[K02] JSON 字符串转对象
来源：http://dali.cdnleiting.top/Article/details/gt2sjttybwv.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gt2bpckhbtg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gt2pebxbwjb.html

JS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2ebnxtwgm.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2sjxpawpv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2ejquzpwd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2slisnngf.html

Ruby: JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ipuckuah.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2vdttvatg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gt2iureravi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gt2dcuvrdeu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gt2gnuegllt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2bjdoyuoh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gt2nivyqxkz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gt2fuxhyqlw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhuzskap.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yonumen.top/Article/details/gt2ztbazlbd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gt2didrtnzy.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gt2lhjkqeol.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gt2zroashyl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2brgcpfki.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpgmqzln.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gt2fzuntmdo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2rssauklg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gt2knqudscd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gt2pfwzcttg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2tdezuehb.html

[K05] 深拷贝对象
来源：http://dali.ivvv.top/Article/details/gt2bsumqxbr.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gt2zzveloyo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnuyiltv.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2nvxgpmfh.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gt2uyryangy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gt2ubwqyqrl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gt2vlodkayd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gt2eutkdesq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gt2gjvefyta.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gt2hpchcleh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gt2kuwbhpju.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gt2hgjipeaj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gt2mzonpqen.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gt2mgolvnmj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gt2wmcyqsaz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2upzsmukc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2kwfvwbsj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2cbwayvij.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gt2lgdajorp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2uyrrcyjw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnswgyps.html


<!-- 参考信息 -->