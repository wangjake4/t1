代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gtufvzvvnn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tianlin.xyz/Article/details/gtaqhkvtkc.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gttjilagsz.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gtvcbqeqyd.html

ROLLBACK TO sp1;
来源：http://dali.yuxming.cn/Article/details/gtybimboyj.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gtfbwjcoso.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gtcuifyejo.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gtnfrviuyn.html

ANALYZE TABLE users;
来源：http://dali.sufxvd.cn/Article/details/gtnpqyhrmp.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gtbrmqorgu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gtjpcfnbmh.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gtrsezgbtu.html

SHOW INDEX FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtvzkcypgd.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gtafhtilnl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gtyxnmlrjo.html

[Q74] 强制使用索引
来源：http://dali.guannengcc.top/Article/details/gtogvemdey.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.andypj.xyz/Article/details/gtxkvslrvy.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtkmnlmwpw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gtmxtdxigf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.vqdsnc.cn/Article/details/gtcwbsmspi.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gtwjoleold.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.vqdsnc.cn/Article/details/gtbdjlmyao.html

[Q77] 时间加减
来源：http://dali.nwbrower.top/Article/details/gtrydxkdcj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gtffsgjtfu.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtgbpykkuq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofynzxcl.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtaovlfgjo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sxryk.cn/Article/details/gtiehasvrc.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gtkcjyhzhq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtdwsgurgp.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtamdfkumr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sxryk.cn/Article/details/gtalyzqeta.html

[Q82] 字符长度与字节长度
来源：http://dali.haohaochexian.top/Article/details/gtbpwfybtc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtwasktldc.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gteeudhvjo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtzjaltkzb.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gtablutqfm.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtarxxrpcu.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhjoafyy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gtuuqhpsbu.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gtwcoweqen.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xziqi.cn/Article/details/gtofbfpafm.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gtgmaicidc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cheryme.top/Article/details/gtcpsuuvti.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gtjvvrlevm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gtinkettig.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shuidangran.top/Article/details/gtujpowkkb.html

[Q89] 判断表是否存在
来源：http://dali.hywenlv.cn/Article/details/gtjbepdxqa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtqypmoriz.html

[Q90] 生成序号列
来源：http://dali.pycfn.com/Article/details/gtfxdwzbim.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gtzvurkpoz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthohmrbmn.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gtpahtdlse.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtvhxauixt.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gtktyjnjyi.html

#!/usr/bin/env bash
来源：http://dali.xuanzx.com/Article/details/gtvzkngpel.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gtgmeymdbv.html

[R02] 变量赋值与使用
来源：http://dali.ppjwa.cn/Article/details/gtcjtcoszi.html

name="Tom"; echo "$name"
来源：http://dali.vqdsnc.cn/Article/details/gtwrxeqzks.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gtawvjhspb.html

readonly PI=3.14
来源：http://dali.cucudq.cn/Article/details/gtglwhthht.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gttcshrpbp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sysykeji.top/Article/details/gtiykuhcpy.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gtbrhhhdwj.html

name="${1:-default}"
来源：http://dali.pengpengdd.cyou/Article/details/gthemustrz.html

[R06] 判断命令是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gtppxnycel.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtiqjwpxvr.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhbykuep.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aizwys.cn/Article/details/gtvlqdfpyp.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gtvmjjnbuj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aizwys.cn/Article/details/gtyluchgqc.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtefwauoef.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gtgqauybdo.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gteixaacpy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nwbrower.top/Article/details/gtcndvpowi.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gttkhstpfd.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gtsczvadux.html

start) echo "启动" ;;
来源：http://dali.xziqi.cn/Article/details/gtfqmkrqcc.html

stop)  echo "停止" ;;
来源：http://dali.c1oappe.top/Article/details/gtwrbuevdr.html

*)     echo "未知命令" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujixuias.html

esac
来源：http://dali.fengsongda.top/Article/details/gtzisfuouk.html

[R12] for 遍历文件
来源：http://dali.havefunace.top/Article/details/gtilairgzx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nwbrower.top/Article/details/gtlwzqllxg.html

[R13] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gtageksqmg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtzchmpbbq.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gtbtflryqu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gtihvfgatv.html

[R15] while 逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtatvtosco.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jlsjyb.cn/Article/details/gtbgkttjlu.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gtelverkye.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtjxbyckue.html

[R17] 数组定义与取值
来源：http://dali.xuanzx.com/Article/details/gtybbsnqrg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtumessdik.html

[R18] 遍历数组
来源：http://dali.zdqjudy.top/Article/details/gtdcmwcmgs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gtbagjlvxm.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gtvbwqfwyj.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gtkzitxqlg.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gtrlnljres.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gtvzuaiaee.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtgxhqvlko.html

echo "${#s}"
来源：http://dali.iojbl.cn/Article/details/gtmysqicfd.html

