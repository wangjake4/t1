代发 wailian999

ANALYZE TABLE users;
来源：http://dali.shuidangran.top/Article/details/gt2rfrmjhju.html

[Q71] 查看建表语句
来源：http://dali.sweek.top/Article/details/gt2cqoivupa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jyoumei.cn/Article/details/gt2vivvkdkd.html

[Q72] 查看索引
来源：http://dali.chenzaomai.com/Article/details/gt2ibdyjxfu.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2msyfthxj.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gt2yqxphgmq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gt2asgpmxeg.html

[Q74] 强制使用索引
来源：http://dali.jianghu66.top/Article/details/gt2zplsqjsc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbtoowns.html

[Q75] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2xulayszb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcalveix.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gt2nzfdkntb.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gt2fvopcyod.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gt2niahfvmc.html

[Q77] 时间加减
来源：http://dali.ehwqpu.com/Article/details/gt2xsuambyt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gt2luqmoloh.html

[Q78] 当前时间
来源：http://dali.shzxlz.cn/Article/details/gt2delmamja.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuanzhike.top/Article/details/gt2dmhfbijh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaufhvi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daxiang520.top/Article/details/gt2qxzhouoq.html

[Q80] 字符串截取
来源：http://dali.jqgfzy.top/Article/details/gt2zocipolr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2ndpdfaqi.html

[Q81] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gt2htdfmqpo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sweek.top/Article/details/gt2ucsznmhy.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppfezmhg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gialvepz.html

[Q83] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gt2ietjaybh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srohpegm.html

[Q84] 去除首尾空格
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rldwhgpw.html

SELECT TRIM(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2wbobjdms.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gt2afquobdu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gt2furquksh.html

[Q86] 读取 JSON 字段
来源：http://dali.jianghu66.top/Article/details/gt2ntidsolh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gt2cyuqfnzb.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gt2gtbchzdq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gt2xrxlxtor.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gt2yqkqvqqw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gt2yacwipez.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2nspwiega.html

[Q89] 判断表是否存在
来源：http://dali.chenzaomai.com/Article/details/gt2kyqrowtn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangdashe.top/Article/details/gt2mjsdmtcq.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gt2mlajwyhu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.316326.xyz/Article/details/gt2vvnkizzo.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2tfdvibjj.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhdxhhrf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2tivpzmbg.html

[R01] shebang 与严格模式
来源：http://dali.xziqi.cn/Article/details/gt2opofhwwg.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gt2vfevdicj.html

set -euo pipefail
来源：http://dali.fzhhl.top/Article/details/gt2vjbfopju.html

[R02] 变量赋值与使用
来源：http://dali.wangdashe.top/Article/details/gt2bnqtmylr.html

name="Tom"; echo "$name"
来源：http://dali.jlsjyb.cn/Article/details/gt2nblhuklj.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gt2jjukuibl.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gt2vkauoosq.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gt2ssppuhuk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.iojbl.cn/Article/details/gt2wjchmwtp.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gt2fnwcnkis.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gt2tikkvdqa.html

[R06] 判断命令是否存在
来源：http://dali.hysaishi.cn/Article/details/gt2wltyadao.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hbdrwqer.html

[R07] if 判断文件
来源：http://dali.dianchejie.cn/Article/details/gt2yqkqftno.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2okuphrna.html

[R08] 数值比较
来源：http://dali.daxiang520.top/Article/details/gt2wqnyfurz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2liswzhlu.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gt2ddecsxiz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2tgorxhfq.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gt2ygfrrqhw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2axtruywi.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gt2nuweapzo.html

case "$1" in
来源：http://dali.yuanzhike.top/Article/details/gt2qdozmsdb.html

start) echo "启动" ;;
来源：http://dali.zycfv.cn/Article/details/gt2pudyxoba.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2xlarsyjb.html

*)     echo "未知命令" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekzhxrea.html

esac
来源：http://dali.zhixingplan.top/Article/details/gt2gegzidow.html

