代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.bjfxy.top/Article/details/gt2mfpupcug.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tghpvdqc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2serndzwf.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2hifzgmhh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gt2hqkwstza.html

[Q90] 生成序号列
来源：http://dali.zycfv.cn/Article/details/gt2kjewbxxu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ckcvqvte.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2pwsollhk.html

R. Bash 专题
来源：http://dali.cdnleiting.top/Article/details/gt2tnotziub.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2aymxeydt.html

[R01] shebang 与严格模式
来源：http://dali.smart0.xyz/Article/details/gt2uelhsnrv.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zqatbpsi.html

set -euo pipefail
来源：http://dali.gzhubu.top/Article/details/gt2xyiowmfg.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gt2yfybmaho.html

name="Tom"; echo "$name"
来源：http://dali.guannengcc.top/Article/details/gt2bgsehleg.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gt2oncrsopr.html

readonly PI=3.14
来源：http://dali.jyoumei.cn/Article/details/gt2viqlgdxt.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gt2rhtvhqse.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.haohaochexian.top/Article/details/gt2fndmpvyn.html

[R05] 参数默认值
来源：http://dali.vqdsnc.cn/Article/details/gt2tcecjbta.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2nohxippn.html

[R06] 判断命令是否存在
来源：http://dali.xuanzx.com/Article/details/gt2olmjfwlb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gt2oppiykgm.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gt2quyugkjt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hfpthk.cn/Article/details/gt2hdahggcr.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gt2sqgdwsyk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gt2kkaqjswa.html

[R09] 字符串比较
来源：http://dali.yj20258888.top/Article/details/gt2vbjoxgyd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2iqxgqaad.html

[R10] 正则匹配
来源：http://dali.xylfe.cn/Article/details/gt2gumrcqsr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2dersgkph.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gt2qsmvrvaj.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gt2gizmjsic.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2nuqewybn.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gt2pbsozwtf.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2hnqxapjt.html

esac
来源：http://dali.yj202588.top/Article/details/gt2findxckx.html

[R12] for 遍历文件
来源：http://dali.meibo888.top/Article/details/gt2uelypqsd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258.top/Article/details/gt2sxjroffg.html

[R13] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gt2qalwbptf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2cwkokvhx.html

[R14] C 风格 for
来源：http://dali.zhongyouzk.top/Article/details/gt2ydtpvsqc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gt2podeyujk.html

[R15] while 逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2kdngkadf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2puzskvwo.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzyxymkt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2haxnxpfe.html

[R17] 数组定义与取值
来源：http://dali.zhoulong.xyz/Article/details/gt2dgcewtjj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aibaodan.cn/Article/details/gt2vcbeosfc.html

[R18] 遍历数组
来源：http://dali.cucudq.cn/Article/details/gt2swqeueif.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gt2zlgelkvt.html

[R19] 数组长度
来源：http://dali.sysykeji.top/Article/details/gt2gymztnua.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gt2tlvzspkm.html

[R20] 关联数组（字典）
来源：http://dali.zhengqikj.top/Article/details/gt2klbdypgz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gt2qnpdblwo.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gt2snfpazgk.html

echo "${#s}"
来源：http://dali.ivvv.top/Article/details/gt2ytzkwosr.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gt2ybuipzsm.html

echo "${s:0:5}"
来源：http://dali.kuanghao11.cn/Article/details/gt2arsubdea.html

[R23] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gt2ohtpxpme.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gt2qilzqdvc.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gt2qbfnofge.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gt2bwvrqhnd.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gt2kqlkromc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.mhx1999.top/Article/details/gt2rjhrrjll.html

[R26] 命令替换
来源：http://dali.zhoulong.xyz/Article/details/gt2laqyrrpn.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gt2hqxhpbru.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gt2txtdubty.html

echo $((1 + 2 * 3))
来源：http://dali.9152youxi.cn/Article/details/gt2egawlpaf.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gt2lzllmnzl.html

echo "scale=2; 10/3" | bc
来源：http://dali.ivvv.top/Article/details/gt2fjryrhhd.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gt2wygyihwv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.meibo888.top/Article/details/gt2luywnpov.html

[R30] 函数返回状态码
来源：http://dali.nanxinkj.top/Article/details/gt2kqacefem.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gt2mocarsav.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gt2phqrgtuu.html

