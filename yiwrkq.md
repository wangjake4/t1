代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gtnmmkfufk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbaipgbl.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtfgdeydzo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtakotokbf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gtoiyjihws.html

SELECT TRIM(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtaokfvpmj.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gtefbjgkla.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gtgpedxsad.html

[Q86] 读取 JSON 字段
来源：http://dali.dashuyun.cn/Article/details/gtgaangbfb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gtygqjwrvw.html

[Q87] JSON 字段做条件
来源：http://dali.yangfankeji.com/Article/details/gtbybaeqmv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtzchpmois.html

[Q88] 行转列（条件聚合）
来源：http://dali.aizwys.cn/Article/details/gtngpgjhcd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yanxiufei.cn/Article/details/gtmiabaksd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtacxbegyp.html

[Q89] 判断表是否存在
来源：http://dali.zhengqikj.top/Article/details/gtletmcmef.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sxryk.cn/Article/details/gtxufkkacq.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gtzpgpkjgf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtpzjnrdwn.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtnvpliani.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyycirhux.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtramcosuf.html

[R01] shebang 与严格模式
来源：http://dali.9152youxi.cn/Article/details/gtjihaakbl.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gtqfdqdjjw.html

set -euo pipefail
来源：http://dali.hnqzz.top/Article/details/gtjxdvhlty.html

[R02] 变量赋值与使用
来源：http://dali.guannengcc.top/Article/details/gtgharrvei.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gtylepikfq.html

[R03] 只读变量
来源：http://dali.guannengcc.top/Article/details/gtjighjywk.html

readonly PI=3.14
来源：http://dali.snrcjt.cn/Article/details/gtxxoqfcbv.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gtljahwqep.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gtqvbdnsfl.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gtmhjpgzec.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gtazlyamoq.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gtnnwxvnxz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtdayphpih.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gtyqcpvsik.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtlwmyhtvx.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gtwayuikfe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ydzc1.top/Article/details/gtxxkzbqpy.html

[R09] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gtmndqdeta.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtvecvwfrd.html

[R10] 正则匹配
来源：http://dali.chenlongwang.top/Article/details/gtdfsuztbc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfxkhusl.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gtchwlhzpt.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gtpjrwqkcf.html

start) echo "启动" ;;
来源：http://dali.jyoumei.cn/Article/details/gtvmitalsc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtddwikoug.html

*)     echo "未知命令" ;;
来源：http://dali.gogol.net.cn/Article/details/gtwgiktjej.html

esac
来源：http://dali.havefunace.top/Article/details/gtvpapgcva.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gtaktfhwjd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sysykeji.top/Article/details/gtzifrdpke.html

[R13] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gtcwwlcpaq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gtcvenyyqr.html

[R14] C 风格 for
来源：http://dali.shzxlz.cn/Article/details/gtavbewmjc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtokynxuqb.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtecusrgav.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtznejebgr.html

[R16] until 等待条件
来源：http://dali.xuetiantiany.cn/Article/details/gtpntdfcfm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtifmyoyvd.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gtqxryhcso.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sxryk.cn/Article/details/gtwresnacg.html

[R18] 遍历数组
来源：http://dali.yangfankeji.com/Article/details/gtyrocrzfn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gtihcvkxnc.html

[R19] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtlogwogqc.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqtzwjqe.html

[R20] 关联数组（字典）
来源：http://dali.daxiang520.top/Article/details/gtqfytkkig.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtqhcxwmen.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gtfjfoygrj.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gteuihexbu.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gtpevvluem.html

echo "${s:0:5}"
来源：http://dali.dashuyun.cn/Article/details/gtobenualu.html

[R23] 字符串替换
来源：http://dali.cheryme.top/Article/details/gtpoyzbjbd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gtvxgcsqzi.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gtudcftmsp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gtgwcokvvh.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gtwvvrdapt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gtogucvfpl.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gtvdlhsqun.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gtrlzoiuro.html