[R22] 截取子串
来源：http://dali.ivvv.top/Article/details/gtcjsnehkq.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gtvnjumomi.html

[R23] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtqzqlbzpg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fengsongda.top/Article/details/gtsuhjekwl.html

[R24] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtcrnbbcpf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gtthkhjzzm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zdqjudy.top/Article/details/gtssnhfbux.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.quarkkingdee.top/Article/details/gtwgridgeh.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupftoxzh.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gtxuwghtrl.html

[R27] 算术展开
来源：http://dali.aizwys.cn/Article/details/gtqvfieoob.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gtanulffbw.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gtjlvueysb.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtrtgnqore.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gtvpviyzqp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gtrnpvidzc.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gtjmvadojd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gtxfwdnwbu.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtemijhffq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gtjtmdaszd.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gtzbkixnzl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtijuombmx.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258888.top/Article/details/gtubyhrqaq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.vqdsnc.cn/Article/details/gttnlhbgke.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gtntofjfog.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtoixjrure.html

[R35] 后台执行并等待
来源：http://dali.hnqzz.top/Article/details/gtiarzxbcl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gtdmhcgpcd.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gtoslsonxr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenzaomai.com/Article/details/gtflsyeknv.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gtlwtxykls.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gtmhfljzie.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gtefkcjybg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgufenzy.top/Article/details/gtwafdsqcg.html

[R39] 重定向标准输出与错误
来源：http://dali.cdnleiting.top/Article/details/gtylsdohyb.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtynzepoyr.html

[R40] 追加写日志
来源：http://dali.ydzc1.top/Article/details/gtfxhcodaa.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gtbhmkmnue.html

[R41] 丢弃输出
来源：http://dali.9152youxi.cn/Article/details/gttfvsbgmq.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gtxcyjzpkq.html

[R42] 输入重定向
来源：http://dali.9152youxi.cn/Article/details/gtymevcmyb.html

wc -l < a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtblzxlwge.html

[R43] 按名字查找文件
来源：http://dali.gzhubu.top/Article/details/gtzuncxabs.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gtdhluorsd.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gtmhtocnyj.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gtuhqujfjm.html

[R45] 批量删除
来源：http://dali.zycfv.cn/Article/details/gtxlodyvmn.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gtwgpxnbol.html

[R46] 递归替换文件内容
来源：http://dali.sysykeji.top/Article/details/gtykjllqwx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gtrmnwviem.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gtvldywozj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gthrisyznf.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gtyfyfgpxx.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtpkiskulr.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtguphvboc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dashuyun.cn/Article/details/gtrxqbeycy.html

[R50] awk 求和
来源：http://dali.sxryk.cn/Article/details/gtptbvxcwm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkbqczyd.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddgrjagi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gtyazdgnqm.html

[R52] 统计行数
来源：http://dali.hywenlv.cn/Article/details/gtjvylspwq.html

wc -l a.txt
来源：http://dali.xylfe.cn/Article/details/gtthyteqzg.html

[R53] 查看文件头与实时尾
来源：http://dali.jyoumei.cn/Article/details/gtlxdmndbf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gtdjhoslzd.html

[R54] 比较两个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtlwcrpwzb.html

diff a.txt b.txt
来源：http://dali.ivvv.top/Article/details/gtwigcroxm.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gtczbiqjqd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.snrcjt.cn/Article/details/gtfeylquen.html

[R56] 远程拷贝
来源：http://dali.shzxlz.cn/Article/details/gtysjxslgm.html

scp file user@host:/path/
来源：http://dali.ivvv.top/Article/details/gtzokdrrqo.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtqindvauo.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gtvblvmcqe.html

[R58] 下载文件
来源：http://dali.0kj1m.cn/Article/details/gtlqzfpzzu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gtiauibpty.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtnagpafuz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gotoacloud.top/Article/details/gtanimrpvd.html

[R60] 只看 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtdrbrvqoi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gtunyhvfuz.html

[R61] 磁盘占用
来源：http://dali.jlsjyb.cn/Article/details/gtggpgyrip.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gtjwifaxnf.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gtzidpwknv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gtwgbzoxye.html

[R63] 内存与进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgpunwvj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gtbcxmarsc.html

[R64] 结束进程
来源：http://dali.yuxming.cn/Article/details/gtacgfnsan.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gtknsfbgsx.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gteczrthhn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gtznuoitdg.html

[R66] 定时任务
来源：http://dali.xylfe.cn/Article/details/gtfkiwxvxh.html

crontab -e;  crontab -l
来源：http://dali.jqgufenzy.top/Article/details/gtaedmlvxr.html

[R67] 生成随机十六进制串
来源：http://dali.shzxlz.cn/Article/details/gtyvltxblo.html

openssl rand -hex 16
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpxwhgyv.html

[R68] 计算文件校验值
来源：http://dali.gogol.net.cn/Article/details/gtmqyvsstq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gtgjrpxqhb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gtsijwtzxs.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gtpqyzqhqe.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gtgdijqrnw.html

