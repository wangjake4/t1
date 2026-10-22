代发 wailian999

ANALYZE TABLE users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xpaesrgm.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgpihslg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gt2wiapimnb.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gt2tdluezzk.html

SHOW INDEX FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2tvxvwvnf.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gt2intzoysy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gt2zytneyej.html

[Q74] 强制使用索引
来源：http://dali.hfpthk.cn/Article/details/gt2ynlvchbq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxvuodmw.html

[Q75] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gt2nvkcidog.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2nevnilal.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgfzy.top/Article/details/gt2jqaegbod.html

[Q76] 按天统计
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgefznnq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gt2knjgzzft.html

[Q77] 时间加减
来源：http://dali.yvedp.cn/Article/details/gt2asvxuzvk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gt2ybrnbsrj.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gt2kbgyboge.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjyvyebs.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gt2unpknzob.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gaohongyu789.top/Article/details/gt2xsnitmaf.html

[Q80] 字符串截取
来源：http://dali.ehwqpu.com/Article/details/gt2nslvexvm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2ppezxuok.html

[Q81] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gt2ywzkyobe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2igysfora.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gt2wepfijqd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2thdkntun.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqjshsmk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2wtcvgozg.html

[Q84] 去除首尾空格
来源：http://dali.chenzaomai.com/Article/details/gt2pmzqxbsu.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2psbiobys.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iddonndf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxinkj.top/Article/details/gt2clamuohh.html

[Q86] 读取 JSON 字段
来源：http://dali.yuxming.cn/Article/details/gt2zmuzhqnb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gt2fddkcljm.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gt2ovhtjnsx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gt2oboejmty.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenjidiqi.icu/Article/details/gt2viadipqs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gt2oigtqdkl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2koeywgyn.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2tfchicay.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gt2ruclvomp.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gt2mlupgcov.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2icdbuorr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2wlgeoguw.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gt2kvircjso.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2zeycfqsm.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gt2wxnvkztg.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gt2uiimkcfa.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gt2qvhfefpv.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gt2mnwuhyoa.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gt2webamzwq.html

[R03] 只读变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvuckhtt.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gt2nrexcpak.html

[R04] 位置参数
来源：http://dali.hywenlv.cn/Article/details/gt2pkxpyvdd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.iojbl.cn/Article/details/gt2zhwcdrbn.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gt2afcpuylk.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gt2ptrjngaf.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gt2ccsvygct.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzkpxtik.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gt2mbakumov.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2vuvwxizg.html

[R08] 数值比较
来源：http://dali.gogol.net.cn/Article/details/gt2ytsyejqs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cashguo.top/Article/details/gt2vytvhlqt.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gt2viurndzo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.c1oappe.top/Article/details/gt2fyoryqqt.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gt2mqohuumy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aibaodan.cn/Article/details/gt2zyalhhpr.html

[R11] case 多分支
来源：http://dali.yangfankeji.com/Article/details/gt2ffdkufhh.html

case "$1" in
来源：http://dali.gotoacloud.top/Article/details/gt2sbccwdng.html

start) echo "启动" ;;
来源：http://dali.guannengcc.top/Article/details/gt2wviegpwm.html

stop)  echo "停止" ;;
来源：http://dali.zycfv.cn/Article/details/gt2whmovtcz.html

*)     echo "未知命令" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2gqvvckjn.html

esac
来源：http://dali.andypj.xyz/Article/details/gt2ixupoiod.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxblitii.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gt2tgnycutq.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxnuoznp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2xonrvmmn.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gt2atnwqmhq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2olvyzecl.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2vvbwyjwq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjfpzdbh.html

[R16] until 等待条件
来源：http://dali.dianchejie.cn/Article/details/gt2eayoyxda.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akdkbxxx.html

[R17] 数组定义与取值
来源：http://dali.xinyue.icu/Article/details/gt2felxgiyo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2kzkqljhk.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gt2nwjmxihg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2hvpyomcs.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gt2lnsakvkg.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gt2twdxbafi.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqrjybpf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gt2ugrufrse.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gt2qlufgpoi.html

echo "${#s}"
来源：http://dali.nanxinkj.top/Article/details/gt2xcczrirz.html

[R22] 截取子串
来源：http://dali.yuxming.cn/Article/details/gt2xcuingav.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gt2guzyvexv.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfatkmle.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sxryk.cn/Article/details/gt2egssyvjg.html

[R24] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gt2jmrxuvml.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gt2hhcwabin.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gt2dfhguyjy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gt2msmvvnlw.html

[R26] 命令替换
来源：http://dali.andypj.xyz/Article/details/gt2jflqraxt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhptfxn.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gt2gznsqimz.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gt2mcinkpsg.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gt2whahywcl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhongyouzk.top/Article/details/gt2hhdgpfsj.html

[R29] 定义函数
来源：http://dali.ivvv.top/Article/details/gt2oooprxej.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gt2teiziqov.html

[R30] 函数返回状态码
来源：http://dali.ybcxt.top/Article/details/gt2tsxcgvgj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.mhx1999.top/Article/details/gt2kfuwvzzf.html