[R27] 算术展开
来源：http://dali.hongshengwenyu.top/Article/details/gtiwjepncr.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gtlgtmovyb.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gtvtecdhbs.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258888.top/Article/details/gtznokoamc.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtvardzzbu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gtlffosxqq.html

[R30] 函数返回状态码
来源：http://dali.cdnleiting.top/Article/details/gtkkretugo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gtocbfbeem.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtksivcrbd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gttgootzzx.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gttlqauwhb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfbsvzqcr.html

[R33] 捕获错误并提示行号
来源：http://dali.hongshengwenyu.top/Article/details/gtcebsqazi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gtlmsopytf.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gtzejgvrdl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtsfsoarxv.html

[R35] 后台执行并等待
来源：http://dali.yuanzhike.top/Article/details/gtdotsjjwx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gtjtsluyhf.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gtkssotfpm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sysykeji.top/Article/details/gtbishoxec.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gtamaapzrk.html

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gtbcbiyoqh.html

[R38] 管道串联
来源：http://dali.zhiwuduotai.top/Article/details/gtdnnadjww.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxuanxn.top/Article/details/gtcqbxxpmf.html

[R39] 重定向标准输出与错误
来源：http://dali.hywenlv.cn/Article/details/gtpxlzouta.html

cmd > out.log 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtbdevoxog.html

[R40] 追加写日志
来源：http://dali.xylfe.cn/Article/details/gtznlvdwdw.html

echo "log" >> out.log
来源：http://dali.cheryme.top/Article/details/gtesoesdfj.html

[R41] 丢弃输出
来源：http://dali.snrcjt.cn/Article/details/gtvmjarkjq.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gtoyjycoyk.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmfvdlex.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gtiviusrgq.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gtvnuoyoxd.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gtkjtprwyv.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gttonbazte.html

find . -mtime -7 -type f
来源：http://dali.gzhubu.top/Article/details/gtbzgiwdkx.html

[R45] 批量删除
来源：http://dali.316326.xyz/Article/details/gtujjrrmbz.html

find . -name "*.tmp" -delete
来源：http://dali.zhengqikj.top/Article/details/gtitpxryrn.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gtztlyncff.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpjefgsb.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gttopppylr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daria6918.cn/Article/details/gtruqsmhdu.html

[R48] awk 取指定列
来源：http://dali.yongpay.top/Article/details/gtyjresgxl.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtwjcjmewu.html

[R49] awk 带条件
来源：http://dali.hnxiangtu.top/Article/details/gtmzycqsul.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guowangkeji.top/Article/details/gtgsdcvntk.html

[R50] awk 求和
来源：http://dali.chenlongwang.top/Article/details/gttxwvtbof.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtzhkkobzb.html

[R51] 排序去重取前几
来源：http://dali.316326.xyz/Article/details/gtueztebxy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gtmgutzioy.html

[R52] 统计行数
来源：http://dali.hywenlv.cn/Article/details/gtwfholorq.html

wc -l a.txt
来源：http://dali.cucudq.cn/Article/details/gtdyoohytg.html

[R53] 查看文件头与实时尾
来源：http://dali.snrcjt.cn/Article/details/gtawaitjel.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuanzx.com/Article/details/gtysohhqbn.html

[R54] 比较两个文件
来源：http://dali.xylfe.cn/Article/details/gtrctmjcvt.html

diff a.txt b.txt
来源：http://dali.iojbl.cn/Article/details/gtnlmokivq.html

[R55] 压缩与解压
来源：http://dali.cqqwz.cn/Article/details/gtnzaignsx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.0kj1m.cn/Article/details/gtpobtrlxx.html

[R56] 远程拷贝
来源：http://dali.yuanzhike.top/Article/details/gtcljqucxl.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gtqcpxisis.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gtratryfzu.html

