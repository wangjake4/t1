代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gaohongyu789.top/Article/details/gt2lyncainw.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gt2okaxkejp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gt2fedjtgwm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gt2absogmoc.html

[Q76] 按天统计
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfzbqoch.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhongyouzk.top/Article/details/gt2xgcplntm.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gt2nnmorfnl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gt2uppmbhvo.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gt2ljvsulvv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.feifeiyinyue.top/Article/details/gt2lfrylppo.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gt2czahqfpc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhoulong.xyz/Article/details/gt2pnwzhygt.html

[Q80] 字符串截取
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfvpbyus.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2teomgfhu.html

[Q81] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gt2xdisrpgk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2jqkcqjso.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gt2tupmdhva.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vhlbxhjo.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snjufwkw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2quennkvf.html

[Q84] 去除首尾空格
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ectopgix.html

SELECT TRIM(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2wznosohc.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gt2ituwiubt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gt2sngudqsd.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gt2yotabtpg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gt2gzhpswdf.html

[Q87] JSON 字段做条件
来源：http://dali.redwolf501.top/Article/details/gt2gzvrvpxb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xylfe.cn/Article/details/gt2ztpzsugk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gt2dkczgxin.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbvrtbob.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2nfpuxrar.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gt2hmdnlbyi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tnccbaji.html

[Q90] 生成序号列
来源：http://dali.andypj.xyz/Article/details/gt2yvfbdugb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gt2sxpvjptv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2zewavjgk.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gt2mddeqwrk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdjyaqqx.html

[R01] shebang 与严格模式
来源：http://dali.redwolf501.top/Article/details/gt2zcynxzmu.html

#!/usr/bin/env bash
来源：http://dali.wangdashe.top/Article/details/gt2llukodbe.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gt2xuktscmw.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aeliibhx.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gt2lcnygrrl.html

[R03] 只读变量
来源：http://dali.yanxiufei.cn/Article/details/gt2ffrcmlms.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gt2hxshmadz.html

[R04] 位置参数
来源：http://dali.hysaishi.cn/Article/details/gt2mfotviya.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kxvqkwlr.html

[R05] 参数默认值
来源：http://dali.shangyingyoupin.top/Article/details/gt2cojdbevh.html

name="${1:-default}"
来源：http://dali.yj20258888.top/Article/details/gt2ukqfmgja.html

[R06] 判断命令是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2gcpzvzek.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gt2uisdwody.html

[R07] if 判断文件
来源：http://dali.sxryk.cn/Article/details/gt2kcupydry.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gt2eebsgycg.html

[R08] 数值比较
来源：http://dali.yuxming.cn/Article/details/gt2wgjfbgrh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gt2orezhfmi.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gt2qwlupsmv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2drsjwuof.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jybiendy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2aijgksvk.html

[R11] case 多分支
来源：http://dali.hongshengwenyu.top/Article/details/gt2jeidmgfl.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gt2ijxmjwsh.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gt2feaatofm.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gt2szgyjwli.html

*)     echo "未知命令" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2fhotlhre.html

esac
来源：http://dali.hysaishi.cn/Article/details/gt2xaqnlodq.html

[R12] for 遍历文件
来源：http://dali.yanxiufei.cn/Article/details/gt2nldwqwnz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zdqjudy.top/Article/details/gt2cmozulmq.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gt2ucdqvtsp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gt2vxjcuzgc.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gt2cpfkkgbe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2ddmyhcjc.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2xlhcyrrb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.9152youxi.cn/Article/details/gt2lhsisdtg.html

[R16] until 等待条件
来源：http://dali.tianlin.xyz/Article/details/gt2khnixxnf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gt2gvhflxxj.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gt2lpvygbqq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gt2daiofegt.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gt2hhznqdtd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gt2psxpfidc.html

[R19] 数组长度
来源：http://dali.bjfxy.top/Article/details/gt2olqnpbpy.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gt2eeedpbje.html

[R20] 关联数组（字典）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lergnrho.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gt2ibfobrkv.html

[R21] 字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gt2aemkuzpy.html

echo "${#s}"
来源：http://dali.hysaishi.cn/Article/details/gt2ctrflakm.html

[R22] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kgrfgyyd.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gt2upjndpet.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gt2wpaghqlp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxinkj.top/Article/details/gt2dmssrmbd.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gt2ngtmyrki.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2pverkopm.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tznpzkhw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2zyekhbge.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gt2dmnaagqa.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gt2zobrraem.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gt2dlsknlvx.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohcuhikv.html

[R28] 浮点运算
来源：http://dali.yanxiufei.cn/Article/details/gt2wqxmxhgq.html

echo "scale=2; 10/3" | bc
来源：http://dali.yanxiufei.cn/Article/details/gt2wawiutns.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gt2siehxlnj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2inwaauva.html

[R30] 函数返回状态码
来源：http://dali.hysaishi.cn/Article/details/gt2uswnnbdp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gt2dexinkhj.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwquczwd.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xwjenuaq.html