[R31] 局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubwdryks.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gt2rzuuyqkg.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfgmxosz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2glqyfeuv.html

[R33] 捕获错误并提示行号
来源：http://dali.nwbrower.top/Article/details/gt2ctxjbfxn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gt2xajpfudi.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gt2xiwxdkyr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gt2eewgirhx.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gt2tqapedgm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258.top/Article/details/gt2lolvwgsg.html

[R36] 并发执行多个任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jsrbfzrb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ehwqpu.com/Article/details/gt2ctanphpc.html

[R37] 把输出赋给变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfmngjyc.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yesfolds.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gt2rztwatls.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gt2aqnyddoe.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gt2hdlaqfzj.html

cmd > out.log 2>&1
来源：http://dali.c1oappe.top/Article/details/gt2zqqtbycj.html

[R40] 追加写日志
来源：http://dali.ybcxt.top/Article/details/gt2rfqgzdsu.html

echo "log" >> out.log
来源：http://dali.316326.xyz/Article/details/gt2gtyhxsvj.html

[R41] 丢弃输出
来源：http://dali.nanxuanxn.top/Article/details/gt2gkdpnhkv.html

cmd >/dev/null 2>&1
来源：http://dali.birdmap.top/Article/details/gt2zlrsocly.html

[R42] 输入重定向
来源：http://dali.jiagoushi.top/Article/details/gt2yeveehmv.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gt2ainznaoh.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gt2huknwxpe.html

find . -name "*.log" -type f
来源：http://dali.shzxlz.cn/Article/details/gt2wknxmxwq.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gt2hxgmjgco.html

find . -mtime -7 -type f
来源：http://dali.bjfxy.top/Article/details/gt2ljttnbxg.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gt2yzfmqdvl.html

find . -name "*.tmp" -delete
来源：http://dali.quarkkingdee.top/Article/details/gt2nzdzsfzf.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gt2dhipmxxr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dashuyun.cn/Article/details/gt2rvyqzkbd.html

[R47] sed 单行替换
来源：http://dali.316326.xyz/Article/details/gt2gwaxoxhp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangdashe.top/Article/details/gt2mxnpjndz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrghgih.html

awk '{print $1, $3}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2yggpaejx.html

[R49] awk 带条件
来源：http://dali.hfpthk.cn/Article/details/gt2uspyfsme.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpfyuefv.html

[R50] awk 求和
来源：http://dali.jinqigfzy.top/Article/details/gt2muikzraz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2eemxmhpv.html

[R51] 排序去重取前几
来源：http://dali.yuxming.cn/Article/details/gt2zoxlrbmm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhengqikj.top/Article/details/gt2axghunyl.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gt2uhczzeuz.html

wc -l a.txt
来源：http://dali.yonumen.top/Article/details/gt2ihteeedn.html

[R53] 查看文件头与实时尾
来源：http://dali.tianlin.xyz/Article/details/gt2vqjactxx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gt2ajmbuayu.html

[R54] 比较两个文件
来源：http://dali.hfpthk.cn/Article/details/gt2ghxwnjmt.html

diff a.txt b.txt
来源：http://dali.yj20258888.top/Article/details/gt2jdcpaxqw.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gt2ypvxejkh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.meibo888.top/Article/details/gt2kiebapvm.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gt2opeqxyph.html

scp file user@host:/path/
来源：http://dali.quarkkingdee.top/Article/details/gt2uyggceaz.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gt2vleakexc.html

ssh user@host 'uptime'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abcmsnxx.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gt2cmcbtgul.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gt2axbkswwv.html

[R59] 发 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gt2repbovkd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gt2bhxmmgmf.html

[R60] 只看 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2jfxrjdmv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.316326.xyz/Article/details/gt2onlfgdhs.html

[R61] 磁盘占用
来源：http://dali.jinqigfzy.top/Article/details/gt2hhlcvehj.html

df -h;  du -sh *
来源：http://dali.zhoulong.xyz/Article/details/gt2qzgxknxr.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gt2zfadklwp.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gt2ljsfbfnt.html

[R63] 内存与进程
来源：http://dali.yvedp.cn/Article/details/gt2mwuoeyjc.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gt2pbbkpjvp.html

[R64] 结束进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcmveqzf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gt2vrpmokpe.html

[R65] 查看端口占用
来源：http://dali.chenzaomai.com/Article/details/gt2kwexlrqg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ppjwa.cn/Article/details/gt2ljmsetpc.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gt2xaeiquzw.html

crontab -e;  crontab -l
来源：http://dali.c1oappe.top/Article/details/gt2mhdxagsq.html

[R67] 生成随机十六进制串
来源：http://dali.smart0.xyz/Article/details/gt2yjjpcbkc.html

openssl rand -hex 16
来源：http://dali.quarkkingdee.top/Article/details/gt2vsptqtnq.html

[R68] 计算文件校验值
来源：http://dali.hnxiangtu.top/Article/details/gt2qvktzqdw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.smart0.xyz/Article/details/gt2ehjpaqhe.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gt2qaxdzroh.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gt2imfbuoww.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gt2crzybtim.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njrcdjah.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gt2ipqlmyyj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gt2fllmhgjc.html

