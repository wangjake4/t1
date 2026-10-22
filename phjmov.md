代发 wailian999

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gtupbojfay.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gtkgqnlync.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gtmdtgogch.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zycfv.cn/Article/details/gtbpssvrnd.html

[Q78] 当前时间
来源：http://dali.yj202588.top/Article/details/gtdpgavodf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuetiantiany.cn/Article/details/gtsyfcxdls.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gtufokitil.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.316326.xyz/Article/details/gtqzoislfb.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gtljqjcppf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtmxvbvtax.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzhkbolo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtvcdqxwtp.html

[Q82] 字符长度与字节长度
来源：http://dali.jianghu66.top/Article/details/gtnkixiqfr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtmibfymnn.html

[Q83] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtvjuzqlof.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtjlbyzodv.html

[Q84] 去除首尾空格
来源：http://dali.zhengqikj.top/Article/details/gtcqbcnpuw.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtlfhjhexo.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gtwqmiegjt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gtpuxawydw.html

[Q86] 读取 JSON 字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfvsrpcg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yonumen.top/Article/details/gtahiqrnti.html

[Q87] JSON 字段做条件
来源：http://dali.c1oappe.top/Article/details/gtiglqnzxk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gtlhyhqnwe.html

[Q88] 行转列（条件聚合）
来源：http://dali.vqdsnc.cn/Article/details/gtlyvoofba.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gtwqpumpit.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtatchrljz.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtunpmjuvb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guowangkeji.top/Article/details/gtasvzcyyv.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gtplhwslnx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xinyue.icu/Article/details/gtfrskowct.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdfevefy.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtzxpanrtd.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtptqouyxn.html

[R01] shebang 与严格模式
来源：http://dali.jyoumei.cn/Article/details/gtngysmeey.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gtvhtyyxev.html

set -euo pipefail
来源：http://dali.xinyue.icu/Article/details/gtmlyooucl.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gtznrjidkd.html

name="Tom"; echo "$name"
来源：http://dali.sysykeji.top/Article/details/gttjhspqhk.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gtxiumkdxj.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gtrtcmpsbd.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gtuaunjoof.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gtsrruguys.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gtbkqfprhh.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gtklqhiftg.html

[R06] 判断命令是否存在
来源：http://dali.andypj.xyz/Article/details/gtfokpwtyo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtchrlxbhs.html

[R07] if 判断文件
来源：http://dali.xziqi.cn/Article/details/gtjyzfjdir.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbwmrhph.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gtbyssfhxg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenlongwang.top/Article/details/gtgdravaad.html

[R09] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtpkpgtuoi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gtcnyemsrc.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gtndsjytvy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtewzilllb.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtsjacfdyy.html

case "$1" in
来源：http://dali.andypj.xyz/Article/details/gtruaelgkb.html

start) echo "启动" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtkjnffclb.html

stop)  echo "停止" ;;
来源：http://dali.shuidangran.top/Article/details/gtipqdehoy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gttxigtpvt.html

esac
来源：http://dali.kuanghao11.cn/Article/details/gteylyhvxe.html

[R12] for 遍历文件
来源：http://dali.mhx1999.top/Article/details/gtqnknbvdo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gtnbaogpvd.html

[R13] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gtkmqkwswz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtugymvxca.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gtdtlzsgfx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gtfriehycq.html

[R15] while 逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtaiosxafp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtmjyodyow.html

[R16] until 等待条件
来源：http://dali.svipenyu.cn/Article/details/gtfpyedxrg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtwoqepipi.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gtivajgzny.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gtdonwwjjq.html

[R18] 遍历数组
来源：http://dali.andypj.xyz/Article/details/gtqwbmafdj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgufenzy.top/Article/details/gtrxguhbdh.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtipriybtl.html

echo "${#arr[@]}"
来源：http://dali.hfpthk.cn/Article/details/gtktfqouot.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gthtxrvpak.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtracbtwyj.html