[R12] for 遍历文件
来源：http://dali.hnxiangtu.top/Article/details/gt2abbunoiw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2awadxfvv.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gt2cushihzr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gt2klcrgbzs.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gt2xczdfuuo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gt2tynnfesh.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2sehzvwgb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gt2fezapbcg.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bsuyppqv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gt2baohvolt.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gt2fvbpktmi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.vqdsnc.cn/Article/details/gt2ervtlerx.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gt2dcndxrsk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gt2iydjkyef.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ucwjbaie.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2zqktmija.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gt2ysjcgzpm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gt2npezgpkf.html

[R21] 字符串长度
来源：http://dali.jqgfzy.top/Article/details/gt2ixplsdcg.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gt2caucsefi.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gt2scjbogwt.html

echo "${s:0:5}"
来源：http://dali.chenzaomai.com/Article/details/gt2dntdqdgp.html

[R23] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gt2hyufiqqy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aibaodan.cn/Article/details/gt2wdgukbjh.html

[R24] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gt2pngceljx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gt2khhtimxl.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gt2msjkvzhy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gt2nwgeubdt.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gt2tcfwzgmk.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gt2nyqeizwt.html

[R27] 算术展开
来源：http://dali.cqqwz.cn/Article/details/gt2ykitkxfb.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gt2lxggrxic.html

[R28] 浮点运算
来源：http://dali.sxryk.cn/Article/details/gt2nrcfgmuj.html

echo "scale=2; 10/3" | bc
来源：http://dali.hfpthk.cn/Article/details/gt2ejwsdylt.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gt2gdytqwbt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwicofkc.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gt2vexydsfm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daria6918.cn/Article/details/gt2axmseqvn.html

[R31] 局部变量
来源：http://dali.andypj.xyz/Article/details/gt2rkcydnwb.html

