代发 wailian999

[Q76] 按天统计
来源：http://dali.cdnleiting.top/Article/details/gtrtwvheqc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtmbqblfkj.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gtkirqvrqo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yongpay.top/Article/details/gtmrtsyiqa.html

[Q78] 当前时间
来源：http://dali.tanke756.top/Article/details/gtrxmwxzui.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gtoyiwnhuf.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtemqchtec.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhengqikj.top/Article/details/gthfkjhgov.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gtvxrhkegj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtmjjeqghb.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtzwrdxzfs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fzhhl.top/Article/details/gttjoovbdq.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqgsqzxa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtdkexybom.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtndyhlyqy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtzgdlkbwp.html

[Q84] 去除首尾空格
来源：http://dali.yuxming.cn/Article/details/gtpnaxlkot.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtmaftqzjc.html

[Q85] 数值取整
来源：http://dali.sufxvd.cn/Article/details/gtglppmjmj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.vqdsnc.cn/Article/details/gtuaiqwogt.html

[Q86] 读取 JSON 字段
来源：http://dali.nwbrower.top/Article/details/gtospfjnfr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufsnojbr.html

[Q87] JSON 字段做条件
来源：http://dali.sufxvd.cn/Article/details/gtkqkdnuoa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.redwolf501.top/Article/details/gtchuabkio.html

[Q88] 行转列（条件聚合）
来源：http://dali.ivvv.top/Article/details/gtydxkfwjk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gtibisfxwv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gtnjcxgavk.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gttvxcucmg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenlongwang.top/Article/details/gttewdlrar.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gtirwisyyk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gtfritsift.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtdbvhmalx.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gtexsdmqlf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbrkaahkl.html

[R01] shebang 与严格模式
来源：http://dali.hysaishi.cn/Article/details/gtglrnxxds.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gtgjpqulwx.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gtgfdtuvhc.html

[R02] 变量赋值与使用
来源：http://dali.yj20258.top/Article/details/gtezesaibc.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gtbmiapxlj.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gtfllnfdiw.html

readonly PI=3.14
来源：http://dali.nanxinkj.top/Article/details/gtnkfhyudo.html

[R04] 位置参数
来源：http://dali.zdqjudy.top/Article/details/gttquufnwr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yangfankeji.com/Article/details/gtynavasjr.html

[R05] 参数默认值
来源：http://dali.shzxlz.cn/Article/details/gttrvywiff.html

name="${1:-default}"
来源：http://dali.aizwys.cn/Article/details/gtcqrchqwk.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gtykgkxhxo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtdrgfcqzx.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gtygoxxqoq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gtsujmxgpy.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gturcegbza.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gtvgdpzqxd.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtmthdjedj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjtqudnj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gtsfpngbgf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gtgnyxrdnu.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gttgyosfhe.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gtutmsxhug.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gtabxmibfz.html

stop)  echo "停止" ;;
来源：http://dali.tianlin.xyz/Article/details/gtlpurwcdf.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gtelootvye.html

esac
来源：http://dali.yj202588.top/Article/details/gtzellrxmy.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtlctktaau.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtmlwhmggx.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gtioljptrb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlulftcf.html

[R14] C 风格 for
来源：http://dali.aizwys.cn/Article/details/gtajrwngfg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gthacmyggz.html

[R15] while 逐行读文件
来源：http://dali.yj20258.top/Article/details/gtcdldsiea.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtlxdybbyk.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtuxvuawvd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtzfqgoger.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gtlnxubsxr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gtwrejllwy.html

[R18] 遍历数组
来源：http://dali.ehwqpu.com/Article/details/gtsakhlgzp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gtcftauuhi.html

[R19] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtymbcnibh.html

echo "${#arr[@]}"
来源：http://dali.birdmap.top/Article/details/gtroblpevv.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gtiufwisov.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zdqjudy.top/Article/details/gtpkgsqpep.html

[R21] 字符串长度
来源：http://dali.fengsongda.top/Article/details/gtlejcpjew.html

echo "${#s}"
来源：http://dali.zhoulong.xyz/Article/details/gtluxgomrg.html

[R22] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtejnxmubz.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gtkaihwgde.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gttntsklvj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gttakwasda.html

[R24] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtktdyggiz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gtqkleyuih.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gtlwypnrvj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tanke756.top/Article/details/gtnxxqvnby.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtldpclqsj.html

now=$(date +%F); echo "$now"
来源：http://dali.hnxiangtu.top/Article/details/gtfzkbhbia.html

[R27] 算术展开
来源：http://dali.ehwqpu.com/Article/details/gtuznpzvow.html

echo $((1 + 2 * 3))
来源：http://dali.zdqjudy.top/Article/details/gtpndzuefl.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gtwwforowb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhixingplan.top/Article/details/gtpllltkus.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtvminkixt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dashuyun.cn/Article/details/gtepxpevmc.html

[R30] 函数返回状态码
来源：http://dali.cdnleiting.top/Article/details/gthbgnebku.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gtzhbzvavx.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gthuovhufo.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gtpsiocujb.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtmxfuoxvb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtrgitqgln.html

