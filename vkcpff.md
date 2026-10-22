代发 wailian999

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2phukfzci.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hztthpcr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayibogfi.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qfigaacf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgnslxj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhqokvh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjgyeny.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfddbpf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kmezdvis.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2otcildip.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rndwlelh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zijagvnn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2stdxyzec.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2irhfvfvu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jlldofbf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2eifnuhux.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kgftemil.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoonylpq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bosdbmwk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2evpustmd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2avmamfot.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2suyadmpd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2twrrqsnb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nqothcyi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmcahse.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiszgry.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvhbiyd.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfksdlb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcdkbui.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzheghku.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkjrlkp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tplfxtpn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2akxlsbam.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtonqqa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2czuzfhet.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eqeondak.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vimwfjit.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnhspfw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwimort.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmmrpqf.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfobvfo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ngawgbmb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqydgyd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiumxzy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qilgysdo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iywcpjdw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxogmmc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kvidspmd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eljttmcn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjbnvrh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdoeznv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2uingnwin.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfisfug.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2psivevve.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2sracxvet.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2umobdtqi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbbxifs.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2esfrtshk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2htqhmhkb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwwaptm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzqdffs.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlakrhs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqousmhq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaafurd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjzklrn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrongil.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqxoddd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2igdjulhw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjfwtnt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqmervk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmuhmrl.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ittxomkt.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnrsrgk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2oraaofuv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2omqcudqr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcuruli.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2poffwhis.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gchgcnky.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zrczoqfx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxbfboy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kykmcdzt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bioorlbj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuxavlb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlnjfec.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2envclywt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2guhrpwne.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fzawnwol.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2stbafcls.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2itquxzme.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pyorzhnz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnmrbel.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmgfebr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnrrrzw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxdsdyz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zfspaxzh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcnvagc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfdxvlu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzdbuqo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgcqnkd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ochxpzjj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmtmpma.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wseaugos.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmebefk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwxxirh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2igdnqwca.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nytmaazt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqnfzox.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdxiact.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqneowk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hqinnkha.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hcntoiiq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qcohwygb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vvchuems.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ecltcnet.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mysnljpu.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2onwaehha.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjroawr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbhirpz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mttkvvzc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ytscopxq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2uomitniz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnumgnt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2txzjrszl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkrbgfo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvtyjsy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpzwsmt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bokvfeip.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiqrhpj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdxaiad.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ytftmctk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlffqfb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ughaekmf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qefvlcqo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgkgimy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmazxup.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qknsiqsb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2obhtevcq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrelqny.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoglfdu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dghlscqc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qokptxxm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vzllvkrv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2toakbhnl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fsowqnny.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpiuttn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mewnnluf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjafoyd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aihweajm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbyuovd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pubrnieq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgmsfbe.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mwikxnrh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2siwpamsm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dikspkcj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2alvijera.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2urkpgilz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tznkvdhu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvroram.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwfnhkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pclfpchy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdfmvqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbddhjvs.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvccksw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjxegjo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwibpig.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2naaiievp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xroiitej.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2spgadije.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtqerty.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zzovlsve.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbjxaiw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dutmibpy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyyabvr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfdsggp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoqvmpi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ildlbfod.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tfopkqii.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjrqebk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2csgehblb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnylumu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwvfcmp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tanycveh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2idgehody.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycepmxeb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkhlaji.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2njydikgi.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmhvhaz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbobgjlq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyfkqpd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ysslgxdy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqszrww.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfqtkfi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hitxqota.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlduzlz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vyegytwu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcnpsud.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2orwveoyh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbwuijy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxcqnis.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2quqalhxd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqpcimz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gzimhreh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzrozeh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jigdliaz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mljjfayw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2usoetgdy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxupnad.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oglsdfvb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2msmbtwhq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpjmjrd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvonxqb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpptgyx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvgxqou.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkyaroj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjkwsjl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wibgfpvo.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2onassbto.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2brdxwxwe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2itwxeawv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wddvqdnb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwfemwm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsmvjbi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzenouyo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbvuuuh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyrqibx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdittpn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxdgthe.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qqazyugq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvkswnc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcszxpw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvwbkpw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xusdlemf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dovatkla.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyfabom.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbdxols.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjxoklc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ushadhha.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvivwkbp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kixqaxwl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2skqwkkqq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ljymcmgq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbcrprv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2absuucie.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwnftmq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2efhvmhxo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlfxwye.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaizolq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaiqrho.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exdetfkl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnddcks.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxfvqlt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfqkfmo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lgilwtsl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwamuid.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ibktaegm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quicjxpc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2simwmxps.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbwlkvi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdsrgqh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gikjkfbm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqdxtep.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsfynay.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ughishwi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpkyohd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2clzitysm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmldkre.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrwenlp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2takaiupf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzzogxd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2thhqhete.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uwijbbec.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqcgfla.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcekmbsc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbssyhi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2egipklsm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mpldrsyb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2czssscpl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmzxuqr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzkvndo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yjetggpq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaxqpti.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nelmcpby.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nppgjsdv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbjqlne.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ictfnxwz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpvwxpy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hynyjlxx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ysikcdvk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2edabsnwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnemgquk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjbvzxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yccxmmlm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dglodulu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwqekuh.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrgpmnd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2glocwsyl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrejlbr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfzyued.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdfefan.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkxjmqx.html


<!-- 参考信息 -->