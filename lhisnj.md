代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gtynnfcuqq.html

[Q75] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtcuwjfudf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtjyzdmqoj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gtruaclfqu.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gtcxsblkfp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtcprysvxj.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gtfkkbfxii.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenlongwang.top/Article/details/gtzejfapqb.html

[Q78] 当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxonhvhkl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvihnlaip.html

[Q79] 字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gtcageupuz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.0kj1m.cn/Article/details/gtxdriomfs.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gtzrfxntyn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtnxzcxtzs.html

[Q81] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtipucxshm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtncdxsuda.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gtswvdqidx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtaxdkpwhq.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtqmzarvoj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtrjoeynak.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gtmerfqhsw.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtzigfzgkk.html

[Q85] 数值取整
来源：http://dali.daria6918.cn/Article/details/gtjervuuui.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.andypj.xyz/Article/details/gtejplezsc.html

[Q86] 读取 JSON 字段
来源：http://dali.cdnleiting.top/Article/details/gtjcbsopmv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gtghwjvakj.html

[Q87] JSON 字段做条件
来源：http://dali.jiagoushi.top/Article/details/gtlptwtnnq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cqqwz.cn/Article/details/gtqdqprbfp.html

[Q88] 行转列（条件聚合）
来源：http://dali.andypj.xyz/Article/details/gtcpbzlras.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtjgrfxsix.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gtyahyzhwx.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gtitlmbowz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.birdmap.top/Article/details/gtisfszxyv.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gtzhoeebgd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gtifgllgic.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrpxeqlhq.html

R. Bash 专题
来源：http://dali.smart0.xyz/Article/details/gtudpsskeo.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtpiweewdo.html

[R01] shebang 与严格模式
来源：http://dali.hammf.cn/Article/details/gteoutstpm.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gtqsmkfhil.html

set -euo pipefail
来源：http://dali.bjfxy.top/Article/details/gtrgytasyk.html

[R02] 变量赋值与使用
来源：http://dali.svipenyu.cn/Article/details/gtastjkfuu.html

name="Tom"; echo "$name"
来源：http://dali.nwbrower.top/Article/details/gtpozvmwwv.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gtqgbnrbea.html

readonly PI=3.14
来源：http://dali.fzhhl.top/Article/details/gtukvhtbir.html

[R04] 位置参数
来源：http://dali.kuanghao11.cn/Article/details/gtdpqbumpk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gtrpxsxvmr.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gtabkmfcjp.html

name="${1:-default}"
来源：http://dali.tanke756.top/Article/details/gtgkdwzeog.html

[R06] 判断命令是否存在
来源：http://dali.gzhubu.top/Article/details/gtjismpkgi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtxkxtbaov.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmmsxryw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gtmlndvddp.html

[R08] 数值比较
来源：http://dali.bjfxy.top/Article/details/gtxeaunvsc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gtsrflmnat.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gtvvummukt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtewrefdym.html

[R10] 正则匹配
来源：http://dali.zhixingplan.top/Article/details/gthmuugzck.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhqghlmm.html

[R11] case 多分支
来源：http://dali.316326.xyz/Article/details/gtelualttv.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gtdmxuofpc.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gtkoqlpksb.html

stop)  echo "停止" ;;
来源：http://dali.yvedp.cn/Article/details/gtudploxzm.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gtrkwjsjsb.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gtmmgfizor.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gthdqbwsiu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gtthkqrnbu.html

[R13] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gtsufttlir.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtxlhdoafw.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gthqjhvuvl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gtuvdnfumi.html

[R15] while 逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtdfdvaycp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuanzx.com/Article/details/gtawmnrrco.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtechoqbbh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvdmukjf.html

[R17] 数组定义与取值
来源：http://dali.cqqwz.cn/Article/details/gtwqnckogv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sweek.top/Article/details/gtrdpqwewc.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gtnhlkmlrp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gtcaxejfwg.html