[R33] 捕获错误并提示行号
来源：http://dali.daria6918.cn/Article/details/gtyhotndnd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gtvomqluwk.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtgkyxxsqc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtohzwjycn.html

[R35] 后台执行并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtrlwmhksz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtdqovfruu.html

[R36] 并发执行多个任务
来源：http://dali.ydzc1.top/Article/details/gtagmceisy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.iojbl.cn/Article/details/gtgdmizqtn.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gtmqpiudcn.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gtwmfwqvac.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gtqhyaqdwz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhongyouzk.top/Article/details/gtkdiysrbz.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gtcuwqydyf.html

cmd > out.log 2>&1
来源：http://dali.xinyue.icu/Article/details/gtxgvslxvy.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtjlvsunec.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gtrppmmwpe.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gtzdknleef.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gtbjafvvbx.html

[R42] 输入重定向
来源：http://dali.yongpay.top/Article/details/gtaycuqfrx.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gtyecsdsxk.html

[R43] 按名字查找文件
来源：http://dali.jyoumei.cn/Article/details/gtmkxuydtu.html

find . -name "*.log" -type f
来源：http://dali.havefunace.top/Article/details/gtdacvutzn.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gtirmckiex.html

find . -mtime -7 -type f
来源：http://dali.jinqigfzy.top/Article/details/gtxjlmjgen.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gtknqbvmku.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gtiuqhmoia.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gtpnepdcoa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gtwsencucf.html

[R47] sed 单行替换
来源：http://dali.hywenlv.cn/Article/details/gtphkwogzc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtidbdjwym.html

[R48] awk 取指定列
来源：http://dali.jiagoushi.top/Article/details/gtpegvtphi.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtcqwdmyae.html

[R49] awk 带条件
来源：http://dali.daxiang520.top/Article/details/gttvukzoxv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.iojbl.cn/Article/details/gtxeagmjme.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccluiodn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtmufhsoaw.html

[R51] 排序去重取前几
来源：http://dali.zdqjudy.top/Article/details/gtctokbidj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gtskzypquy.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gtdihiyrrb.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gtmwxqqtsf.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gtsxmardzb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gtaawildob.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtpdovpspl.html

diff a.txt b.txt
来源：http://dali.jqgfzy.top/Article/details/gtnmfdbrfd.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gtauvynoek.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gtvggpojmw.html

[R56] 远程拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtktzfjcgx.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gtdlzeepke.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gtdgtpgiep.html

ssh user@host 'uptime'
来源：http://dali.cqqwz.cn/Article/details/gthblhdtjo.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gtrrcnlrac.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhiwuduotai.top/Article/details/gtsdwljubt.html

[R59] 发 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gtuujpztmd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gtymlzjqkn.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtwmueehux.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenlongwang.top/Article/details/gtdqovfayl.html

[R61] 磁盘占用
来源：http://dali.yueranfly.top/Article/details/gtslbwfxsi.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gtohibzxja.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gtjyzbihov.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigxciptp.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gthijhlxuu.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gtpqtlbiiq.html

[R64] 结束进程
来源：http://dali.bjfxy.top/Article/details/gtsikzmupy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gthxvhxspx.html

[R65] 查看端口占用
来源：http://dali.smart0.xyz/Article/details/gtzobtjimu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinghuilouyu.cn/Article/details/gtkewlldov.html

[R66] 定时任务
来源：http://dali.nwbrower.top/Article/details/gtjqxcxusr.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gtvokqdpad.html

[R67] 生成随机十六进制串
来源：http://dali.gogol.net.cn/Article/details/gtxpncqqrz.html

openssl rand -hex 16
来源：http://dali.hnxiangtu.top/Article/details/gtxjrnlduv.html

[R68] 计算文件校验值
来源：http://dali.pengpengdd.cyou/Article/details/gtllabmtep.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gtetblohal.html

[R69] 生成随机密码
来源：http://dali.hysaishi.cn/Article/details/gtbokfbgoz.html

head -c 16 /dev/urandom | base64
来源：http://dali.guowangkeji.top/Article/details/gtirglurgk.html

[R70] 时间戳与互转
来源：http://dali.hnxiangtu.top/Article/details/gtyypqzbrk.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gthifvdhct.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtokvgaycb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sysykeji.top/Article/details/gtohdsabgb.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gttmfpgpvl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtglrnsmzp.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gtlkadofag.html

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gtetmzzogz.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtenitsdbe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gtaeubfdbx.html

[R75] 导出环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtddeyizca.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtdgluysmu.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gtdhhizmds.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtimtyncwi.html

[R77] 读取用户输入
来源：http://dali.fengsongda.top/Article/details/gtbfbqirsu.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gtqvomszao.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gtgrhaplxd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gtgsuvvpok.html

[R79] 解析命令行选项
来源：http://dali.xuetiantiany.cn/Article/details/gttqsdufey.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yongpay.top/Article/details/gtoqtwolyh.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gtemcsloqc.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gtogjqphvo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthnnwnbfd.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gthxzatjxa.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gthzxufpob.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gtmbzfckzd.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gtdmqhzpbk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtlhbbxryo.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtlaglzfev.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gtiepcuhbq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gtrljvezae.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gthnrdasen.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gtjlucokma.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtreedqasu.html

