代发 wailian999

[Q80] 字符串截取
来源：http://dali.yonumen.top/Article/details/gteobpafhn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtnmzizczh.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtkyeewzri.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtzwqdpcty.html

[Q82] 字符长度与字节长度
来源：http://dali.gaohongyu789.top/Article/details/gtjubtbsex.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtqdhhpeqw.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtvynuqugp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtqkazpipg.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gthzyihjis.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtjltnprjj.html

[Q85] 数值取整
来源：http://dali.hammf.cn/Article/details/gtoxsrkirz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gtlpbylqey.html

[Q86] 读取 JSON 字段
来源：http://dali.shuidangran.top/Article/details/gtrbucqqbt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gtjxpwupry.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gtukpzprai.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuetiantiany.cn/Article/details/gttlnuxuav.html

[Q88] 行转列（条件聚合）
来源：http://dali.ybcxt.top/Article/details/gtrcqtayag.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.316326.xyz/Article/details/gtdrbrthjk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrjbnxht.html

[Q89] 判断表是否存在
来源：http://dali.ehwqpu.com/Article/details/gtdixgouyn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoemvmarp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gtnberpsjg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gtekpbaqfq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvuurjjxd.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gtjxvdxoek.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbpzmapmn.html

[R01] shebang 与严格模式
来源：http://dali.zhongyouzk.top/Article/details/gtnyequanl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gtbdbfnxaz.html

set -euo pipefail
来源：http://dali.sufxvd.cn/Article/details/gthukjbhdu.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gtjvyfqdga.html

name="Tom"; echo "$name"
来源：http://dali.hywenlv.cn/Article/details/gtzbyyazja.html

[R03] 只读变量
来源：http://dali.yuanzhike.top/Article/details/gtjljdklst.html

readonly PI=3.14
来源：http://dali.kuanghao11.cn/Article/details/gtoktaqcgj.html

[R04] 位置参数
来源：http://dali.hammf.cn/Article/details/gtsudteihy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgacelov.html

[R05] 参数默认值
来源：http://dali.snrcjt.cn/Article/details/gtktkfjwgg.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gtdvfsulme.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtikgsvcln.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtudjwpupi.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gtkxogkuvs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gtritjmruw.html

[R08] 数值比较
来源：http://dali.guannengcc.top/Article/details/gtxuroabdz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.smart0.xyz/Article/details/gtoeiwewzz.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtwvgzefzq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yangfankeji.com/Article/details/gtsdxiypcs.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gtpvfodyyd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gtpkjnndwn.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gtmasdjluj.html

case "$1" in
来源：http://dali.nwbrower.top/Article/details/gtcfwujrsc.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gtvrpfembh.html

stop)  echo "停止" ;;
来源：http://dali.9152youxi.cn/Article/details/gtzmyvicsa.html

*)     echo "未知命令" ;;
来源：http://dali.fzhhl.top/Article/details/gtoqamnrym.html

esac
来源：http://dali.hongshengwenyu.top/Article/details/gtjcoumyar.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gtgcohhaku.html

for f in *.txt; do echo "$f"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtcfivjhsk.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gtivrbukhq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtcyggoiyy.html

[R14] C 风格 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykwcnbma.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtloaggefv.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtjetivskr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxicrmwq.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gthgzppoqe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtknkpnvoc.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gtntxkwvrv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gtkypgzrwq.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gtsqpgjjcc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tianlin.xyz/Article/details/gtglibvhdf.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtyjkexxpj.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gtknxwobbc.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gtwcfvwhhf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gtrxlyebbv.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gthgupacwf.html

echo "${#s}"
来源：http://dali.jinqigfzy.top/Article/details/gtjhitbvfh.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gtpsdqxnhb.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gtzpyxosxn.html

[R23] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxvucqvs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhongyouzk.top/Article/details/gtrgrlmzsv.html

[R24] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtliwkksbi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gtmetxiazq.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gtislqmwyu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gtrgoyfbaj.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gtaxwnnfpg.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gtcxlbwwln.html

[R27] 算术展开
来源：http://dali.daxiang520.top/Article/details/gtmpextktd.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtrejtgfkq.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gtvfulxfue.html

echo "scale=2; 10/3" | bc
来源：http://dali.gzhubu.top/Article/details/gtobxkkyze.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gtbwriuihw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhengqikj.top/Article/details/gtpyxwyxhd.html

[R30] 函数返回状态码
来源：http://dali.redwolf501.top/Article/details/gtkoihvebz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gtnvzkeyru.html

[R31] 局部变量
来源：http://dali.yonumen.top/Article/details/gtaduelbcn.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtofrivzfo.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtkffpfebw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtdlekxygk.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gtsvcktxmr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gtbfoknasn.html

[R34] 退出时清理
来源：http://dali.quarkkingdee.top/Article/details/gttywikpcm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gtlkheltfy.html

[R35] 后台执行并等待
来源：http://dali.hnxiangtu.top/Article/details/gtoffgpmrr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gtlpcprzxm.html

