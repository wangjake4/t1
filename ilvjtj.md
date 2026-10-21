代发 wailian999

ANALYZE TABLE users;
来源：http://dali.yj202588.top/Article/details/gtuzbqvllc.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gtronbfwrx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gtdxyqeeom.html

[Q72] 查看索引
来源：http://dali.wangshuangyany.cn/Article/details/gtcwofjfcv.html

SHOW INDEX FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtscvbwmse.html

[Q73] 查看表状态
来源：http://dali.cheryme.top/Article/details/gtfpfdqacw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.smart0.xyz/Article/details/gtvodsdydx.html

[Q74] 强制使用索引
来源：http://dali.nanxinkj.top/Article/details/gtpylgryoz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgufenzy.top/Article/details/gtqhteuypp.html

[Q75] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtuzpxzcqe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtrepxmonh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gtvrvxdziz.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gtjihtkdbu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangshuangyany.cn/Article/details/gtbpzzhqwi.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gtooaqfaxs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dianchejie.cn/Article/details/gthfxjvwxe.html

[Q78] 当前时间
来源：http://dali.svipenyu.cn/Article/details/gthmlwldqq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinghuilouyu.cn/Article/details/gthuintdek.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gtwfemnfqj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gtdzmexbns.html

[Q80] 字符串截取
来源：http://dali.gaohongyu789.top/Article/details/gtfrfdmgen.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtcrrpwcgd.html

[Q81] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtbbqbzbvo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbsjrlym.html

[Q82] 字符长度与字节长度
来源：http://dali.zycfv.cn/Article/details/gtkiogbufp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtcspigybw.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtboycqirv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtrgluktqw.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gteomdrmhm.html

SELECT TRIM(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtrdkqwzul.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gtrdbgycey.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fengsongda.top/Article/details/gthciohzhz.html

[Q86] 读取 JSON 字段
来源：http://dali.bjfxy.top/Article/details/gtobxbmixx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gtyywvysyg.html

[Q87] JSON 字段做条件
来源：http://dali.zhoulong.xyz/Article/details/gtfhmpavta.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pycfn.com/Article/details/gtyhvjamgd.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gtszbtnhyc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtdslpfeky.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtgbiwlels.html

[Q89] 判断表是否存在
来源：http://dali.yuxming.cn/Article/details/gtqnmvlche.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258888.top/Article/details/gtgnaeuxek.html

[Q90] 生成序号列
来源：http://dali.xylfe.cn/Article/details/gtvjhitgiy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yonumen.top/Article/details/gtyndoewzg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtkuxhderv.html

R. Bash 专题
来源：http://dali.jyoumei.cn/Article/details/gtgrqjetzg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtgurpuvdl.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gtuqqlknhf.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gtdvtihayi.html

set -euo pipefail
来源：http://dali.fengsongda.top/Article/details/gtanzcxgbf.html

[R02] 变量赋值与使用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwqawwps.html

name="Tom"; echo "$name"
来源：http://dali.yj202588.top/Article/details/gtjaefyeuj.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gtonggpxww.html

readonly PI=3.14
来源：http://dali.yonumen.top/Article/details/gtxlgfxcds.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gtnqviwvdp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yvedp.cn/Article/details/gtcjxtwlcm.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gtdtpiwkll.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gtyixflzom.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gtqhpkqbbv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtbxxzaiog.html

[R07] if 判断文件
来源：http://dali.andypj.xyz/Article/details/gtjasszgtt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dianchejie.cn/Article/details/gtzbmrgdfc.html

[R08] 数值比较
来源：http://dali.ivvv.top/Article/details/gtxbcefozi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.andypj.xyz/Article/details/gtajzuqpih.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gtiydgalrr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sweek.top/Article/details/gtubycthbq.html

[R10] 正则匹配
来源：http://dali.zdqjudy.top/Article/details/gtimbwjjyh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gtehmgovhw.html

[R11] case 多分支
来源：http://dali.jinqigfzy.top/Article/details/gtumichhuz.html

case "$1" in
来源：http://dali.gogol.net.cn/Article/details/gtcponilrs.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gtkbtliqlm.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gtehbpqovu.html

*)     echo "未知命令" ;;
来源：http://dali.0kj1m.cn/Article/details/gtggxserzj.html

esac
来源：http://dali.0kj1m.cn/Article/details/gtfthezcan.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gtnyqxyfot.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sxryk.cn/Article/details/gttppwnxpm.html

[R13] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtfcdnoxsm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtncmywras.html

[R14] C 风格 for
来源：http://dali.yanxiufei.cn/Article/details/gtnemzqshp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gtzfnlvwyw.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtjddumvfz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gtmljhhlmq.html

[R16] until 等待条件
来源：http://dali.jianghu66.top/Article/details/gtwjwkqvmr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtqpfzrzxn.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gtkmobbvgd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangdashe.top/Article/details/gtavwvjvzn.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gtpntpziaj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sufxvd.cn/Article/details/gtylxtmaju.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtntflfvhd.html