[S05] C：字符串长度
来源：http://dali.daria6918.cn/Article/details/gtjclqqllb.html

strlen(s)
来源：http://dali.redwolf501.top/Article/details/gtkmzawzup.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gtqxslyrcj.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtlculiirm.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gtmrukngqu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtntjbnczl.html

[S08] C：动态内存分配与释放
来源：http://dali.haohaochexian.top/Article/details/gtuzvjvkzm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gtpxtoourd.html

[S09] C：结构体定义与初始化
来源：http://dali.ivvv.top/Article/details/gtcwablkzd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gtpxqoopoc.html

[S10] C：指针与解引用
来源：http://dali.0kj1m.cn/Article/details/gtxkdjlmzl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gtcvgqoafo.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtsescxvyo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gtnaalcmvv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtifznxtpe.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtugobqqyn.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gtaywimbkm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtlthogvyo.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gtwgeqfpvx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtsauvkjvi.html

[S14] C：枚举
来源：http://dali.wangdashe.top/Article/details/gtcdxejwpp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jlsjyb.cn/Article/details/gtldncnoef.html

[S15] C：类型转换
来源：http://dali.zdqjudy.top/Article/details/gtzstoahdw.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtxclbumth.html

[S16] C：位操作置位
来源：http://dali.gaohongyu789.top/Article/details/gtffpprlqq.html

x |= (1 << 3);
来源：http://dali.yvedp.cn/Article/details/gtjfjdxgup.html

[S17] C：安全拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtyploleep.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnqzz.top/Article/details/gtpmsfxibe.html

[S18] C：命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtecjodoze.html

int main(int argc, char **argv)
来源：http://dali.mhx1999.top/Article/details/gtrdugzfvw.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtanrdjdpg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtzyxcgmuq.html

[S20] C：二分查找
来源：http://dali.jyoumei.cn/Article/details/gtcfkiwsjb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtuecctuzh.html

[S21] C：字符类别判断
来源：http://dali.yj20258888.top/Article/details/gtvxgcjifq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtxotwpncg.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtfgxwrzxa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenzaomai.com/Article/details/gtpibhhavz.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gteekrnbwy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gotoacloud.top/Article/details/gtomytqccn.html

[S24] C：获取本地时间
来源：http://dali.xuanzx.com/Article/details/gtfrmoqvjj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gtezmwatig.html

[S25] C：内存拷贝
来源：http://dali.redwolf501.top/Article/details/gtgzgiuvov.html

memcpy(dst, src, n);
来源：http://dali.havefunace.top/Article/details/gtazztdhus.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gtxbgbdhmp.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigufen.top/Article/details/gtdbilcytw.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gtwlixjmge.html

const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtjskpibyp.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gtbemdjjfo.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gtbwvewxru.html

[S29] C：变参函数
来源：http://dali.jiagoushi.top/Article/details/gtsadrjhyl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gtrtzqhbtp.html

[S30] C：头文件保护
来源：http://dali.svipenyu.cn/Article/details/gthjilpcpb.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gtekjmrxrk.html

#define X_H
来源：http://dali.zycfv.cn/Article/details/gtwcvhoasu.html

#endif
来源：http://dali.hnxiangtu.top/Article/details/gtabfcwjmy.html

[S31] C++：Hello World
来源：http://dali.zycfv.cn/Article/details/gtzhuudshj.html

#include <iostream>
来源：http://dali.fzhhl.top/Article/details/gtgyrqqjcq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gtrfgkkyov.html

[S32] C++：字符串
来源：http://dali.fengsongda.top/Article/details/gthdxaiwhx.html

std::string s = "hi";  s += "!";
来源：http://dali.shuidangran.top/Article/details/gtlvpxjzkd.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gtbyqcsfba.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gtslxicrwz.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gtgahqbbej.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gtxozvitjy.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gtctujprbm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtzfpwgxpp.html

[S36] C++：unordered_map
来源：http://dali.vqdsnc.cn/Article/details/gtgwadjany.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtwvbavjmi.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gteywsrprd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jianghu66.top/Article/details/gtglwxuvsw.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gtzxfpejgi.html

std::sort(v.begin(), v.end());
来源：http://dali.ivvv.top/Article/details/gtadljurtx.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gtiskirvps.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.316326.xyz/Article/details/gtsrduzmiv.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuuyrrab.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shzxlz.cn/Article/details/gtdjmwmuaz.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtjnubdvnw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gtzdnzxdqh.html

[S42] C++：继承与虚函数
来源：http://dali.zhixingplan.top/Article/details/gtlsjnwetw.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gtthwyktvc.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gtehnkhsaa.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gtmtiqamhm.html

[S44] C++：引用传参
来源：http://dali.zhiwuduotai.top/Article/details/gteoqdgjmc.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gtwbiteiiz.html

[S45] C++：lambda
来源：http://dali.xylfe.cn/Article/details/gtgathdjho.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhiwuduotai.top/Article/details/gtfchgkczg.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gtlbgjdiig.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gtrrpwmrsn.html


<!-- 参考信息 -->