[R36] 并发执行多个任务
来源：http://dali.ydzc1.top/Article/details/gtuqsdipir.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hongshengwenyu.top/Article/details/gtiteboijv.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gteduxaegb.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gttdztbtwb.html

[R38] 管道串联
来源：http://dali.xuanzx.com/Article/details/gtvilqcefi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.smart0.xyz/Article/details/gtsenbnfsb.html

[R39] 重定向标准输出与错误
来源：http://dali.redwolf501.top/Article/details/gtuhpqjxll.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gtkvdorscz.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gtyowfwewe.html

echo "log" >> out.log
来源：http://dali.nanxinkj.top/Article/details/gtarhcpgdm.html

[R41] 丢弃输出
来源：http://dali.redwolf501.top/Article/details/gtyazpvruv.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gtnepddtcj.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gtrmzjthqz.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gtzqzrpert.html

[R43] 按名字查找文件
来源：http://dali.snrcjt.cn/Article/details/gtmumiwkly.html

find . -name "*.log" -type f
来源：http://dali.smart0.xyz/Article/details/gtwbxbqaak.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gtlkjzfqos.html

find . -mtime -7 -type f
来源：http://dali.nanxuanxn.top/Article/details/gtakdjnrhr.html

[R45] 批量删除
来源：http://dali.iojbl.cn/Article/details/gtwkdnwixz.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gtlxeczsfj.html

[R46] 递归替换文件内容
来源：http://dali.zhiwuduotai.top/Article/details/gtbudpyybc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gtqpogdewg.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gtbxeonnis.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gttfjxqvnv.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gtfgjlidfx.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtsxtsmrkb.html

[R49] awk 带条件
来源：http://dali.xuetiantiany.cn/Article/details/gtqagitulp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvezzshll.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gtasjlptso.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xylfe.cn/Article/details/gtlssrelss.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gtgxbmgpvn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gtgwsfwmkg.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gtwuzfoqmq.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gtpbfwqach.html

[R53] 查看文件头与实时尾
来源：http://dali.xuetiantiany.cn/Article/details/gtkbkujmrv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gtyminaauw.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gtryohaedy.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gtpgyupeze.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gtghnfpvux.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sysykeji.top/Article/details/gtqodbcupd.html

[R56] 远程拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtymnqadbb.html

scp file user@host:/path/
来源：http://dali.jinqigfzy.top/Article/details/gtkkdiegyx.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnseoldj.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxjzojlu.html

[R58] 下载文件
来源：http://dali.hammf.cn/Article/details/gthtegwwvb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.0kj1m.cn/Article/details/gtfyfgbohp.html

[R59] 发 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtmpuhsrdm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.mhx1999.top/Article/details/gtciwmhkvv.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gttamzhimd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlgrfpct.html

[R61] 磁盘占用
来源：http://dali.zhoulong.xyz/Article/details/gtousiggsp.html

df -h;  du -sh *
来源：http://dali.hammf.cn/Article/details/gtjhzgglqy.html

[R62] 找最占空间的文件
来源：http://dali.vqdsnc.cn/Article/details/gtplxienwc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlljtraf.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gtyohtolhb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhixingplan.top/Article/details/gtllobbafv.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gtvppkbych.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guannengcc.top/Article/details/gtgemqfykl.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gtpqjbmtzf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvxojdle.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtfqayzqcj.html

crontab -e;  crontab -l
来源：http://dali.daria6918.cn/Article/details/gtrhgamjzq.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtronouhqw.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gtdvyaobbr.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gtcdvoqicg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gzhubu.top/Article/details/gtcajkkaip.html

[R69] 生成随机密码
来源：http://dali.hammf.cn/Article/details/gtsuqpoxkx.html

head -c 16 /dev/urandom | base64
来源：http://dali.shuidangran.top/Article/details/gtznwncnng.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gtsrwaakic.html

date +%s;  date -d @1700000000
来源：http://dali.ppjwa.cn/Article/details/gtpfwdrvqp.html

[R71] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtowcoulup.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gtdervlrar.html

[R72] 等待端口就绪
来源：http://dali.feifeiyinyue.top/Article/details/gtdddvflzu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtvakfawdp.html

[R73] 分割大日志
来源：http://dali.svipenyu.cn/Article/details/gtnoclkjir.html

split -l 1000 big.log part_
来源：http://dali.hnqzz.top/Article/details/gtbzxupnut.html

[R74] 批量重命名
来源：http://dali.wangdashe.top/Article/details/gtaejviehr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gttsbrlqen.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtcaxigvfn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gtexmginln.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gtgqixhyqw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtqtnnihby.html

[R77] 读取用户输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnctcwtgr.html

read -rp "请输入: " ans
来源：http://dali.sxryk.cn/Article/details/gtgnwqexqo.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gtmghcidkl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gtaoukzype.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gtragkkilu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gtastigtyt.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gtfrbhyoia.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gtzxpsuilc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqnsvxthi.html

S. C / C++ 专题
来源：http://dali.vqdsnc.cn/Article/details/gtyfxuqtzt.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmayydfyu.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gtzuzeghhz.html