[R19] 数组长度
来源：http://dali.birdmap.top/Article/details/gtbutawciu.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gtxdndfhfc.html

[R20] 关联数组（字典）
来源：http://dali.ybcxt.top/Article/details/gtalmcgpvr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dianchejie.cn/Article/details/gtcwtlxfqm.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gttykultui.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gtbzgwguyw.html

[R22] 截取子串
来源：http://dali.hammf.cn/Article/details/gtzymhxjme.html

echo "${s:0:5}"
来源：http://dali.hammf.cn/Article/details/gtamvxvytb.html

[R23] 字符串替换
来源：http://dali.cheryme.top/Article/details/gtuqkupmwx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258.top/Article/details/gtzsihlxjn.html

[R24] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gthcxwdixj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gaohongyu789.top/Article/details/gtpzmdjwts.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gtwhnusakj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gtbdjrnojo.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gtaspaoiwa.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gtwrzemhkw.html

[R27] 算术展开
来源：http://dali.fzhhl.top/Article/details/gthagrengs.html

echo $((1 + 2 * 3))
来源：http://dali.dashuyun.cn/Article/details/gtubklmqof.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gtsduzjrrm.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gtndhlgkqq.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtpefkkwmi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cqqwz.cn/Article/details/gtweggihig.html

[R30] 函数返回状态码
来源：http://dali.pycfn.com/Article/details/gthxofttkw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gtnvithnbt.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gtomnmgnvz.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gtlhyzygwe.html

[R32] 参数个数校验
来源：http://dali.vqdsnc.cn/Article/details/gtjwmtipbq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gtnjoqpfss.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gtdfoqjxpu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gtqpserilo.html

[R34] 退出时清理
来源：http://dali.ybcxt.top/Article/details/gtlkidobpg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gthlsltzso.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gtigphvsjv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnqzz.top/Article/details/gtkbgolkwi.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gtvumnbmuj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gtvbhakynv.html

[R37] 把输出赋给变量
来源：http://dali.jlsjyb.cn/Article/details/gtzswvhlww.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtzprsrcbe.html

[R38] 管道串联
来源：http://dali.zhixingplan.top/Article/details/gtjveqnjqk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sxryk.cn/Article/details/gtmqidfzof.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gtkujcnjwi.html

cmd > out.log 2>&1
来源：http://dali.xziqi.cn/Article/details/gtdgficjlc.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gtclrjmeov.html

echo "log" >> out.log
来源：http://dali.jqgufenzy.top/Article/details/gtorfvtggx.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtboxzdhsl.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gtmabvffwj.html

[R42] 输入重定向
来源：http://dali.vqdsnc.cn/Article/details/gtujcmucda.html

wc -l < a.txt
来源：http://dali.zdqjudy.top/Article/details/gtpyabswsr.html

[R43] 按名字查找文件
来源：http://dali.pycfn.com/Article/details/gtyhqwqlnf.html

find . -name "*.log" -type f
来源：http://dali.bjfxy.top/Article/details/gtrujrdznh.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gtnodqgdyj.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gtlskvicua.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gtjjxjelpc.html

find . -name "*.tmp" -delete
来源：http://dali.jyoumei.cn/Article/details/gtvmdmigpa.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gthlthrxjs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guowangkeji.top/Article/details/gtazefgpjk.html

[R47] sed 单行替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtniyjeeyf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gtxunumocy.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gtqsetseuo.html

awk '{print $1, $3}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtrcuhgacf.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gttahfvoun.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zdqjudy.top/Article/details/gttbjiotts.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gtsbpuapvn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtlwvjdrjn.html

[R51] 排序去重取前几
来源：http://dali.redwolf501.top/Article/details/gttprdwocd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gtwpbgbecz.html

[R52] 统计行数
来源：http://dali.yj20258888.top/Article/details/gtrjotmeuw.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gtlharlnqt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gtrvqpadcn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gtkqhattel.html