[R21] 字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtoukosyun.html

echo "${#s}"
来源：http://dali.aizwys.cn/Article/details/gtcxpsimad.html

[R22] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtbenbcywc.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gtgbyrigqf.html

[R23] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtsolhcxaq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hywenlv.cn/Article/details/gtwblacxpe.html

[R24] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtnzldcexx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gtsfnufqux.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gtbjphbtkb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenjidiqi.icu/Article/details/gtrbcjldon.html

[R26] 命令替换
来源：http://dali.aibaodan.cn/Article/details/gtyxjztafk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gtgxqlazva.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gtknwhzqyd.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gtkwnpfobq.html

[R28] 浮点运算
来源：http://dali.zdqjudy.top/Article/details/gtirmqarvz.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gtjgmmhdzw.html

[R29] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtoprkkwtp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gtboqjkatm.html

[R30] 函数返回状态码
来源：http://dali.nanxinkj.top/Article/details/gtyghivypt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ybcxt.top/Article/details/gtbklhzfvq.html

[R31] 局部变量
来源：http://dali.hysaishi.cn/Article/details/gtavqzbltd.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gtxqkjtqdy.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gttzoxysbo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gteoapnwnd.html

[R33] 捕获错误并提示行号
来源：http://dali.sweek.top/Article/details/gtnvlikmov.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigufen.top/Article/details/gtqlkvugcx.html

[R34] 退出时清理
来源：http://dali.havefunace.top/Article/details/gtuhedioty.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtzvyxccrd.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gtkgccusbt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gtbdbqhtcg.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gtktqpqrpc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tanke756.top/Article/details/gtudcvedqn.html

[R37] 把输出赋给变量
来源：http://dali.quarkkingdee.top/Article/details/gtyluxnjyl.html

files=$(ls -1)
来源：http://dali.xuanzx.com/Article/details/gtwffzsqyb.html

[R38] 管道串联
来源：http://dali.sxryk.cn/Article/details/gtkudznyfc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsoafhrey.html

[R39] 重定向标准输出与错误
来源：http://dali.shangyingyoupin.top/Article/details/gtuotiwmfh.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gtmuhaxihi.html

[R40] 追加写日志
来源：http://dali.tian-w.cn/Article/details/gtpqrcpieo.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gtzuujssyk.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gtxlmwuvbn.html

cmd >/dev/null 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtzpklugot.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gtzfmhzrmk.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gtndpxipvh.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksabzjdx.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfcpkicd.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtikoqzjcb.html

find . -mtime -7 -type f
来源：http://dali.birdmap.top/Article/details/gtwfbzvfic.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gtsiugtlyg.html

find . -name "*.tmp" -delete
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajdubbst.html

[R46] 递归替换文件内容
来源：http://dali.hywenlv.cn/Article/details/gtatsznwtp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gtvtbfbgjm.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gtoywvvtbb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtrujrocta.html

[R48] awk 取指定列
来源：http://dali.shuidangran.top/Article/details/gtelwdwczh.html

awk '{print $1, $3}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtpbcrxapd.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gtmlrjoask.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gtndpcvtbf.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gtbrbxwpdy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtfikmzxcn.html

[R51] 排序去重取前几
来源：http://dali.zdqjudy.top/Article/details/gtqmosybud.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gtayjbstwp.html

[R52] 统计行数
来源：http://dali.jinqigufen.top/Article/details/gtvioqkvyc.html

wc -l a.txt
来源：http://dali.svipenyu.cn/Article/details/gtfqxvrigr.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gtpjctncrp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.meibo888.top/Article/details/gttxlhxyvc.html

[R54] 比较两个文件
来源：http://dali.aibaodan.cn/Article/details/gtodgoslmi.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gtkyxaajlh.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gtaokuhhgu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuetiantiany.cn/Article/details/gtjtzwqzbo.html

[R56] 远程拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtiemfdkfl.html