#include <stdio.h>
来源：http://dali.nanxinkj.top/Article/details/gtfktxyfwv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xinyue.icu/Article/details/gtktbmywyb.html

[S02] C：变量与格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtmvdnjtsi.html

int a = 10; printf("%d\n", a);
来源：http://dali.ydzc1.top/Article/details/gtfxvteaxn.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gttrsmzqyg.html

int x; scanf("%d", &x);
来源：http://dali.svipenyu.cn/Article/details/gtzurjbymu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gtdvxvabxn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.bjfxy.top/Article/details/gtvzofjogy.html

[S05] C：字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtyvbfonvk.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gteigxbitr.html

[S06] C：字符串比较
来源：http://dali.meibo888.top/Article/details/gtujktjxan.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtqhvklkxi.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtqdcqggya.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gtbrfidhsw.html

[S08] C：动态内存分配与释放
来源：http://dali.ybcxt.top/Article/details/gtizljufsu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gtgylsqnby.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gtuiiiespm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gtvwfpbyiv.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgvarhho.html

int *p = &a;  *p = 5;
来源：http://dali.aizwys.cn/Article/details/gtakpropht.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtbtsqsybj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gtfcbfrhni.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuxming.cn/Article/details/gtjjukirsr.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gthdozsuic.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvhtrasp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gtucddfdgs.html

[S13] C：宏定义
来源：http://dali.cdnleiting.top/Article/details/gtsbbgexpi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tian-w.cn/Article/details/gtlczoeaef.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gtukncqdam.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shuidangran.top/Article/details/gtemrbywkf.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gtuudkbkia.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gtjpzxhnnt.html

[S16] C：位操作置位
来源：http://dali.yuxming.cn/Article/details/gtdcaqqhjb.html

x |= (1 << 3);
来源：http://dali.gzhubu.top/Article/details/gtmfygzwdy.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtlzgijkdg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gtfcbtgpom.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmlrrkex.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gttmjkjabj.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gtewrlrogd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtuhbabvrz.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gtzlstefbx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtdjaxljbm.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gtyodxlior.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gtrfgzubly.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtsycnmahu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gtnmfvwvgd.html

[S23] C：随机数
来源：http://dali.wangdashe.top/Article/details/gtcsxhicqt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqzkitlw.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gtoggirmpo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hysaishi.cn/Article/details/gtvmgpktql.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gtiziawvfl.html

memcpy(dst, src, n);
来源：http://dali.zhixingplan.top/Article/details/gtfdeokwpa.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gtxaiqqfzs.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gtuppgvfrk.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkelvlbi.html

const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtckrakkbv.html

[S28] C：静态变量
来源：http://dali.yj202588.top/Article/details/gtadeluvdd.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gtxskfsrvf.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gtrsgjvnwi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtckcefdzy.html

[S30] C：头文件保护
来源：http://dali.sysykeji.top/Article/details/gtfzljwqgp.html

#ifndef X_H
来源：http://dali.snrcjt.cn/Article/details/gtshphywem.html

#define X_H
来源：http://dali.316326.xyz/Article/details/gtddyukhus.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gtvnlsfgpq.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtiopgvwgk.html

#include <iostream>
来源：http://dali.guannengcc.top/Article/details/gtictjjkcx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gtbqkeitot.html

[S32] C++：字符串
来源：http://dali.9152youxi.cn/Article/details/gtprtmimfv.html

std::string s = "hi";  s += "!";
来源：http://dali.aizwys.cn/Article/details/gtslelraee.html

[S33] C++：vector 增删
来源：http://dali.nanxuanxn.top/Article/details/gtxxdpnpcu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gtzrngkudg.html

[S34] C++：遍历 vector
来源：http://dali.aizwys.cn/Article/details/gteluvvyrh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkfqcmil.html

[S35] C++：map
来源：http://dali.wangdashe.top/Article/details/gtfwxftokm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesgxnzru.html

[S36] C++：unordered_map
来源：http://dali.yj20258888.top/Article/details/gtxounzqzz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtjcecsnzh.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gthofzuqvp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gthifaaotc.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gtrrvvuddt.html

std::sort(v.begin(), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgsbhahd.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gtebszsbqn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cheryme.top/Article/details/gtgcneuojf.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gtoalpvois.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtkrqstpng.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gtkjqaxfqv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gtjjiclgil.html

[S42] C++：继承与虚函数
来源：http://dali.xylfe.cn/Article/details/gtilwcpirf.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gtllbvxjkk.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gtoutrbzod.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodoesxvz.html

[S44] C++：引用传参
来源：http://dali.havefunace.top/Article/details/gtcxysmwkf.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gtqjyjerge.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gtzsttwvqx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gtvvfjkprd.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gtvvcoetbz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ivvv.top/Article/details/gtqdywrfku.html

[S47] C++：结构化绑定遍历
来源：http://dali.snrcjt.cn/Article/details/gtbkrosxps.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sysykeji.top/Article/details/gtpohfbcxd.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtrtoqzijc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gtvejbphoz.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gtvtxwvaio.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gtemihrrvz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gtkoohsvlo.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gtrzjynquy.html


<!-- 参考信息 -->