[R54] 比较两个文件
来源：http://dali.zhongyouzk.top/Article/details/gtepuasoxh.html

diff a.txt b.txt
来源：http://dali.sufxvd.cn/Article/details/gtbswomsli.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gtddxbmuom.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sysykeji.top/Article/details/gtnoerdvpr.html

[R56] 远程拷贝
来源：http://dali.xylfe.cn/Article/details/gttnoddeek.html

scp file user@host:/path/
来源：http://dali.hysaishi.cn/Article/details/gtjccitfbe.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gtrzpybfos.html

ssh user@host 'uptime'
来源：http://dali.shuidangran.top/Article/details/gtthsjxajs.html

[R58] 下载文件
来源：http://dali.nanxuanxn.top/Article/details/gtmabtxhtv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ppjwa.cn/Article/details/gtycdvktrq.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtlqbkqnrs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuxming.cn/Article/details/gtbbixrfzl.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvbztadx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gtypfycifz.html

[R61] 磁盘占用
来源：http://dali.shangyingyoupin.top/Article/details/gtxhzaibmi.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gtfyvmbkav.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gtqnpagdnz.html

du -ah . | sort -rh | head -10
来源：http://dali.aizwys.cn/Article/details/gtpkydiyhl.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gtsctiqusn.html

free -h;  ps aux | grep nginx
来源：http://dali.guannengcc.top/Article/details/gtvlejoaau.html

[R64] 结束进程
来源：http://dali.gogol.net.cn/Article/details/gtbkbiqkgn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yonumen.top/Article/details/gthwwmqktc.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gtaaoqppkx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gtvmelgjlw.html

[R66] 定时任务
来源：http://dali.havefunace.top/Article/details/gthvrsywxo.html

crontab -e;  crontab -l
来源：http://dali.c1oappe.top/Article/details/gtohldlbxe.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigufen.top/Article/details/gthriikxcf.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gtnailmdyv.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gteogskovy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gtfubshsct.html

[R69] 生成随机密码
来源：http://dali.0kj1m.cn/Article/details/gtxhjtnevb.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gtnglwgufa.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gthscpsljr.html

date +%s;  date -d @1700000000
来源：http://dali.tanke756.top/Article/details/gthzzzomww.html

[R71] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtfgvyvbdg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.smart0.xyz/Article/details/gtduzaxbpy.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gtrrieqtut.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzxbafar.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gtbwnmdywd.html

split -l 1000 big.log part_
来源：http://dali.hnqzz.top/Article/details/gtcunzncfm.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gtcjzxgnet.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhoulong.xyz/Article/details/gtjtvlbpvl.html

[R75] 导出环境变量
来源：http://dali.hywenlv.cn/Article/details/gtzfbkgixb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gtgslpdquf.html

[R76] 使用临时文件
来源：http://dali.ydzc1.top/Article/details/gtykoiywcx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtkzhrrjnl.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuvjrpie.html

read -rp "请输入: " ans
来源：http://dali.xylfe.cn/Article/details/gtistskdhl.html

[R78] 交互式菜单
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbmjbfeb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenjidiqi.icu/Article/details/gtecemumer.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gtghzzaszg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gtgoxsblhj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gtouurvogn.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gtmhferqbl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvvpidblk.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsviouwqc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttxyeicuy.html

[S01] C：Hello World
来源：http://dali.daxiang520.top/Article/details/gtxcqfxwxu.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gtqlfwlciq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtgkvpejmx.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gtvowxkolw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zdqjudy.top/Article/details/gtgnfqdbwp.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gtdqvumadr.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtzyxzulnw.html

[S04] C：字符串复制
来源：http://dali.hnqzz.top/Article/details/gtwzxguyyz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtlngfpkum.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtwcjtobma.html

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtxclvaqhn.html

[S06] C：字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtlnjnuggt.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gtfmtfpuub.html

