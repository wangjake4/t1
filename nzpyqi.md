代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.sysykeji.top/Article/details/gt2uraeerlc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gt2zglalpep.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nswkuvzk.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgaynsjb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gotoacloud.top/Article/details/gt2ndvqnjfs.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gt2ohtaajvk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zopbsjaz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2cktozgtq.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gt2dfwuqtof.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2lckjitvy.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmxmuri.html

#!/usr/bin/env bash
来源：http://dali.yangfankeji.com/Article/details/gt2shnsbpxf.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2alzwuhhf.html

[R02] 变量赋值与使用
来源：http://dali.fzhhl.top/Article/details/gt2qyhdnbim.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gt2eqfgnnxq.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gt2waruummv.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxrteigo.html

[R04] 位置参数
来源：http://dali.svipenyu.cn/Article/details/gt2covkutao.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gt2idxoiqbl.html

[R05] 参数默认值
来源：http://dali.cashguo.top/Article/details/gt2qtaqbfpb.html

name="${1:-default}"
来源：http://dali.9152youxi.cn/Article/details/gt2uoontkyp.html

[R06] 判断命令是否存在
来源：http://dali.fzhhl.top/Article/details/gt2cdknldbw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gt2trybpizz.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gt2caldhlvp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gt2mhrcxfpq.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjifnypw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuxming.cn/Article/details/gt2miadqtcu.html

[R09] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gt2ydyywhxi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gt2kegdnzxk.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gt2zajvxetx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2vxnnnitv.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gt2snbvdscd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyswgyh.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gt2wmoxpkpt.html

stop)  echo "停止" ;;
来源：http://dali.aizwys.cn/Article/details/gt2utksgxvt.html

*)     echo "未知命令" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xolnqnor.html

esac
来源：http://dali.zycfv.cn/Article/details/gt2czuitmbt.html

[R12] for 遍历文件
来源：http://dali.zdqjudy.top/Article/details/gt2qdqgerma.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yueranfly.top/Article/details/gt2obodflql.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gt2dwzsgetq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gt2powithrw.html

[R14] C 风格 for
来源：http://dali.pycfn.com/Article/details/gt2rlqgcwqd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gt2tucdixnv.html

[R15] while 逐行读文件
来源：http://dali.wangdashe.top/Article/details/gt2esdiijwq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2bkpjrgjw.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gt2zqimhycg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gt2wuzqrajg.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gt2etfgltni.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sweek.top/Article/details/gt2oeghiunl.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gt2bliephkj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2lmrfbpwt.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gt2ygpwezgq.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gt2mmqaiwdj.html

[R20] 关联数组（字典）
来源：http://dali.birdmap.top/Article/details/gt2awvuumnx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2khzoiakz.html

[R21] 字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2grjwgssf.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gt2eeozdlkp.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gt2sneuimjn.html

echo "${s:0:5}"
来源：http://dali.cdnleiting.top/Article/details/gt2mgijjvaf.html

[R23] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gt2ybtmlyjn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2aniihvmm.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2hbtzuido.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gt2cleavzps.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxmewiac.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gt2plmztuwe.html

[R26] 命令替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2inltemuw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gt2qnshqioj.html

[R27] 算术展开
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rlcmhfiq.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gt2irvogfkk.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gt2ccopniyy.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gt2dbpsmwbg.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gt2wtbkgazy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gt2myybixtx.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gt2qiwfmuhd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gt2aqlzietk.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gt2wduduufa.html