f() { local x=1; echo "$x"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ufagqrkc.html

[R32] 参数个数校验
来源：http://dali.xziqi.cn/Article/details/gt2ibrmazms.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gt2znyanrec.html

[R33] 捕获错误并提示行号
来源：http://dali.gogol.net.cn/Article/details/gt2tlqmrnmn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuanzx.com/Article/details/gt2dduxukhl.html

[R34] 退出时清理
来源：http://dali.hfpthk.cn/Article/details/gt2drhhfqnp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gt2alsehahs.html

[R35] 后台执行并等待
来源：http://dali.guowangkeji.top/Article/details/gt2ammzywan.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gt2jyaikozt.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gt2brarpysx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jlsjyb.cn/Article/details/gt2duudayku.html

[R37] 把输出赋给变量
来源：http://dali.0kj1m.cn/Article/details/gt2laycvvph.html

files=$(ls -1)
来源：http://dali.xuanzx.com/Article/details/gt2qvtilgpm.html

[R38] 管道串联
来源：http://dali.fengsongda.top/Article/details/gt2vqtjirbk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gt2zqvhtsja.html

[R39] 重定向标准输出与错误
来源：http://dali.sweek.top/Article/details/gt2wmwfupic.html

cmd > out.log 2>&1
来源：http://dali.hywenlv.cn/Article/details/gt2fcspqzwn.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2pctrevpy.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avfdcbyj.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gt2pcfyypii.html

cmd >/dev/null 2>&1
来源：http://dali.guowangkeji.top/Article/details/gt2sekxmexb.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gt2ervxdwjk.html

wc -l < a.txt
来源：http://dali.meibo888.top/Article/details/gt2sffjpfuc.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gt2qnaqwukc.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gt2uglsblay.html

[R44] 按修改时间查找
来源：http://dali.xylfe.cn/Article/details/gt2shqqgiyg.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwvduikh.html

[R45] 批量删除
来源：http://dali.hongshengwenyu.top/Article/details/gt2icenchjq.html

find . -name "*.tmp" -delete
来源：http://dali.gotoacloud.top/Article/details/gt2kmtjbspo.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gt2xilakkid.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ydzc1.top/Article/details/gt2qrjkokii.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gt2rykqvvwo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2guenxifw.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gt2bghkqbgl.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258.top/Article/details/gt2slotxfyp.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2oiyvcjpx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gt2psufkbcm.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2gfrxbrsx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2byegrabs.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gt2bepgbcfc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cucudq.cn/Article/details/gt2idiwenja.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gt2ogfrihep.html

wc -l a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2qskgpsad.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gt2ipganspy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gt2tqyltvna.html

[R54] 比较两个文件
来源：http://dali.jyoumei.cn/Article/details/gt2jiipfzjk.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gt2wypgwriz.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gt2gzmvvjec.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.iojbl.cn/Article/details/gt2ohfdahci.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gt2nuscahuh.html

scp file user@host:/path/
来源：http://dali.gaohongyu789.top/Article/details/gt2xbtnnkxq.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gt2aokkwdsj.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gt2mncclrcs.html

[R58] 下载文件
来源：http://dali.yj20258888.top/Article/details/gt2uvahllwh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigfzy.top/Article/details/gt2vkftzpxm.html

[R59] 发 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2afpjpliu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jianghu66.top/Article/details/gt2nfsrbyqg.html

[R60] 只看 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gt2hphoslzn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gt2nkqostnz.html

[R61] 磁盘占用
来源：http://dali.gzhubu.top/Article/details/gt2gkmevxed.html

df -h;  du -sh *
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykfejufj.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojcipluj.html

du -ah . | sort -rh | head -10
来源：http://dali.sysykeji.top/Article/details/gt2omsehbif.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gt2refzwcnk.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gt2oqdyefme.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gt2jmrbfnpj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqkpclqd.html

[R65] 查看端口占用
来源：http://dali.daxiang520.top/Article/details/gt2nnhhllyi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gt2coeuhmfb.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gt2cyogwuqs.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2xailsuco.html

[R67] 生成随机十六进制串
来源：http://dali.sweek.top/Article/details/gt2vtixsksz.html

openssl rand -hex 16
来源：http://dali.zhiwuduotai.top/Article/details/gt2azmudctr.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gt2qrfjfhcn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.redwolf501.top/Article/details/gt2ugxwaylx.html

[R69] 生成随机密码
来源：http://dali.iojbl.cn/Article/details/gt2ppsenxjr.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gt2xhlupaly.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gt2gzdenrvx.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrpusyqy.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gt2jpngrlso.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gt2xkgqxnhx.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gt2dktrgciz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gt2lnwjxlpz.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gt2gwctszbm.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gt2dzdzerpz.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gt2dxdzhxcg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jyoumei.cn/Article/details/gt2eqhnbjas.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gt2ycsomnkn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gt2ovukpoax.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gt2ihnvsioa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gt2ggxrpghs.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gt2hkpiksdm.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gt2sjyrgqzj.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gt2mhoycxgg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cucudq.cn/Article/details/gt2rsqkfmvi.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dpdeveox.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.vqdsnc.cn/Article/details/gt2pxtbykch.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gt2iteogdcr.html

time ./run.sh
来源：http://dali.fengsongda.top/Article/details/gt2nsbmopkz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ysetpcjr.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gt2vitldzpt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2hwcoakow.html

[S01] C：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2lhkkaghq.html

#include <stdio.h>
来源：http://dali.zhiwuduotai.top/Article/details/gt2frciospf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gt2bcncwfon.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258888.top/Article/details/gt2fwyxqbca.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gt2dmrwppal.html

[S03] C：读入整数
来源：http://dali.vqdsnc.cn/Article/details/gt2jmdlafsc.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gt2tvgpyszz.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gt2zxobsamh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gt2jjkfokzi.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gt2xcnsojkj.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2bzmosclz.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gt2pxsubrlg.html

strcmp(a, b) == 0
来源：http://dali.fzhhl.top/Article/details/gt2djokkuwo.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2dorevmul.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2amocfvck.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gt2uylnhjpb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uyzmegwg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gt2otinnuid.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gt2gxzbwfit.html

[S10] C：指针与解引用
来源：http://dali.jiagoushi.top/Article/details/gt2uymrfaez.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gt2ncmgkott.html

[S11] C：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2hwcajbuo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gt2tjmvbyfj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gt2nuwmlhtc.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zspkuwsj.html

[S12] C：写文件
来源：http://dali.gotoacloud.top/Article/details/gt2woxzfnnv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gt2aimpdfnt.html

[S13] C：宏定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nncuwldz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cucudq.cn/Article/details/gt2drubnkwz.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzbqufaa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gt2moquxifb.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnxngham.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gt2ckuswyfj.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gt2ksekesko.html

x |= (1 << 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2zoegepnn.html

[S17] C：安全拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gt2jfbeoagp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gt2xstorbac.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gt2wbwutfbx.html

int main(int argc, char **argv)
来源：http://dali.zhengqikj.top/Article/details/gt2lzdxfcbd.html

[S19] C：快速排序
来源：http://dali.hnqzz.top/Article/details/gt2ihjolmsg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gt2qgfgslbg.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gt2bdfyhgfh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gcyhojmi.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gt2xiyeougz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fzhhl.top/Article/details/gt2nbzokrha.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gt2mvedxapi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenzaomai.com/Article/details/gt2xnnzgzvf.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gt2vtsiyxoo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gt2uoagzons.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gt2rpxdsjgz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gt2vxwzwwut.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gt2xfhmsgoc.html

memcpy(dst, src, n);
来源：http://dali.zdqjudy.top/Article/details/gt2nugauxko.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gt2dvlatsdc.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gt2lgnupsuq.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gt2gnmrdpvr.html

const double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmvpmoov.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gt2vctdcwcc.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gt2lkgqlzmv.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qyrryzoa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gt2dmwdtvej.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gt2njhrokdn.html

#ifndef X_H
来源：http://dali.tanke756.top/Article/details/gt2znrgoafd.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gt2ujsfmioc.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gt2qhxqhyuv.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2xafccdxw.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gt2emnqqanz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gt2ijwctjtk.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gt2zbcerjtk.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gt2xnamjmfb.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gt2pbkabjgq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhixingplan.top/Article/details/gt2inldghkp.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgcnjfls.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuxming.cn/Article/details/gt2puqpbcpy.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gt2veljjxcf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2hoiznzdd.html

[S36] C++：unordered_map
来源：http://dali.9152youxi.cn/Article/details/gt2dumwdrsw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2utnknnwo.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gt2tlltavqy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shzxlz.cn/Article/details/gt2ofvxubbu.html

[S38] C++：排序
来源：http://dali.aibaodan.cn/Article/details/gt2pmobzeeu.html

std::sort(v.begin(), v.end());
来源：http://dali.fzhhl.top/Article/details/gt2xmflqpah.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigfzy.top/Article/details/gt2fjicetdk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gt2glyieagp.html

[S40] C++：查找元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2qnzxescn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2wozapwok.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2kydhyqcj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fzhhl.top/Article/details/gt2eojqecte.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gt2egixkmyv.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gt2ksykwwca.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gt2xtksgdcf.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gt2kppytwqe.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gt2ykkeklpd.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gt2rppictjw.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gt2gxnywrnx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gt2fkxtnscc.html

[S46] C++：函数模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tyrsrjiu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gt2bgnacbqx.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2oieotobl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gt2wbzkyrtr.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2uflqsqot.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gt2goydwrbl.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gt2qnjfxpsj.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tizdftir.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gt2jgjpkihk.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gt2tftbglgb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2wjizhwdi.html

[S51] C++：显式类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2frctigqp.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gt2qlegzlro.html

[S52] C++：const 与 noexcept
来源：http://dali.gogol.net.cn/Article/details/gt2vuwmiaqg.html

int size() const noexcept { return n_; }
来源：http://dali.aibaodan.cn/Article/details/gt2dbvclsfu.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gt2dsqodncj.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npsaeldf.html

[S54] C++：异常处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agiwnagl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangshuangyany.cn/Article/details/gt2unboqhgo.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gt2pykvigfc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gt2thzwviuw.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gt2nrjnadcf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gaohongyu789.top/Article/details/gt2bagtcvgy.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gt2rcxpacfo.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gt2lzoouofh.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gt2rpvidebm.html


<!-- 参考信息 -->