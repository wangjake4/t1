代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.sxryk.cn/Article/details/gt2kjxfzjhu.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gt2hdkvsdnu.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gt2cksgflvv.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2isuxbtzm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxkkjeif.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gt2wmcokums.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2toksbsax.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gt2gabsmsng.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gt2kylbkpgv.html

Ruby: rescue ArgumentError => e
来源：http://dali.svipenyu.cn/Article/details/gt2rbluvnfi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gt2vrjpehlt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gt2gmsjmxng.html

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvtjieef.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gt2fbpjbgel.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2mlqbefsn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gt2djmpvxod.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nwbrower.top/Article/details/gt2cbkhsxvx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gt2tdulhqwh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gt2tdzikvaq.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gt2tbvvebub.html

[H07] 断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpigpylu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pycfn.com/Article/details/gt2tokcvann.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gt2zibeonem.html

JS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvahgjtv.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gt2hrxrceul.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gt2zvjvdxag.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gt2khrmnthy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gt2ertgtknf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jroymord.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gt2nmpucuws.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.mhx1999.top/Article/details/gt2beswihbw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gt2kcjqqgje.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gt2gnelmsbx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gt2cufvawtm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gmrcescp.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gt2txqrvvtk.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuanzhike.top/Article/details/gt2qqsdlpog.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gt2ywqsszqq.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gt2irlmhhzm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ehwqpu.com/Article/details/gt2jzophdkx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.9152youxi.cn/Article/details/gt2crdrkjyl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hfpthk.cn/Article/details/gt2xtntxzsi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dklxtmws.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gt2wpdagtcw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezdsxpmh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gt2nuuvvyhj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kfntjudw.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gt2yivonnlo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gt2kjkxmeah.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gzhubu.top/Article/details/gt2fdughurt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gt2ikzfcjkw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2ijscuydy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cscrtzoy.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gt2fkqcjfjs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gt2sfvmogrw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2qgkfesjx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2icljlnjr.html

I. 正则表达式
来源：http://dali.aizwys.cn/Article/details/gt2snuugfie.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2xhsgeqhn.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2czrnbyww.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gt2zvyikobs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gt2nqowxrpo.html

JS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gt2owbksddy.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gt2svpalops.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenlongwang.top/Article/details/gt2rlwympsk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gt2lkieswny.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gt2bjfdtxxp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdwdydtx.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2kcpixefw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jevlvziq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.havefunace.top/Article/details/gt2iawaacrk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gt2psdihnrl.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nvbhkqyh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tndregcr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gt2upzhvaoh.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gt2dkgvndzy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2kspbuoxz.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gt2ktyhxent.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2bhcfloek.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gt2lalsfymo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhengqikj.top/Article/details/gt2gthsplaq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbjbohmo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gt2gjnevusl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfjlyfdf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gt2fvceoovp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gt2agasyezm.html

[I04] 正则替换
来源：http://dali.mhx1999.top/Article/details/gt2rwilaair.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yangfankeji.com/Article/details/gt2obpfrlqy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2wwmsvkhf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtzrxdw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gt2frrzpoxq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gt2vdmmsqkv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2hkvyqtuj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gt2tliohkbu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gt2ilaaeqwy.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gt2yuipizyw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dojkiykv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwlvdnzd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gt2npqcmgag.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2pghppqwb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2btvhmfgj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gt2wgupufzg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2mvsvexsm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gt2pehmvnvd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gt2yhcdprlg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2klijzrim.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gt2scorqgge.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gt2slqyqkba.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gt2eufykxcr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2pnlqxcgy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cucudq.cn/Article/details/gt2pnideokz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gt2oqmfuklr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ijynofes.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gt2ngmihtxu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuxming.cn/Article/details/gt2ulxpewkb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gt2hwkunbkl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gt2hietbzga.html

TS:   /error/gim
来源：http://dali.ybcxt.top/Article/details/gt2dlrjnmug.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qofjiscc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.meibo888.top/Article/details/gt2qomiltow.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gt2dmgtyohl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gt2enylseyh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gt2rjpijppr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sysykeji.top/Article/details/gt2cptuqiou.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gt2ldqpnygq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iljdmcnn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gt2jqfpvifq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wziozwmb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gt2gqjrlopw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gt2vqmjnpcm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2vwasjicm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2fuqdaera.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gt2kelorbbc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2inyfhbpb.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2vbzpkscy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigfzy.top/Article/details/gt2puntlzno.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gt2pdyfrips.html

JS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gt2sdnbfbhi.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2tbaqyopc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2uwaruykz.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gt2vylyojjg.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gt2tywlhvmg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gt2jdmwigyk.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gt2pbxyhctg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gt2pvpevzar.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gt2mxpwnxpp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gt2uutwbeur.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gt2tiflrlcs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bfwoyxqg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gt2eiznajvq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2nrddzpdi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gt2vbrjhaej.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gt2aikeztzq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gt2rfqagwkh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gt2vdmlpail.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2zssughda.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2yigmktej.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2lkbeayax.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2lnpbtzvm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2lkrnfjqe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gt2zfsqhqyr.html