date +%s;  date -d @1700000000
来源：http://dali.fzhhl.top/Article/details/gtmryuwsvv.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtnvqviccm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sxryk.cn/Article/details/gtowpnwcvl.html

[R72] 等待端口就绪
来源：http://dali.jlsjyb.cn/Article/details/gtctajffvv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gttkvekojx.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gtcnjdeuep.html

split -l 1000 big.log part_
来源：http://dali.cashguo.top/Article/details/gtcdlwmdac.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gtmjqnmhrf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnqzz.top/Article/details/gtdsalthrs.html

[R75] 导出环境变量
来源：http://dali.zhixingplan.top/Article/details/gtpbgsgihf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cdnleiting.top/Article/details/gtsdugwwwm.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gtgfqmnjzw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gthvtthjef.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gtyejntxhw.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gtitoggynz.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gtculamvwl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuanzhike.top/Article/details/gtnreckrpf.html

[R79] 解析命令行选项
来源：http://dali.gotoacloud.top/Article/details/gtufvqzvps.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gtngmzoazs.html

[R80] 查看脚本执行耗时
来源：http://dali.vqdsnc.cn/Article/details/gtqtohoijs.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gtgzgttjug.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtakbmbghv.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gtellbhkft.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gteemsttwn.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtsewijdmr.html

#include <stdio.h>
来源：http://dali.jqgufenzy.top/Article/details/gtihkaxrjl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigufen.top/Article/details/gtaymlszcw.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gteslmcbso.html

int a = 10; printf("%d\n", a);
来源：http://dali.yonumen.top/Article/details/gtqhvqmilq.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gtfvypcywm.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gtsnshhowj.html

[S04] C：字符串复制
来源：http://dali.nanxinkj.top/Article/details/gtejscxmxe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangdashe.top/Article/details/gtmxmtqzse.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtwpjezwec.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gtphtdrcqo.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gtxakvwmlm.html

strcmp(a, b) == 0
来源：http://dali.feifeiyinyue.top/Article/details/gtwdjlxklb.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gtuyhcxhhv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gtltqaapnz.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gtjtqurqdp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gtdopvsfoz.html

[S09] C：结构体定义与初始化
来源：http://dali.andypj.xyz/Article/details/gtvwgucvzz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yvedp.cn/Article/details/gtnlxikbtt.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gthloczssg.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gtcddwxmzr.html

[S11] C：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtkiftriaf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghjevcrs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gtqhcuksrr.html

fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtsnpnkgtg.html

[S12] C：写文件
来源：http://dali.yuxming.cn/Article/details/gtxymxxupq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpahvgjv.html

[S13] C：宏定义
来源：http://dali.yj20258.top/Article/details/gtlrbzhqct.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gtyhudiznr.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gtqkdnuqhd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gtzyuegaqu.html

[S15] C：类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrabdbbo.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gtjdlezjbg.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gtmbaqxgge.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gthaodoscl.html

[S17] C：安全拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtadtlgaue.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gtkaackxqm.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gtigprxwlr.html

int main(int argc, char **argv)
来源：http://dali.zhengqikj.top/Article/details/gtyxbivdev.html

[S19] C：快速排序
来源：http://dali.feifeiyinyue.top/Article/details/gtspunykzg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtqqqqvtid.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gtayjeelfe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtvuayocqd.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gtrjoyqkov.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shzxlz.cn/Article/details/gtwdmcuehz.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkjgikzx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gtnnnotzfs.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gtnbykqigb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yongpay.top/Article/details/gtwmubaefe.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gtqoefmycp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daxiang520.top/Article/details/gtapaanovl.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gtqeinbftd.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gtswubzaqf.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzihhfgtq.html

memset(a, 0, sizeof a);
来源：http://dali.yvedp.cn/Article/details/gttecriazd.html

[S27] C：定义常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpunogjh.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtdoworxme.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gtnsnxvfsv.html

static int counter = 0;
来源：http://dali.dianchejie.cn/Article/details/gtgyvzsgdt.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gtgffdcxhi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pycfn.com/Article/details/gtfxlhqgvu.html

[S30] C：头文件保护
来源：http://dali.9152youxi.cn/Article/details/gtzgwxlogj.html

#ifndef X_H
来源：http://dali.yongpay.top/Article/details/gtmxschham.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gtdfdmrsli.html

#endif
来源：http://dali.iojbl.cn/Article/details/gtdicqkyso.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtdzcttroq.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gtkwpfbraw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvmuxvqa.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gtvpoczmti.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gtkvieeidk.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gtfrepzqzn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtqydvsint.html

[S34] C++：遍历 vector
来源：http://dali.hysaishi.cn/Article/details/gtnouxaajh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gtijlmevqv.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gtcbythgzw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtequziefm.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlkvzstx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtxnbqgcyh.html


<!-- 参考信息 -->