[R72] 等待端口就绪
来源：http://dali.redwolf501.top/Article/details/gt2vfjzejms.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtzgujpy.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gt2rbyfixqe.html

split -l 1000 big.log part_
来源：http://dali.ivvv.top/Article/details/gt2sgbfhsmb.html

[R74] 批量重命名
来源：http://dali.cqqwz.cn/Article/details/gt2vtebiawa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fzhhl.top/Article/details/gt2qbjidfgr.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2syipirkv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gt2nlaknlyj.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gt2twpbeabm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gt2ckghmuwq.html

[R77] 读取用户输入
来源：http://dali.yanxiufei.cn/Article/details/gt2kbsccwga.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gt2suzcgjwd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgxrsvw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dashuyun.cn/Article/details/gt2ftaxkdjx.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xixkfujf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjfniixx.html

[R80] 查看脚本执行耗时
来源：http://dali.snrcjt.cn/Article/details/gt2dfbjesfi.html

time ./run.sh
来源：http://dali.tianlin.xyz/Article/details/gt2rusnjgsd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2lphoflbs.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gt2pfeyeflo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2vrvlhvnz.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2xxqyjjno.html

#include <stdio.h>
来源：http://dali.aizwys.cn/Article/details/gt2ytohnusl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gt2dvpwjswh.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gt2pfkodfys.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gt2bgbouubu.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gt2efasbjed.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gt2pqvniwlb.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gt2ngyjasha.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.andypj.xyz/Article/details/gt2mmpvkohc.html

[S05] C：字符串长度
来源：http://dali.ehwqpu.com/Article/details/gt2dilddncg.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gt2nqrqtmii.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gt2bxorqfvq.html

strcmp(a, b) == 0
来源：http://dali.nwbrower.top/Article/details/gt2ffbdgopz.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gt2semrxtpn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gt2rhetcvcm.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gt2ggkthvts.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuanzx.com/Article/details/gt2pculebsc.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gt2crrmqgdw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fengsongda.top/Article/details/gt2lycazmsv.html

[S10] C：指针与解引用
来源：http://dali.cucudq.cn/Article/details/gt2mdgbaqrq.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gt2rbmofjkd.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2rqaryjum.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gt2ykdwouek.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gt2dybpajoy.html

fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gt2dzrcldnk.html

[S12] C：写文件
来源：http://dali.shuidangran.top/Article/details/gt2uakpvaol.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gt2twohhdez.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gt2eogazyzp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gt2bdxgywvd.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gt2fxjlvcxl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xogfkqxd.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gt2rcaowdxr.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gt2mruwfpkr.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gt2ywpjastd.html

x |= (1 << 3);
来源：http://dali.iojbl.cn/Article/details/gt2poeqwqrf.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gt2clmubofq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sxryk.cn/Article/details/gt2asuzwemf.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sykvsgzz.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gt2exabxulo.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gt2attrzndm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gt2jgsgnmnl.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gt2rlbsqilg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gt2qcpdrsll.html

[S21] C：字符类别判断
来源：http://dali.yueranfly.top/Article/details/gt2pnvqknxd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.snrcjt.cn/Article/details/gt2svtbvyxv.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gt2lntrdjst.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gt2jqqpfnkc.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gt2qdnoaeoi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gt2vqqoeeod.html

[S24] C：获取本地时间
来源：http://dali.cdnleiting.top/Article/details/gt2pdwojlda.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gt2bpktkclk.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gt2xrpwgvqc.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gt2knvbycil.html

[S26] C：内存清零
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctygwnwn.html

memset(a, 0, sizeof a);
来源：http://dali.haohaochexian.top/Article/details/gt2eqhokqgo.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gt2iiaxyaft.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gt2nywkrprp.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrwsehhz.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gt2ukvhkxgm.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gt2jvswhstk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gt2yldoygdz.html

[S30] C：头文件保护
来源：http://dali.jinqigufen.top/Article/details/gt2ajanvvjk.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gt2xbyyvnac.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpdrrarg.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gt2juandlxf.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2aburhrri.html

#include <iostream>
来源：http://dali.zhongyouzk.top/Article/details/gt2nlyvpxag.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xziqi.cn/Article/details/gt2xbelmolz.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gt2hzsvfvnk.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gt2aehthhyh.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gt2hxhzymai.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2eylhookb.html

[S34] C++：遍历 vector
来源：http://dali.yj20258.top/Article/details/gt2aajzrypn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cdnleiting.top/Article/details/gt2rzwnneve.html

[S35] C++：map
来源：http://dali.fengsongda.top/Article/details/gt2iddmuctq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2yyjvfslu.html

[S36] C++：unordered_map
来源：http://dali.daxiang520.top/Article/details/gt2rdjaaglt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2lafvffhu.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gt2ignqogdg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gt2xtizqvmi.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gt2lfltsmmi.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gt2wywzpwrp.html

[S39] C++：自定义比较器排序
来源：http://dali.jianghu66.top/Article/details/gt2pmylwiax.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gt2qcgdxdqe.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gt2cyjjhuac.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gt2tzyuihxl.html


<!-- 参考信息 -->