[R32] 参数个数校验
来源：http://dali.dashuyun.cn/Article/details/gt2qekpxqtm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gt2iqdlxhfa.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwqpezkz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gt2bczoqscb.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gt2yjhbhkxq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gt2uwxlvvig.html

[R35] 后台执行并等待
来源：http://dali.haohaochexian.top/Article/details/gt2nsylajal.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zycfv.cn/Article/details/gt2ktgeatyc.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gt2kqoiygmh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258.top/Article/details/gt2ksjoypun.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gt2jybvbbaq.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqcebibu.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gt2wjladvjy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dianchejie.cn/Article/details/gt2hluqzbrq.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gt2nlbtueht.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gt2isdeufuz.html

[R40] 追加写日志
来源：http://dali.sysykeji.top/Article/details/gt2jntfnakn.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gt2zarpicmu.html

[R41] 丢弃输出
来源：http://dali.cqqwz.cn/Article/details/gt2qqlileqy.html

cmd >/dev/null 2>&1
来源：http://dali.yvedp.cn/Article/details/gt2vwspfafo.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gt2upjxiehj.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gt2xkorycyx.html

[R43] 按名字查找文件
来源：http://dali.pycfn.com/Article/details/gt2okscgbmo.html

find . -name "*.log" -type f
来源：http://dali.daxiang520.top/Article/details/gt2qrujokjb.html

[R44] 按修改时间查找
来源：http://dali.ehwqpu.com/Article/details/gt2mzvmwmat.html

find . -mtime -7 -type f
来源：http://dali.ehwqpu.com/Article/details/gt2xhfstddr.html

[R45] 批量删除
来源：http://dali.sweek.top/Article/details/gt2ypkoytvn.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gt2kvsxvqiw.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gt2xiluvslw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gt2jfivjeel.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gt2qygbkust.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2zzfpdsrt.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gt2fhyyzmiz.html

awk '{print $1, $3}' a.txt
来源：http://dali.xinyue.icu/Article/details/gt2ekkconmb.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gt2zvwfesbx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gt2dxxvqkqe.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gt2mgygnaxm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2knsdxpbf.html

[R51] 排序去重取前几
来源：http://dali.yj202588.top/Article/details/gt2vetkxemx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ryplyztg.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gt2pdszgwxn.html

wc -l a.txt
来源：http://dali.cucudq.cn/Article/details/gt2wcowwdsk.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gt2olxaioxg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wefjnnpy.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gt2nlcygpdp.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iscllnjp.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2incpgzwx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.bjfxy.top/Article/details/gt2krrncqom.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gt2beoykgwd.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gt2keaznxyl.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gt2kpskekfb.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gt2gyfpmsfc.html

[R58] 下载文件
来源：http://dali.snrcjt.cn/Article/details/gt2cuabztiq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj202588.top/Article/details/gt2wuboyexg.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2zugkvxqc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guowangkeji.top/Article/details/gt2ttdvtxha.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvykfkuq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.smart0.xyz/Article/details/gt2pmleemfl.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gt2hrdvwydd.html

df -h;  du -sh *
来源：http://dali.ehwqpu.com/Article/details/gt2pdutmfgo.html

[R62] 找最占空间的文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2leojixmi.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gt2ncpdcepm.html

[R63] 内存与进程
来源：http://dali.hammf.cn/Article/details/gt2btpzwrha.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gt2zuufcdux.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gt2hkudzemr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xgrxvrua.html

[R65] 查看端口占用
来源：http://dali.yanxiufei.cn/Article/details/gt2fusbpeoy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gt2qskitkce.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gt2hraafvcs.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gt2firgpjbp.html

[R67] 生成随机十六进制串
来源：http://dali.bjfxy.top/Article/details/gt2xikvrosf.html

openssl rand -hex 16
来源：http://dali.yanxiufei.cn/Article/details/gt2zbqykfwt.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gt2wutufzds.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gt2kqztfsqs.html

[R69] 生成随机密码
来源：http://dali.wangdashe.top/Article/details/gt2swbsrwrz.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gt2ekthgeqh.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gt2tmcqwrjp.html

date +%s;  date -d @1700000000
来源：http://dali.ybcxt.top/Article/details/gt2hnznuopy.html

[R71] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gt2bihidzec.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.svipenyu.cn/Article/details/gt2hnpopmah.html

[R72] 等待端口就绪
来源：http://dali.zhixingplan.top/Article/details/gt2nxbygfak.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqjkdtmz.html

[R73] 分割大日志
来源：http://dali.cashguo.top/Article/details/gt2yefuldpc.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gt2nozelydi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiikvys.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gt2llyqpyco.html

[R75] 导出环境变量
来源：http://dali.fzhhl.top/Article/details/gt2kqhyfrap.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gt2zysdhmgf.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gt2hitudkxx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gt2mkscqtec.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gt2qtysgeeq.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gt2fxnmcajm.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gt2frkkpuky.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gt2gaoygryy.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gt2hshurzro.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xinyue.icu/Article/details/gt2buqmyuhv.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gt2wzpceevz.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gt2jhrwflli.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ciifkrtw.html