[J04] 时间戳与日期互转
来源：http://dali.guannengcc.top/Article/details/gt2icexnffh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gt2pxdtjvef.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gt2flwcpttx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvmuzefh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gt2wjicewsn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.redwolf501.top/Article/details/gt2ddvunoch.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2vmixuins.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2ghgfxold.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gt2essymkrn.html

[J05] 时间加减（加 7 天）
来源：http://dali.havefunace.top/Article/details/gt2mhpgabec.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gt2rbkddjgd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gt2ukghmqve.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gt2blbmhnfl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkjjhchv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gt2duhetduu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2afbtgygy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gt2kvmpggaj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gt2ppdgfwfb.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gt2rqquvxsy.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ceecnobh.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gt2hbxfidad.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gt2jnxmdqmr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gt2fwsjqhjh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gt2oonqctei.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xxllcmvs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.c1oappe.top/Article/details/gt2nijfudxr.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhoulong.xyz/Article/details/gt2demvqthi.html

[J07] 比较两个日期
来源：http://dali.jinqigfzy.top/Article/details/gt2mwmabdwh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2tbzyunfp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.quarkkingdee.top/Article/details/gt2skiuvykc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2misqiplj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gt2dfjajjts.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2ubsnfvak.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gt2ultedfzs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2xdhsfkmj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2aodjquxx.html

[J08] 提取年月日与星期
来源：http://dali.pengpengdd.cyou/Article/details/gt2tggprhet.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gt2qqreccal.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gt2ptxkukfd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gt2jtphbhzz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gt2mlvosxip.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gt2nngszwsj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gt2qxvrxglh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gt2gqnlqsnr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gt2tmjbxtos.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gt2wfnlpsfk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gt2gayrcedc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gt2cxkyyzgo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gt2kjgmudiu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gt2lkxlxcef.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gt2iloykanm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zycfv.cn/Article/details/gt2vuqvzlfv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gt2grfrlsql.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gt2tqgjbhtz.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gt2wcjpmwqb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gt2ztcuquwo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aibaodan.cn/Article/details/gt2cmzxwygb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bburiodl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjklricc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guowangkeji.top/Article/details/gt2casfxbia.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gt2qkhgfkgo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gt2hdlsdspw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gt2fmdxepab.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2vpqppwms.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gt2nbhteujr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2pnidktdq.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gt2mpyxsmtc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gt2cfejuwvi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gt2gvjuywou.html

JS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gt2nyisuqub.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gt2rfqwbsat.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gt2uhkbhncd.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2cyhclfui.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gt2rjivcmkk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2hvijxefm.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gt2dserljnl.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gt2xszxiolx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpkuecql.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2dgluyrwe.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2xlnizksc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2bzszygiv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gt2nkuznhvg.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2dqvlbeam.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangdashe.top/Article/details/gt2hcgkbeix.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gt2fdsxxzcg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gt2fuybixhk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gt2xsmwmuhf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2crklvjei.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2svowoesl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2cvqjlnvu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gt2spcdbgtp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gt2cxjdqwfw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sufxvd.cn/Article/details/gt2oqvjvrix.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gt2azcujzfo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2cnlavolo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gt2lulfdtnb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gt2xteugskc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gt2wcalxwjk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2gshrosbj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gt2paxaowfa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gt2iuchnacc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gt2qjbhuzhg.html

[K05] 深拷贝对象
来源：http://dali.gotoacloud.top/Article/details/gt2rxceasfe.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2jlbdkjvn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.snrcjt.cn/Article/details/gt2ezktyezc.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dchybhag.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gt2zzoheoje.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gt2okqmdysx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gt2jbjfwkql.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gt2sauttsqz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gt2vzfvmofb.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gt2duzxyvns.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.andypj.xyz/Article/details/gt2xmofukks.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ybcxt.top/Article/details/gt2hcvzgoxm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2rpbpmoxz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gt2jgjujttj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gt2gyouynir.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2tnysyemy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2ceohhjoz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uzdysddt.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gt2yzntbjra.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2qyasgivl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gt2egfsbvqh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2wyrgjsyk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2vczhkvlt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2qfzlfuru.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxuanxn.top/Article/details/gt2yxjsyqyb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gt2ogabtlop.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2bmmrgdkh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuetiantiany.cn/Article/details/gt2hognzoca.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2gtpdnmpe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gt2osclphxi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gt2idtzmhzn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gt2jjfhigix.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqydmfjb.html

Go:   encoding/gob
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kubpdwvc.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gt2cnzkakns.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2inmteene.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2eajrngyq.html


<!-- 参考信息 -->