scp file user@host:/path/
来源：http://dali.quarkkingdee.top/Article/details/gtxpyihyvx.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gttzibtglm.html

ssh user@host 'uptime'
来源：http://dali.jianghu66.top/Article/details/gtvtufegvc.html

[R58] 下载文件
来源：http://dali.yj20258888.top/Article/details/gtkrnazbpi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhoulong.xyz/Article/details/gtkdvgyozt.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtajfxcmck.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gtlgqnmqsp.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtofewzmyu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gtkdptnvvs.html

[R61] 磁盘占用
来源：http://dali.cqqwz.cn/Article/details/gtctqwocyb.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gthgwiufok.html

[R62] 找最占空间的文件
来源：http://dali.zdqjudy.top/Article/details/gtsrnsfeup.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gthwuwpves.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gtfsltglom.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gtbzytaind.html

[R64] 结束进程
来源：http://dali.c1oappe.top/Article/details/gtlzwzmtna.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gtgkbcnrna.html

[R65] 查看端口占用
来源：http://dali.smart0.xyz/Article/details/gttycmhrmt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxinkj.top/Article/details/gtwgasjcqc.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gtzfxjyequ.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gtcpujtqnz.html

[R67] 生成随机十六进制串
来源：http://dali.ehwqpu.com/Article/details/gtmnmunelk.html

openssl rand -hex 16
来源：http://dali.zhongyouzk.top/Article/details/gtganedkhl.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gtrelcuaax.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yangfankeji.com/Article/details/gtfifouaat.html

[R69] 生成随机密码
来源：http://dali.ybcxt.top/Article/details/gtsckiqefh.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gtejneebye.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtwqxgzeyz.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqosguypw.html

[R71] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtegwbpumf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgufenzy.top/Article/details/gtttfbmehy.html

[R72] 等待端口就绪
来源：http://dali.yvedp.cn/Article/details/gthpwhzuzu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvufeeuqy.html

[R73] 分割大日志
来源：http://dali.pycfn.com/Article/details/gtjottyxbv.html

split -l 1000 big.log part_
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvmxyszd.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gtgvdeaozm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenzaomai.com/Article/details/gtqdwsewmr.html

[R75] 导出环境变量
来源：http://dali.fzhhl.top/Article/details/gtykgmsjec.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gtzfvyionx.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gtghvqqbng.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtbjnmbikk.html

[R77] 读取用户输入
来源：http://dali.feifeiyinyue.top/Article/details/gtltvjabht.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gtoieylape.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gttiftqdlu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pengpengdd.cyou/Article/details/gtypmsiwsk.html

[R79] 解析命令行选项
来源：http://dali.meibo888.top/Article/details/gtvrwjrmwr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jiagoushi.top/Article/details/gtzxylfntc.html

[R80] 查看脚本执行耗时
来源：http://dali.pengpengdd.cyou/Article/details/gtwbdzwzdk.html

time ./run.sh
来源：http://dali.sxryk.cn/Article/details/gtjghjzbvy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtaorycrto.html

S. C / C++ 专题
来源：http://dali.tianlin.xyz/Article/details/gtilaxaqae.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtfquwufpr.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gthhkipdbm.html

#include <stdio.h>
来源：http://dali.zhongyouzk.top/Article/details/gtmkbbvuqc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnqzz.top/Article/details/gtreiyxahl.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gtqtppfulc.html

int a = 10; printf("%d\n", a);
来源：http://dali.hfpthk.cn/Article/details/gtcjeolnhf.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gtgfwmfofe.html

int x; scanf("%d", &x);
来源：http://dali.hnqzz.top/Article/details/gtlurfrfzs.html

[S04] C：字符串复制
来源：http://dali.daxiang520.top/Article/details/gtgwdywktk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gtbekagcfg.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmknozvv.html