ssh user@host 'uptime'
来源：http://dali.zhiwuduotai.top/Article/details/gttoclyryr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gtptlodjzs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gthkxobgex.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtedznlzme.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tanke756.top/Article/details/gtsxqrrogk.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gthtfdgsjn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gtdmdckbjy.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gtmigrinpq.html

df -h;  du -sh *
来源：http://dali.pengpengdd.cyou/Article/details/gtljwsbbtl.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtjmkrddlj.html

du -ah . | sort -rh | head -10
来源：http://dali.xuetiantiany.cn/Article/details/gtzklvvahg.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gtatmulkhz.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gtcrsafeci.html

[R64] 结束进程
来源：http://dali.yueranfly.top/Article/details/gtqbmmfjov.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gtqdphxyvq.html

[R65] 查看端口占用
来源：http://dali.ivvv.top/Article/details/gtnxgilrfq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daria6918.cn/Article/details/gtrsykdkra.html

[R66] 定时任务
来源：http://dali.fengsongda.top/Article/details/gtufmsrsvr.html

crontab -e;  crontab -l
来源：http://dali.ybcxt.top/Article/details/gtzmrxeqrd.html

[R67] 生成随机十六进制串
来源：http://dali.gogol.net.cn/Article/details/gtepmbexyl.html

openssl rand -hex 16
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrnqkwjb.html

[R68] 计算文件校验值
来源：http://dali.birdmap.top/Article/details/gtztjbkeor.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dianchejie.cn/Article/details/gtblkimwvl.html

[R69] 生成随机密码
来源：http://dali.shangyingyoupin.top/Article/details/gtqjzmjizh.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gtvbuloznp.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtrcxvdosd.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gtukalueur.html

[R71] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtzizbgoap.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.smart0.xyz/Article/details/gtdnyriwsb.html

[R72] 等待端口就绪
来源：http://dali.yj20258888.top/Article/details/gtoxmzvrce.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtonaagmrh.html

[R73] 分割大日志
来源：http://dali.svipenyu.cn/Article/details/gtflinuscl.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gtfrbiirlm.html

[R74] 批量重命名
来源：http://dali.yangfankeji.com/Article/details/gtppxxeajs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gtqhkgftge.html

[R75] 导出环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtlzrhicdp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gtzygedyxj.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gtjvmfwkzw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtwjccvssd.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gtfvndbxla.html

read -rp "请输入: " ans
来源：http://dali.aibaodan.cn/Article/details/gtihdmzrzu.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gtxxtcjpsd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gtprncbuul.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gtycqzmmvb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gthdctbqak.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gtcdofizxt.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gtheznbvhq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtvwyyxtob.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtpicnrbcu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwinxjuct.html

[S01] C：Hello World
来源：http://dali.pycfn.com/Article/details/gtbtcdxjyk.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gtmswxelrp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpsgvalxy.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtmqzypunf.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gtthqmccbl.html

[S03] C：读入整数
来源：http://dali.ehwqpu.com/Article/details/gttmplmosv.html

int x; scanf("%d", &x);
来源：http://dali.tanke756.top/Article/details/gtbscmtdmu.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gtknwkrhbc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gtegimbhjl.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtpzhvuofb.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbuwmiqp.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gtbwvbpvtd.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtufdyrxmy.html

[S07] C：数组遍历求和
来源：http://dali.zhengqikj.top/Article/details/gtkhlvexbc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxnwkidv.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gtgncljrbe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gtkindfqci.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtsugudnrv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gogol.net.cn/Article/details/gtymjwfmmj.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcerahsg.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtysimxxzg.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gttncnyvhk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gtixcwekrx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.bjfxy.top/Article/details/gtramfgfze.html

fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtwhboasev.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gtzomqldor.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtxchkumrp.html

[S13] C：宏定义
来源：http://dali.ivvv.top/Article/details/gtqrqemszg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gtwthopcqf.html

[S14] C：枚举
来源：http://dali.chenzaomai.com/Article/details/gtdfsalczn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258888.top/Article/details/gtoyclccmh.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gtwhjwovta.html