f() { local x=1; echo "$x"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrywrvub.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gt2rbgpaueo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gt2zszybpme.html

[R33] 捕获错误并提示行号
来源：http://dali.hammf.cn/Article/details/gt2rxsfsura.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gt2kuyryyzd.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gt2vuzpgauz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gt2qybfebgx.html

[R35] 后台执行并等待
来源：http://dali.pengpengdd.cyou/Article/details/gt2pokbvpbn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.316326.xyz/Article/details/gt2cyzdotro.html

[R36] 并发执行多个任务
来源：http://dali.aizwys.cn/Article/details/gt2jbbqagic.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigufen.top/Article/details/gt2fqkeaidz.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gt2aitjoapa.html

files=$(ls -1)
来源：http://dali.chenzaomai.com/Article/details/gt2vnhpvvvx.html

[R38] 管道串联
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hunovdll.html

cat a.txt | grep -i error | wc -l
来源：http://dali.quarkkingdee.top/Article/details/gt2icgfwfai.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gt2cmxkjnzl.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gt2qdecjtkq.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gt2nkasjueb.html

echo "log" >> out.log
来源：http://dali.jiagoushi.top/Article/details/gt2ofaghyrn.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gt2nsiamjtd.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2gqbrikic.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gt2swxytgnp.html

wc -l < a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqmurmhb.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gt2zfuxwmsb.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gt2hcsukqli.html

[R44] 按修改时间查找
来源：http://dali.zhoulong.xyz/Article/details/gt2xxxfptlv.html

find . -mtime -7 -type f
来源：http://dali.316326.xyz/Article/details/gt2mujgmfnd.html

[R45] 批量删除
来源：http://dali.iojbl.cn/Article/details/gt2igptrlrk.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gt2azplaihj.html

[R46] 递归替换文件内容
来源：http://dali.yj20258888.top/Article/details/gt2cnvveedf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hywenlv.cn/Article/details/gt2dizsrujx.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gt2oufagujk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2fjkcvtzo.html

[R48] awk 取指定列
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmxlxovo.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2buyxyxcc.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gt2tanmpyba.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gt2xwbgtwwo.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gt2etkxokix.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2ytulykny.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxkvobwo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gt2sooyuzhz.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gt2njgddzmk.html

wc -l a.txt
来源：http://dali.yvedp.cn/Article/details/gt2qimheisa.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gt2ylvyygno.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gt2rqvqjlcl.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gt2ihkkbgcy.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2dcqwkypa.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljumdezg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zycfv.cn/Article/details/gt2nxkwroju.html

[R56] 远程拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqvkrlbh.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gt2xcqvsxvg.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gt2rspnffss.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gt2sziyzemc.html

[R58] 下载文件
来源：http://dali.yuanzhike.top/Article/details/gt2qiftekkd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqmjjruv.html

[R59] 发 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gt2rvpncbfj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cashguo.top/Article/details/gt2bwxhvzwq.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gt2ltvmajve.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.redwolf501.top/Article/details/gt2tacyquju.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gt2romyuubm.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gt2wrirzqds.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gt2nlchgnac.html

du -ah . | sort -rh | head -10
来源：http://dali.mhx1999.top/Article/details/gt2zywurrwp.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gt2dguonynl.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gt2lteuwqjk.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gt2etxkdxny.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gt2kuzjyhih.html

[R65] 查看端口占用
来源：http://dali.iojbl.cn/Article/details/gt2jmtwoxmd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gt2kjdzevxq.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gt2eubmwnkt.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gt2jquhuesh.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gt2kjmnlvor.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gt2gtxcqhjw.html

[R68] 计算文件校验值
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcimjrfo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2hyvmkidp.html

[R69] 生成随机密码
来源：http://dali.hammf.cn/Article/details/gt2vxqefsuy.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gt2mjdprwqq.html

[R70] 时间戳与互转
来源：http://dali.svipenyu.cn/Article/details/gt2uvpgsxfz.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gt2kbgrueoo.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2xnptpycz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gt2ydwrzlkz.html

[R72] 等待端口就绪
来源：http://dali.gzhubu.top/Article/details/gt2htqghtdr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gt2ixlzohjz.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gt2mhaulmoz.html

split -l 1000 big.log part_
来源：http://dali.nanxuanxn.top/Article/details/gt2vcmnwxfe.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gt2ioasyjpd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dianchejie.cn/Article/details/gt2sqivabzy.html

[R75] 导出环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2vwzwbjmf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ehwqpu.com/Article/details/gt2ikyzoezo.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gt2mumllxyk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gt2rlsqvhgs.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gt2nihlvzzm.html

read -rp "请输入: " ans
来源：http://dali.quarkkingdee.top/Article/details/gt2jzkfecrb.html

[R78] 交互式菜单
来源：http://dali.iojbl.cn/Article/details/gt2dowlkudm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gt2ywxzshjz.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gt2kltbbuxx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.meibo888.top/Article/details/gt2fwgltfsp.html

[R80] 查看脚本执行耗时
来源：http://dali.ehwqpu.com/Article/details/gt2vfneqtnr.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gt2gvialdhm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2blkjprfc.html

S. C / C++ 专题
来源：http://dali.cdnleiting.top/Article/details/gt2yggbxprv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2kgxgoshj.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2dpilqvmn.html

#include <stdio.h>
来源：http://dali.cheryme.top/Article/details/gt2ibtajrbb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gt2fsefjcty.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gt2arikgglc.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gt2dytaflxf.html

[S03] C：读入整数
来源：http://dali.fengsongda.top/Article/details/gt2unoxljhx.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gt2civjkotw.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gt2ddauwede.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2ypdtmilo.html

[S05] C：字符串长度
来源：http://dali.cheryme.top/Article/details/gt2efxvpkpv.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gt2sznzhjcp.html

[S06] C：字符串比较
来源：http://dali.wangdashe.top/Article/details/gt2uivlaqox.html

strcmp(a, b) == 0
来源：http://dali.tianlin.xyz/Article/details/gt2brfuujzn.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gt2xfrfigse.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gt2xctugqco.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gt2vyjjncfq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ydzc1.top/Article/details/gt2udtriwpl.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gt2xkltsidq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gt2vgrkbwlw.html

[S10] C：指针与解引用
来源：http://dali.jqgfzy.top/Article/details/gt2ymwjuwwh.html

int *p = &a;  *p = 5;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpxuystd.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ciprmxew.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tian-w.cn/Article/details/gt2pvzvpvhs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gt2kcftlidi.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gt2kfpqofqe.html

[S12] C：写文件
来源：http://dali.jlsjyb.cn/Article/details/gt2jpuppvuf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2flbdfbfv.html

[S13] C：宏定义
来源：http://dali.xylfe.cn/Article/details/gt2ckdbxqon.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzdxuqmc.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gt2svmulxjh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jiptncsr.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gt2zwgejqfl.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gt2dodgwcrz.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gt2pikgjmqw.html

x |= (1 << 3);
来源：http://dali.hammf.cn/Article/details/gt2vvyywtkt.html

[S17] C：安全拼接字符串
来源：http://dali.sweek.top/Article/details/gt2sasfvytr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gt2igrufqgi.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gt2hiotnpvf.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gt2pcqjgoia.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwbujoum.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gt2kqmgasmq.html

[S20] C：二分查找
来源：http://dali.havefunace.top/Article/details/gt2duexysxv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gt2vjoanpwt.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gt2gxgkxupo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gt2hnmnhuwy.html

[S22] C：字符串转数字
来源：http://dali.yj202588.top/Article/details/gt2tmixfbcq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shzxlz.cn/Article/details/gt2oxtholgb.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqpakyjn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jddklvjd.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gt2rgzixknj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gt2opdfjfev.html

[S25] C：内存拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svucottm.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gt2vbpecrmi.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gt2kheytiak.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gt2xbyeoiwx.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gt2lxhwrlpx.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2dmlvobns.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gt2tcqjxufq.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjtcheve.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gt2rdopiwoy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gt2cdduibgx.html

[S30] C：头文件保护
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwongstm.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gt2uuscvtpn.html

#define X_H
来源：http://dali.shzxlz.cn/Article/details/gt2qhfhrdgf.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gt2jkjfetcm.html

[S31] C++：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2kipqrwdq.html

#include <iostream>
来源：http://dali.cashguo.top/Article/details/gt2fpnjsquf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gt2nxrmltzr.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gt2rafihudz.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gt2zsfpivjr.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gt2reveveqe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmfxepwe.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gt2xvdxzlrt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gt2zbncqxix.html

[S35] C++：map
来源：http://dali.gaohongyu789.top/Article/details/gt2pcidenfo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2yaogthmu.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gt2xsluzxis.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2zswiqiik.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gt2autleudk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gt2glyzshzu.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gt2tnihpukr.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gt2zpzngpgx.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dsmwaidi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzovifi.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gt2cacbqkpn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jianghu66.top/Article/details/gt2rdfojawl.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gt2fqpnxosr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gt2jzndikma.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gt2grnmljww.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gt2ozdhvkwf.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gt2hceluycf.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gt2vlavzgta.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gt2jougdegv.html

void inc(int &x) { ++x; }
来源：http://dali.yj202588.top/Article/details/gt2tswznpme.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gt2rmutyhrt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gt2qcykkvad.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gt2jlzrlamc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gt2rehbveyu.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2kuhkbttr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.svipenyu.cn/Article/details/gt2zihcagfe.html

[S48] C++：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gt2gpnwaahq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gt2zhkemfkg.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gt2spwjjbbi.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gt2adnblcrl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hysaishi.cn/Article/details/gt2ehnlomls.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmxptxvj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2zaxekqgv.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2vtcrghmf.html

static_cast<double>(a) / b
来源：http://dali.xuetiantiany.cn/Article/details/gt2okyhgtuc.html

[S52] C++：const 与 noexcept
来源：http://dali.jlsjyb.cn/Article/details/gt2swbenviy.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ootfxzod.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwtlylgr.html

std::vector<int> w = std::move(v);
来源：http://dali.andypj.xyz/Article/details/gt2hdkyknjs.html

[S54] C++：异常处理
来源：http://dali.andypj.xyz/Article/details/gt2mywdzpqp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daxiang520.top/Article/details/gt2hhbpjbuv.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itavfcji.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xinyue.icu/Article/details/gt2yjqpxcvh.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gt2optfglpg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zdqjudy.top/Article/details/gt2bispvqiu.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gt2gmhkpmvf.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gt2vevizezn.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gt2chldiwaw.html


<!-- 参考信息 -->