strlen(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvbkcvmu.html

[S06] C：字符串比较
来源：http://dali.havefunace.top/Article/details/gtkcmxzoha.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gtfmacfzjx.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gtiturnljb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgclutyd.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gtrraazgkh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gtospxahvp.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gtasvrenjs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfygbhtf.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gtbcxkvlgx.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gtrotolmgr.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gthopkrxmq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.birdmap.top/Article/details/gtvgmuytrq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hammf.cn/Article/details/gtfvmlcbyw.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gtdlblqgai.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gtnlekrbsk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljrlfsho.html

[S13] C：宏定义
来源：http://dali.xinyue.icu/Article/details/gtiajgnmbr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gtnhgwbtcd.html

[S14] C：枚举
来源：http://dali.gogol.net.cn/Article/details/gtnzmfwloq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gtdcgyyupr.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gtyzslhlup.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gtjoacpqij.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gtssczudmb.html

x |= (1 << 3);
来源：http://dali.cucudq.cn/Article/details/gtgcscdwmf.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtslpfdivx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gtrsgjusac.html

[S18] C：命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtjkcwqvqs.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgtapwzp.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gtdpirskvy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtrawbofwt.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gtjuebhwon.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtfsthoagm.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gtluqnpmjc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cheryme.top/Article/details/gtcvlgyaxy.html

[S22] C：字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtepmvtfmb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gtaxonagvr.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gtzaklkhjx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gtagqokzdx.html

[S24] C：获取本地时间
来源：http://dali.havefunace.top/Article/details/gttwnyyxdr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gtigdcsuvc.html

[S25] C：内存拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtletpcphw.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtdgmiaazz.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gtwecthxkh.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gtttklrrsz.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gtpmufbhoi.html

const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtwgzahzvr.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gtosnjucpi.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtklqkovrt.html

[S29] C：变参函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrbxyllx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gtoifctyen.html

[S30] C：头文件保护
来源：http://dali.shuidangran.top/Article/details/gtevbobcrg.html

#ifndef X_H
来源：http://dali.jqgufenzy.top/Article/details/gtlxzpoudb.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gtbidpovbl.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gtnluzongw.html

[S31] C++：Hello World
来源：http://dali.fengsongda.top/Article/details/gtvxjnjxii.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gtlqoveynv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gtkvilsgpz.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gtebrqolhk.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gttioagdmk.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gtxpymuhmp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gtwailwqig.html

[S34] C++：遍历 vector
来源：http://dali.zdqjudy.top/Article/details/gtwgmjydvz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gtshcztcbp.html

[S35] C++：map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzxfgmhv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtofyrwmrd.html

[S36] C++：unordered_map
来源：http://dali.yonumen.top/Article/details/gtvzdywkza.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtcikckcwa.html

[S37] C++：set
来源：http://dali.sweek.top/Article/details/gtsylclbie.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tianlin.xyz/Article/details/gtxmrhjang.html

[S38] C++：排序
来源：http://dali.pycfn.com/Article/details/gtfgekjooj.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtibkgette.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gtkwhyubyx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ehwqpu.com/Article/details/gtlqqaezsp.html

[S40] C++：查找元素
来源：http://dali.tian-w.cn/Article/details/gtybgrmflm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shuidangran.top/Article/details/gtjtnjyeoo.html

[S41] C++：类与构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtpybajrbt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gtsevhpyrs.html

[S42] C++：继承与虚函数
来源：http://dali.0kj1m.cn/Article/details/gtwseieoul.html

class B : public Base { public: void f() override {} };
来源：http://dali.gzhubu.top/Article/details/gtebsihsxd.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gtlquligbk.html

auto p = std::make_unique<int>(5);
来源：http://dali.shzxlz.cn/Article/details/gtbexkpifp.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gtagqzvpzu.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gtnezulovx.html

[S45] C++：lambda
来源：http://dali.gogol.net.cn/Article/details/gtatcxkrie.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gtccuyxiqo.html

[S46] C++：函数模板
来源：http://dali.quarkkingdee.top/Article/details/gtzrurdmna.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gtkxvzlxmq.html


<!-- 参考信息 -->