f() { local x=1; echo "$x"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2wadrsmkt.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gt2qbksbmlj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gt2lptsmupq.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gt2wrtxhhrp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hfpthk.cn/Article/details/gt2cieaxczj.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gt2hkduiqkx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gt2akvkmyxp.html

[R35] 后台执行并等待
来源：http://dali.9152youxi.cn/Article/details/gt2jsrjyfee.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sweek.top/Article/details/gt2zvvqyaak.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gt2appgeztz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gt2fmxgjhrl.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gt2mixmmkgp.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gt2ylsbwtof.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gt2qlabmnrr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gt2eekjmbzv.html

[R39] 重定向标准输出与错误
来源：http://dali.zdqjudy.top/Article/details/gt2tumpsqar.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gt2ruxhudao.html

[R40] 追加写日志
来源：http://dali.guowangkeji.top/Article/details/gt2mggtajdj.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2eeheeayp.html

[R41] 丢弃输出
来源：http://dali.bjfxy.top/Article/details/gt2ncilfeez.html

cmd >/dev/null 2>&1
来源：http://dali.yuanzhike.top/Article/details/gt2epybfnny.html

[R42] 输入重定向
来源：http://dali.xuanzx.com/Article/details/gt2ahhjgazu.html

wc -l < a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2hcfnbrds.html

[R43] 按名字查找文件
来源：http://dali.jqgufenzy.top/Article/details/gt2mksffytx.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gt2mquoxkzp.html

[R44] 按修改时间查找
来源：http://dali.xylfe.cn/Article/details/gt2ksfdjktt.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gt2nkfbkvfq.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gt2agqbkvpw.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gt2osaunhct.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gt2bilocavv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gt2cmgkvjss.html

[R47] sed 单行替换
来源：http://dali.guannengcc.top/Article/details/gt2ecvzridt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2nsjwjnck.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqtvznsx.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gt2gdwejxxo.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gt2eqrtnlsu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gt2sfzeefcy.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gt2digldxvc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2yqojpbfl.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gt2kxupwbni.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuanzx.com/Article/details/gt2ohfyfvdz.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gt2bknlxggv.html

wc -l a.txt
来源：http://dali.gzhubu.top/Article/details/gt2mafevhzg.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gt2xrkhpkbh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gt2gvwhfkvy.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fobqlszs.html

diff a.txt b.txt
来源：http://dali.ybcxt.top/Article/details/gt2rhktcftc.html

[R55] 压缩与解压
来源：http://dali.aibaodan.cn/Article/details/gt2yqxmkerk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gt2dotjmtiy.html

[R56] 远程拷贝
来源：http://dali.yonumen.top/Article/details/gt2qxrclemj.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gt2vrgyzvfh.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruaypvek.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gt2weuvqzcl.html

[R58] 下载文件
来源：http://dali.daria6918.cn/Article/details/gt2oaqiwthf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.316326.xyz/Article/details/gt2hobdmzhc.html

[R59] 发 POST JSON
来源：http://dali.bjfxy.top/Article/details/gt2smdpydwr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gt2nbzkjwqw.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gt2mgrydxlo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.316326.xyz/Article/details/gt2xrigfgpd.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gt2rjdkkior.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gt2kshalzer.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gt2nftedfdi.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258888.top/Article/details/gt2dzgjfpvg.html

[R63] 内存与进程
来源：http://dali.dashuyun.cn/Article/details/gt2pdksigmd.html

free -h;  ps aux | grep nginx
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lexlevjf.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ubfwnwpj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangshuangyany.cn/Article/details/gt2inluhdrr.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkayoplm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gzhubu.top/Article/details/gt2npqhtuyv.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gt2wreotqwa.html

crontab -e;  crontab -l
来源：http://dali.fzhhl.top/Article/details/gt2ppnewnrl.html

[R67] 生成随机十六进制串
来源：http://dali.mhx1999.top/Article/details/gt2yvkbcmwj.html

openssl rand -hex 16
来源：http://dali.wangdashe.top/Article/details/gt2awgxxgzx.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gt2kevoqxiw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2rqhakckx.html

[R69] 生成随机密码
来源：http://dali.smart0.xyz/Article/details/gt2iasjsbws.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gt2cglvavje.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxbwknts.html

date +%s;  date -d @1700000000
来源：http://dali.iojbl.cn/Article/details/gt2alolrfnh.html

[R71] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2xmqepoxd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nwbrower.top/Article/details/gt2xsvbcxdc.html

[R72] 等待端口就绪
来源：http://dali.daxiang520.top/Article/details/gt2ksujsylj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gt2qpewkoai.html

[R73] 分割大日志
来源：http://dali.daria6918.cn/Article/details/gt2kdgqhrfv.html

split -l 1000 big.log part_
来源：http://dali.jinqigfzy.top/Article/details/gt2kcjynbsg.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrtmbrmi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gt2fhgbullr.html

[R75] 导出环境变量
来源：http://dali.daxiang520.top/Article/details/gt2dfalrtms.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gt2kzqvrefv.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gt2tjayhkvl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gt2nxzbtrnc.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gt2aubrrgrl.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gt2zswvwjog.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gt2jzogdgik.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gt2taiaxuli.html

[R79] 解析命令行选项
来源：http://dali.kuanghao11.cn/Article/details/gt2gtdknbpv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cheryme.top/Article/details/gt2kekgkjjy.html

[R80] 查看脚本执行耗时
来源：http://dali.pycfn.com/Article/details/gt2ihddkoeq.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gt2yehwqgrg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2wkqfznkt.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gt2efmzkhgx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfiuvwwr.html

[S01] C：Hello World
来源：http://dali.yj202588.top/Article/details/gt2awvhnymc.html

#include <stdio.h>
来源：http://dali.vqdsnc.cn/Article/details/gt2rgdaafyz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kuvdcdvn.html

[S02] C：变量与格式化输出
来源：http://dali.chenzaomai.com/Article/details/gt2maijirpm.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvpwqroz.html

[S03] C：读入整数
来源：http://dali.yj20258.top/Article/details/gt2odaejjfm.html

int x; scanf("%d", &x);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rsknjsee.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gt2iwejuvzg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gt2wnqynwcg.html

[S05] C：字符串长度
来源：http://dali.shzxlz.cn/Article/details/gt2athqloli.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gt2bannlody.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gt2gszkwwdq.html

strcmp(a, b) == 0
来源：http://dali.jinqigufen.top/Article/details/gt2benzwhin.html

[S07] C：数组遍历求和
来源：http://dali.dianchejie.cn/Article/details/gt2lyudixam.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jyoumei.cn/Article/details/gt2iwvagjli.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gt2odaozpgr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gt2svztoxeo.html

[S09] C：结构体定义与初始化
来源：http://dali.dianchejie.cn/Article/details/gt2ahyotbjt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuetiantiany.cn/Article/details/gt2xfunpxbr.html

[S10] C：指针与解引用
来源：http://dali.jiagoushi.top/Article/details/gt2zadxngna.html

int *p = &a;  *p = 5;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtdezxsm.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2yykuhihf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gt2gjokbxfe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gt2mbkovieb.html

fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gt2lcyvpulf.html

[S12] C：写文件
来源：http://dali.hysaishi.cn/Article/details/gt2pikvpodo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gt2cczdiwib.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfufzkqu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gt2yxpnjqol.html

[S14] C：枚举
来源：http://dali.yj202588.top/Article/details/gt2emnzomng.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gt2zishxxcm.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gt2ssqfrkwr.html

(double) a / b
来源：http://dali.316326.xyz/Article/details/gt2qivmhmjl.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gt2bfvvrixu.html

x |= (1 << 3);
来源：http://dali.hammf.cn/Article/details/gt2dugvjbcp.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxpxwkie.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gt2clgqubbo.html

[S18] C：命令行参数
来源：http://dali.yongpay.top/Article/details/gt2bcklduku.html

int main(int argc, char **argv)
来源：http://dali.yj20258888.top/Article/details/gt2hoouyuea.html

[S19] C：快速排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtgqnayx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gt2gmqepebl.html

[S20] C：二分查找
来源：http://dali.gotoacloud.top/Article/details/gt2mwpevhly.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gt2lgvcbbud.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gt2kuiabkcd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gt2eqkvjpfh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ipapxayk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gt2uruxmxpr.html

[S23] C：随机数
来源：http://dali.ydzc1.top/Article/details/gt2lxlftbme.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gotoacloud.top/Article/details/gt2ktsjiznu.html

[S24] C：获取本地时间
来源：http://dali.mhx1999.top/Article/details/gt2bbbwgjkl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258.top/Article/details/gt2budokqno.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gt2mylxtndv.html

memcpy(dst, src, n);
来源：http://dali.jianghu66.top/Article/details/gt2ghjxpuem.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gt2geweusrd.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gt2kfnivaka.html

[S27] C：定义常量
来源：http://dali.gaohongyu789.top/Article/details/gt2tchgsclx.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgtuwpqq.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gt2owpyxbgm.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gt2fckttelk.html

[S29] C：变参函数
来源：http://dali.gaohongyu789.top/Article/details/gt2cbxjotqv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gt2ixoattcv.html

[S30] C：头文件保护
来源：http://dali.cdnleiting.top/Article/details/gt2hatgphfr.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gt2mfomonea.html

#define X_H
来源：http://dali.svipenyu.cn/Article/details/gt2kvrjlqgn.html

#endif
来源：http://dali.hywenlv.cn/Article/details/gt2yjeppkly.html

[S31] C++：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2hhrrugui.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gt2qxuzixxy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bhwctiay.html

[S32] C++：字符串
来源：http://dali.yj20258.top/Article/details/gt2dmvagshw.html

std::string s = "hi";  s += "!";
来源：http://dali.haohaochexian.top/Article/details/gt2dgtwuurs.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gt2kbxyagmw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gt2yxkekwcn.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scevywny.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hfpthk.cn/Article/details/gt2djkigtvl.html

[S35] C++：map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fnsdayjm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gt2ctjloqtn.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gt2ytqlpgap.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2kthvgwnj.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gt2klaiefbf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cdnleiting.top/Article/details/gt2ycvrwqax.html

[S38] C++：排序
来源：http://dali.316326.xyz/Article/details/gt2yqevhwvn.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gt2tccdttwe.html

[S39] C++：自定义比较器排序
来源：http://dali.zdqjudy.top/Article/details/gt2vntlopcl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gt2shqfccod.html

[S40] C++：查找元素
来源：http://dali.pycfn.com/Article/details/gt2ufqbsedq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gt2eheatrye.html


<!-- 参考信息 -->