[S07] C：数组遍历求和
来源：http://dali.wangdashe.top/Article/details/gtrjycfhuq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gzhubu.top/Article/details/gtsovbxgvq.html

[S08] C：动态内存分配与释放
来源：http://dali.nwbrower.top/Article/details/gtqkzuuagd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhongyouzk.top/Article/details/gtcbglsjah.html

[S09] C：结构体定义与初始化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnominych.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gtwxusjaye.html

[S10] C：指针与解引用
来源：http://dali.yj202588.top/Article/details/gtoerbfceb.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtdczqfktu.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gttbrxumeu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gtnmodndoj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gtlwgkhaxo.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtntmetekl.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gtklknpjqp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtshhcbsgs.html

[S13] C：宏定义
来源：http://dali.zycfv.cn/Article/details/gtlhxuqegu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sxryk.cn/Article/details/gtkovsxglk.html

[S14] C：枚举
来源：http://dali.tianlin.xyz/Article/details/gtuvladfsc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuetiantiany.cn/Article/details/gtlikhexue.html

[S15] C：类型转换
来源：http://dali.yj20258888.top/Article/details/gtfkbbqdwh.html

(double) a / b
来源：http://dali.hysaishi.cn/Article/details/gtqvkjyeal.html

[S16] C：位操作置位
来源：http://dali.gzhubu.top/Article/details/gtpljaubil.html

x |= (1 << 3);
来源：http://dali.sweek.top/Article/details/gtlpnzjpmq.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gtikdgunmq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jiagoushi.top/Article/details/gtltlqniqk.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtbyinijhk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gtrlsxjhgv.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gtpyxtvrfc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtatwtolad.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gttokfprel.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtqiuazqka.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gtiedxmmec.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenlongwang.top/Article/details/gtbljuvvmv.html

[S22] C：字符串转数字
来源：http://dali.tian-w.cn/Article/details/gtqmtnyhnz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tanke756.top/Article/details/gtympreydo.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gtwspythis.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gtbjwerwfv.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gthiblszek.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gtwwkfomkb.html

[S25] C：内存拷贝
来源：http://dali.xylfe.cn/Article/details/gtsvfjtxoe.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gthvwxztjx.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwrpqtng.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtxlghchxu.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gtiqvephun.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtgcjmbzsj.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkpcmjce.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtcfkwiywg.html

[S29] C：变参函数
来源：http://dali.jinqigfzy.top/Article/details/gtbudzoyso.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.andypj.xyz/Article/details/gtexrlltcy.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gtmkyjsefr.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gtqarnmioj.html

#define X_H
来源：http://dali.aizwys.cn/Article/details/gtceuxneqy.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtdouhonat.html

[S31] C++：Hello World
来源：http://dali.yueranfly.top/Article/details/gtfjtrdctp.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtdezqkxge.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gtiykesyyt.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gtiwhxszen.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gtgigjaazq.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gtxrcslkmj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqubiwjsp.html

[S34] C++：遍历 vector
来源：http://dali.hfpthk.cn/Article/details/gttzkupxpn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gtcuripsnr.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gtdnypbowt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtzrpuohby.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gtkppkpamf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtgsmpmpbu.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gtetqmzgod.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fengsongda.top/Article/details/gtrxedinad.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuizgwqc.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtjoekhhim.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gtachzofmn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuetiantiany.cn/Article/details/gtjfqlcfml.html

[S40] C++：查找元素
来源：http://dali.316326.xyz/Article/details/gtvrbtyajz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yangfankeji.com/Article/details/gtrgxbtppj.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtymqhlqio.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guowangkeji.top/Article/details/gtmtayldni.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gtoziqoyfo.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtzidvffjg.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gtgarfrqqx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zycfv.cn/Article/details/gtxfjdsfxc.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gthghygwgc.html

void inc(int &x) { ++x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxygmmbkv.html


<!-- 参考信息 -->