echo "${#arr[@]}"
来源：http://dali.shuidangran.top/Article/details/gtrkbfbcdf.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gtgmpdiska.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.c1oappe.top/Article/details/gtzybhavrf.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gtsoradgwd.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gtcyquoejk.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gtzcmwtouq.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgduunfq.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtyewsbbxb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gttetfxdbj.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtjptkzbas.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shuidangran.top/Article/details/gtdepefbqy.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gtnvbgymrd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gtxmuxtjit.html

[R26] 命令替换
来源：http://dali.wangdashe.top/Article/details/gtrufxnbcp.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gtjwjvntgi.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gtnjhsfvca.html

echo $((1 + 2 * 3))
来源：http://dali.dianchejie.cn/Article/details/gtslnucjfv.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gtvsujykjj.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtwbgnfuyq.html

[R29] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtupniyzpn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtfzgzslto.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gtflnjqise.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gtdrjldjbz.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtzpfvrfzo.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhpcakfi.html

[R32] 参数个数校验
来源：http://dali.hysaishi.cn/Article/details/gtiectxmrw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcfivdyvp.html

[R33] 捕获错误并提示行号
来源：http://dali.haohaochexian.top/Article/details/gtynwrrnsg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shangyingyoupin.top/Article/details/gtbjecwxdx.html

[R34] 退出时清理
来源：http://dali.jqgfzy.top/Article/details/gtvrtetmho.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gtyrjkihnq.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gtrfaozwvx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gtjzogbjss.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gtdurmhuii.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cucudq.cn/Article/details/gtnubxaehc.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gtifbyzrws.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlqthzwd.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gtgodiyzyp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gtznlmoydy.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gtkehbqtze.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtjntdnnck.html

[R40] 追加写日志
来源：http://dali.yanxiufei.cn/Article/details/gtzhsftxrw.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gtalirlcvn.html

[R41] 丢弃输出
来源：http://dali.shuidangran.top/Article/details/gtpebxdpgq.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gtvtyvuhhe.html

[R42] 输入重定向
来源：http://dali.gogol.net.cn/Article/details/gthszhvmnm.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gtefbteocr.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gtithoajkj.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gtwezemepx.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gtlhdxxitv.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gtutxwppjb.html

[R45] 批量删除
来源：http://dali.sufxvd.cn/Article/details/gtngilazbt.html

find . -name "*.tmp" -delete
来源：http://dali.gaohongyu789.top/Article/details/gtjtdcvvyh.html

[R46] 递归替换文件内容
来源：http://dali.zhoulong.xyz/Article/details/gtmanydmvc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gtdumsbryl.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gtqfksqpmk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtszpttddm.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefbaxfxu.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gtebcolqqg.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gtfmvoiibz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fzhhl.top/Article/details/gtgspxzrds.html

[R50] awk 求和
来源：http://dali.zhengqikj.top/Article/details/gtckigbonb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtnwjaewsu.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdtiveby.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gtcmhdbmwi.html

[R52] 统计行数
来源：http://dali.zhoulong.xyz/Article/details/gtjrdieoma.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gtiqapxcok.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gtbilegyxz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shangyingyoupin.top/Article/details/gtliigpinw.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gtdanosayn.html

diff a.txt b.txt
来源：http://dali.hammf.cn/Article/details/gtdqesyevx.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gtmiiwzbqr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gthjfwzroa.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtiyktylyc.html

scp file user@host:/path/
来源：http://dali.kuanghao11.cn/Article/details/gtprilayle.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtsvsyftob.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gtgbwrbldb.html

[R58] 下载文件
来源：http://dali.nanxuanxn.top/Article/details/gtzpydyyri.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zdqjudy.top/Article/details/gttfluvgiz.html

[R59] 发 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gthpsbxnrv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gtgsxuooyn.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtcwtiufim.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gtxvdlltdh.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gtwxsqesee.html

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gtrgbgndxg.html

[R62] 找最占空间的文件
来源：http://dali.jyoumei.cn/Article/details/gtxcmvwsmq.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigufen.top/Article/details/gtvppvvzpp.html

[R63] 内存与进程
来源：http://dali.chenlongwang.top/Article/details/gtevtmyrcu.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gtevcyehyc.html

[R64] 结束进程
来源：http://dali.sufxvd.cn/Article/details/gtzzcyvkpm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jyoumei.cn/Article/details/gtxurxcgdk.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gtxwhqrpua.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gtqkloayyj.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gtcycwhnli.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gtjalnkyil.html

[R67] 生成随机十六进制串
来源：http://dali.smart0.xyz/Article/details/gtzxfgrrlb.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gtffwonaxs.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gtpkpimqes.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gtbflaxnen.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gtvdbidowr.html

head -c 16 /dev/urandom | base64
来源：http://dali.guowangkeji.top/Article/details/gtvornzyru.html

[R70] 时间戳与互转
来源：http://dali.xinyue.icu/Article/details/gtvrlcjqwe.html

date +%s;  date -d @1700000000
来源：http://dali.dianchejie.cn/Article/details/gtiuvlsgru.html

[R71] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtzcdlospl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtepidvcxt.html