S. C / C++ 专题
来源：http://dali.cdnleiting.top/Article/details/gt2gtfolpnw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2wgbyxnpr.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2kwvucyyb.html

#include <stdio.h>
来源：http://dali.9152youxi.cn/Article/details/gt2uinzygah.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gt2bocbhiha.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gt2ptsxsjaw.html

int a = 10; printf("%d\n", a);
来源：http://dali.tanke756.top/Article/details/gt2nhfgufvq.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gt2rfdqcjxa.html

int x; scanf("%d", &x);
来源：http://dali.hnqzz.top/Article/details/gt2hebyizpv.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gt2rgyajsgi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gt2acjyptvd.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gt2jwyfozvc.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gt2oondyptk.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gt2ccapwdsw.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvrzulzh.html

[S07] C：数组遍历求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uuavgucq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gt2rdxwwynf.html

[S08] C：动态内存分配与释放
来源：http://dali.daria6918.cn/Article/details/gt2oksqphzh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258.top/Article/details/gt2patfqigr.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gt2hlaqhwzv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gt2algifdak.html

[S10] C：指针与解引用
来源：http://dali.bjfxy.top/Article/details/gt2uspkgvaa.html

int *p = &a;  *p = 5;
来源：http://dali.shangyingyoupin.top/Article/details/gt2aoyvzavp.html

[S11] C：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2csuofjym.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2buuwdjaz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2ximywpse.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gt2onyjmpoc.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gt2wlpzxyuf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aizwys.cn/Article/details/gt2xvuhunak.html

[S13] C：宏定义
来源：http://dali.0kj1m.cn/Article/details/gt2pjvnzyew.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.birdmap.top/Article/details/gt2ddqmmfla.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gt2rqmyuymp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuanzhike.top/Article/details/gt2xovzkqwk.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gt2tpawiexy.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gt2wdotpqpf.html

[S16] C：位操作置位
来源：http://dali.yj20258.top/Article/details/gt2vkofkyvc.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gt2mcgzcafm.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2jyxbudyo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yonumen.top/Article/details/gt2ylcveehh.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gt2xcoproph.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gt2kihtlyis.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gt2rwpcbykg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gt2odsdolya.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gt2ogshpyle.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2tkpasmmw.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gt2wavdjndn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gt2lahojuqr.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gt2mdhzaovl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbbnrkmc.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gt2tcrlzflo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gt2seypimaq.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gt2cqsecwic.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gt2lhnhtiiv.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2rqtjpemk.html

memcpy(dst, src, n);
来源：http://dali.guowangkeji.top/Article/details/gt2dptatkqt.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gt2ryppnbfd.html

memset(a, 0, sizeof a);
来源：http://dali.yvedp.cn/Article/details/gt2zjutsxjh.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gt2ielcvpdl.html

const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gt2fltwcsmf.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gt2asbbtxgn.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gt2xmxtorws.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gt2luurvcxb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yongpay.top/Article/details/gt2xrmzgewm.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gt2iujuxrij.html

#ifndef X_H
来源：http://dali.ydzc1.top/Article/details/gt2lhmamgcu.html

#define X_H
来源：http://dali.gzhubu.top/Article/details/gt2ouypzibt.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gt2zjofdnse.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2dxghdlrg.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gt2nxwtwukp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajxqxbkb.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtvpljhv.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gt2jpcalbpr.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gt2ymswjxoq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daria6918.cn/Article/details/gt2gqgebayh.html

[S34] C++：遍历 vector
来源：http://dali.ivvv.top/Article/details/gt2sjxwtkny.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gt2fdpkpvtc.html

[S35] C++：map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpsfyeiq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2facxjikx.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gt2gxnmuwxz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2yhdvrusy.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gt2wnuivamn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gt2wxjxdpdk.html

[S38] C++：排序
来源：http://dali.mhx1999.top/Article/details/gt2ibejtqnn.html

std::sort(v.begin(), v.end());
来源：http://dali.shzxlz.cn/Article/details/gt2xtpfkzgo.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gt2pmxvmkhi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gt2jzslbmvs.html

[S40] C++：查找元素
来源：http://dali.svipenyu.cn/Article/details/gt2biqcerct.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gt2gmqozjfd.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gt2hegvygdv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gt2uligkkxf.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gt2ginipqnm.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gt2hdjiryyb.html

[S43] C++：智能指针
来源：http://dali.0kj1m.cn/Article/details/gt2uvrbzxas.html

auto p = std::make_unique<int>(5);
来源：http://dali.havefunace.top/Article/details/gt2xphbrogk.html

[S44] C++：引用传参
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqkgoapw.html

void inc(int &x) { ++x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkgszxms.html


<!-- 参考信息 -->