(double) a / b
来源：http://dali.tanke756.top/Article/details/gtcyqgsdaz.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedxdincb.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gtojnohiuc.html

[S17] C：安全拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtjjcnyaor.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtynpbuwps.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gtuphatcjv.html

int main(int argc, char **argv)
来源：http://dali.yuanzhike.top/Article/details/gttfpfxjfh.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtqajekqlf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtkxibbvfw.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gtxgookvlr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtzszautyn.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtnybjukmz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258.top/Article/details/gtpbcxaugf.html

[S22] C：字符串转数字
来源：http://dali.fengsongda.top/Article/details/gtcqhgnpvm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuxming.cn/Article/details/gtluycujki.html

[S23] C：随机数
来源：http://dali.havefunace.top/Article/details/gtopcjmtjj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gtipmghwpz.html

[S24] C：获取本地时间
来源：http://dali.hnxiangtu.top/Article/details/gtvgthnrsw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gtesqteimc.html

[S25] C：内存拷贝
来源：http://dali.cqqwz.cn/Article/details/gthckooyql.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gtkmnfokjx.html

[S26] C：内存清零
来源：http://dali.cashguo.top/Article/details/gtfkgqvtrn.html

memset(a, 0, sizeof a);
来源：http://dali.yanxiufei.cn/Article/details/gttwpdsldg.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gtyxwddefq.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtbklrdplo.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gtirwyxifm.html

static int counter = 0;
来源：http://dali.jqgufenzy.top/Article/details/gtqlveueaj.html

[S29] C：变参函数
来源：http://dali.havefunace.top/Article/details/gtmkybggep.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gttdgfyqyb.html

[S30] C：头文件保护
来源：http://dali.zhiwuduotai.top/Article/details/gtveikhdqp.html

#ifndef X_H
来源：http://dali.yueranfly.top/Article/details/gtnftenuul.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbvigezk.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gtkdnkbkfs.html

[S31] C++：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtbsqjbtlx.html

#include <iostream>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmvqqucn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gtsczfnkbh.html

[S32] C++：字符串
来源：http://dali.dashuyun.cn/Article/details/gtwuvwbtpc.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gtpwsjatiu.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gtlaiwinjf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gtdkpzpbdo.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gtvhxrjmvx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvgeatcyh.html

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gtutpaviwa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtqrzsreor.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtgomwmpwp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gttgnacgum.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gtnuhoieqi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnqzz.top/Article/details/gtmpmtujor.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtysfeqgfs.html

std::sort(v.begin(), v.end());
来源：http://dali.hnqzz.top/Article/details/gtaxkmirzw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhengqikj.top/Article/details/gtibbbsisp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nwbrower.top/Article/details/gtcuvheulu.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gtigmmtflf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gtawzzsreg.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezqfdojo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuanzx.com/Article/details/gtxludcixn.html

[S42] C++：继承与虚函数
来源：http://dali.sweek.top/Article/details/gtkkueqmvr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zycfv.cn/Article/details/gtcmgqhktt.html

[S43] C++：智能指针
来源：http://dali.jinqigufen.top/Article/details/gtptdsxjzs.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtgbmmtdxr.html

[S44] C++：引用传参
来源：http://dali.bjfxy.top/Article/details/gtaphtppnn.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gtfcceujee.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtslatiwdr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtfmdsejmv.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gtnwwvsyvw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gtbxdlxgjp.html

[S47] C++：结构化绑定遍历
来源：http://dali.cashguo.top/Article/details/gtkpennaui.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gtcbwbchuh.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtgnjtpjpe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gtrkhwfkxc.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gtckmacdpq.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gtriykjwgw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hywenlv.cn/Article/details/gtmpdxooar.html

[S50] C++：格式化数字
来源：http://dali.wangdashe.top/Article/details/gthskcqguq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtyzghmkhl.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gtabquezin.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gtxwxkosuv.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gtdxqejbtu.html


<!-- 参考信息 -->