[R72] 等待端口就绪
来源：http://dali.zycfv.cn/Article/details/gtnfmxaxuc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtmkvflhwh.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gtrqcoolku.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtrqpyrdgw.html

[R74] 批量重命名
来源：http://dali.andypj.xyz/Article/details/gthzyzpvpn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtwqpvciuv.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gttnngixhk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gtenroblqo.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gtqltilflu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtqreumwfz.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gtgcauzqvc.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gtqezidflz.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gtemkhjiev.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxujmhod.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gtalienalc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yvedp.cn/Article/details/gtawjlfuer.html

[R80] 查看脚本执行耗时
来源：http://dali.havefunace.top/Article/details/gtcjvpmqzs.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gtjvtztzgx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtnallufcs.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxlmyovi.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtnlbzjnqt.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtvmouqury.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtblsnyqvv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigufen.top/Article/details/gtukfhexqu.html

[S02] C：变量与格式化输出
来源：http://dali.zhixingplan.top/Article/details/gttuhnwpti.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gtglnrisnt.html

[S03] C：读入整数
来源：http://dali.havefunace.top/Article/details/gtwjjzdkoj.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gtskblrwua.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtuywokfvo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtgwwirlhc.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtseljxkyb.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gtbkbtgkip.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gteoiaeqpd.html

strcmp(a, b) == 0
来源：http://dali.wangdashe.top/Article/details/gtcdfhjofj.html

[S07] C：数组遍历求和
来源：http://dali.9152youxi.cn/Article/details/gtkciutpbl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwoodkwk.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gtvzunjghv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gtiguyxlam.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgfzy.top/Article/details/gteqajoybj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gtiboakmkh.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gtncusrqkp.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gtcjumajkx.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtexljqctp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gtsxnnhsfo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sufxvd.cn/Article/details/gtumcskdeo.html

fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtpvsomcjp.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtwnzmvneh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xinyue.icu/Article/details/gtpkdygcxe.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gtjitvwhgm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gtvkdmwohu.html

[S14] C：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtdqaluyor.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuetiantiany.cn/Article/details/gtqvbeygel.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuuduyjp.html

(double) a / b
来源：http://dali.316326.xyz/Article/details/gtzkwxydlc.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgpdwwxd.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gtbwbkexwo.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtbqlggutw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cqqwz.cn/Article/details/gttvczvrfy.html

[S18] C：命令行参数
来源：http://dali.xylfe.cn/Article/details/gtxulbavvv.html

int main(int argc, char **argv)
来源：http://dali.daria6918.cn/Article/details/gtsmnnmujs.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gtqjqyqaiz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gtisxdvfoj.html

[S20] C：二分查找
来源：http://dali.9152youxi.cn/Article/details/gtksocxpxx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gtmameicey.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gthprhtohy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zycfv.cn/Article/details/gtjsjqonuz.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gtkarvbnjx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gtifvzvllp.html

[S23] C：随机数
来源：http://dali.hfpthk.cn/Article/details/gtzlbjnvfu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhoulong.xyz/Article/details/gttczujuah.html

[S24] C：获取本地时间
来源：http://dali.sweek.top/Article/details/gtfmayvedv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.316326.xyz/Article/details/gtvvushala.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gtfzdrjsny.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gtvcbuqnip.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gtmbhvzsog.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gttazahnhy.html

[S27] C：定义常量
来源：http://dali.zhengqikj.top/Article/details/gtgzvdnbtv.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtvilposev.html

[S28] C：静态变量
来源：http://dali.hywenlv.cn/Article/details/gtydrugsij.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gtagrpxgcv.html

[S29] C：变参函数
来源：http://dali.cashguo.top/Article/details/gtfilfuidr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gtgybzdkeb.html

[S30] C：头文件保护
来源：http://dali.kuanghao11.cn/Article/details/gtfbtkkccz.html

#ifndef X_H
来源：http://dali.yueranfly.top/Article/details/gtpjraewqh.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gtocdcuodj.html

#endif
来源：http://dali.shuidangran.top/Article/details/gtppdeweeg.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtslcankka.html

#include <iostream>
来源：http://dali.wangdashe.top/Article/details/gtcaxsiinc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cashguo.top/Article/details/gtugtblrrz.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtameveaal.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gtvvetopci.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gtnxsqrvvi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guannengcc.top/Article/details/gtogcgonqa.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gtuutkkols.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fengsongda.top/Article/details/gtyqpuwekn.html

[S35] C++：map
来源：http://dali.smart0.xyz/Article/details/gtvoniuscb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtwdfpmzcm.html

[S36] C++：unordered_map
来源：http://dali.0kj1m.cn/Article/details/gtjyzuhtvp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtxjbisumu.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gtakrwalea.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daxiang520.top/Article/details/gtqqyadaus.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gtqlszffsn.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gtwhzxhgkr.html

[S39] C++：自定义比较器排序
来源：http://dali.yonumen.top/Article/details/gtcgzceytb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gtqzqweaci.html

[S40] C++：查找元素
来源：http://dali.feifeiyinyue.top/Article/details/gtlukkpdzf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gtdmaxrdxm.html


<!-- 参考信息 -->